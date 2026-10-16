# Powering the pump from propane

16 Oct 2026

A propane tub like Joolca still needs electricity: a 12 V pump (30 to 45 W) and batteries for the igniter. The question is whether the propane flame could also make that electricity, so the tub needs no plug, car or charged battery.

**On paper, yes, while the burner is running.** A thermoelectric generator (TEG) turns about 3% of the heat flowing through it into electricity. Running a 40 W pump takes about 1.25 kW of heat through the TEG, about 11% of the HOTTAP's 11 kW burner. The heat a TEG doesn't convert is not lost, because its cold side can be cooled by the tub water, so almost all of it still heats the tub. **It does not work for keeping the pump running all day.** That would push more heat into the tub than it needs, so a battery is still needed for when the burner is off. Everything here is own calc from the sources below. Nobody has built it for a hot tub that we found.

## What needs power

| Load | Power | Source | Strength |
| --- | --- | --- | --- |
| Joolca 12 V pump | **30 to 45 W typical** (2.5 to 3.5 A), 70 W max (5.8 A). Up to 6 L/min, 60 psi | [Joolca support](https://support.joolca.com/hc/en-us/articles/9333421952783-How-many-watts-can-the-pump-draw), [Joolca 12V pump](https://www.joolca.com/products/12v-pump) | Strong, maker |
| HOTTAP V2 igniter and LED display | 2 D-cells, which last about 3 to 6 months. Below 2.1 V combined, it won't ignite. Joolca sells a 12 V adapter that replaces the battery box | [Joolca support](https://support.joolca.com/hc/en-us/articles/360001472375-HOTTAP-V2-specifications), [12V adapter](https://www.joolca.com/products/hottap-12v-power-adapter) | Strong, maker |
| Today's power source | Car 12 V socket, or Joolca's power bank | [Joolca](https://joolca.com/products/hottub-bundle) | Strong |

One 2-hour heat-up runs the pump for about **60 to 90 Wh** (own calc).

## Ways to make electricity from propane

| Option | Output | Efficiency | Fit for us | Source and strength |
| --- | --- | --- | --- | --- |
| **Industrial propane TEG** (Gentherm Global Power Technologies 5120, used on remote oil and gas sites) | 108 W at 12 V, from 11.4 L of propane a day | **About 3.2%** (own calc: 108 W out of 3.3 kW of propane) | Proves the efficiency figure. Far too big and built for 24/7 use | [Spec sheet](https://www.lincenergysystems.com/images/Model-5120-Specification-Sheet-c.pdf), strong, maker. Range 15 to 550 W ([Gentherm brochure](https://automation-x.com/wp-content/uploads/2022/07/Gentherm-Thermoelectric-Generators.pdf?id=5249362&c=422523&h=ef28b8c066423b3a70a5)) |
| **Camp stove TEGs** (Devil Watt 10 W and 15 W, PowerPot 5 W, BioLite CampStove 3 W) | 3 to 15 W each. The 15 W unit needs 2 fans to cool its cold side | Modules are about 5 to 6% | Too small alone. Three or four 10 to 15 W units would cover a 40 W pump | [TEGmart 10 W](https://www.tegmart.com/thermoelectric-generators/propane-gas-10w-camping-stove-teg), [15 W](https://www.tegmart.com/thermoelectric-generators/propane-gas-15w-camping-stove-teg), [PowerPot review](https://geardiary.com/2013/12/16/the-powerpot-v-thermoelectric-generator-review-a-nice-dual-purpose-camping-accessory/), [Low-tech Magazine](https://solar.lowtechmagazine.com/2020/05/thermoelectric-stoves-ditch-the-solar-panels/). Medium |
| **Propane fuel cell** (Inergio 200 W solid oxide fuel cell) | 200 W, 45 g of propane an hour at full output | 35% | Overkill. 29 kg, price on request, 8 to 10 week lead time | [Fuel Cell Store](https://www.fuelcellstore.com/inergio-200w-solid-oxide-fuel-cell-power-generator), medium, retailer |
| **Battery only** (the baseline) | A 12 V 100 Ah lithium battery holds about 1.28 kWh | | About 15 heat-ups per charge at 80 Wh each (own calc). Simplest, but someone has to charge it | Battery price not researched |

## Quiet options compared

None of these is an internal combustion engine. They all burn or react propane quietly and turn heat or chemistry into electricity.

| Option | How it works | Electrical efficiency | Noise | Sizes found | Fit for a tub needing about 50 W |
| --- | --- | --- | --- | --- | --- |
| **Thermoelectric generator (TEG)** | Solid-state modules make a voltage when one side is hot and the other cold. No moving parts | About 3 to 6% | Silent if water-cooled. Some camp units use small fans | 3 W to 550 W ([Gentherm](https://automation-x.com/wp-content/uploads/2022/07/Gentherm-Thermoelectric-Generators.pdf?id=5249362&c=422523&h=ef28b8c066423b3a70a5), [TEGmart](https://www.tegmart.com/thermoelectric-generators/propane-gas-15w-camping-stove-teg)) | **Best fit.** Cheap, simple, sized right, and the tub water cools it |
| **Solid oxide fuel cell (SOFC)** | Propane reacts electrochemically at high temperature. Only a small blower moves | 20 to 35% | A supplier says you have to put your ear to the box to hear it ([Architect](https://www.architectmagazine.com/technology/products/meet-the-cleaner-quieter-backup-power-source/), vendor claim) | Inergio 200 W, 29 kg, price on request ([Fuel Cell Store](https://www.fuelcellstore.com/inergio-200w-solid-oxide-fuel-cell-power-generator)). Adaptive Energy P250i, about 8 hours per 20 lb tank, rated -40°C to 50°C ([LP Gas](https://www.lpgasmagazine.com/adaptive-energy-offers-propane-powered-solid-oxide-fuel-cell/)) | Works, but likely expensive (no prices found) and more power than needed |
| **Stirling engine (micro-CHP)** | Burner heats a sealed gas that drives a piston and alternator. Combustion is continuous and outside the engine, so there are no explosions | 10 to 25% measured ([review](https://www.academia.edu/69407323/A_review_of_Stirling_engine_based_combined_heat_and_power_technology)). 26 to 32% in free-piston prototypes | WhisperGen 44 dBA at 7 m ([Stirling Engines](https://www.stirlingengines.org.uk/manufact/manf/misc/whi.html)), under 50 dBA in other sources | Home units are about 1 kW of electricity plus 6.5 to 12 kW of heat: Microgen 1 kW + 6.5 kW ([spec](https://stirling-tech.com/engine-only-heater-natural-gas-cogeneration/)), WhisperGen 1 kW + 7.5 to 12 kW ([Modern Power Systems](https://www.modernpowersystems.com/analysis/stirling-generators-on-trial/)). Qnergy PowerGen 600 W to 5.6 kW for remote sites ([Qnergy](https://www.redhawkenergy.net/wp-content/uploads/2022/11/Qnergy-Stirling-Engine.pdf)) | Interesting. Its heat output is the same size as a propane tub heater, so one unit could heat the tub and make 1 kW. Built for home boilers on natural gas. Price and availability not checked |
| **Thermophotovoltaic (TPV)** | Flame heats an emitter until it glows. Infrared solar cells turn the glow into electricity | Single digits in propane prototypes | Silent apart from any fan | 20 W propane prototype ([SAE 1999](https://papers.sae.org/publications/technical-papers/content/1999-01-1397/)), 30 W Midnight Sun on natural gas ([Aviation Week](https://ngstage.aviationweek.com/heat-light)) | Not available to buy. Research only |
| **Battery charged from the mains** | No propane involved | | Silent | Any size | The simplest baseline. Fine wherever someone can charge it |

### The tub turns any of these into combined heat and power

Every option above wastes most of its fuel as heat. A generator throwing away 70 to 97% of its heat is normally a bad deal. Here that heat goes into the tub, which needs heating anyway, as long as the unit is cooled by tub water. That makes it combined heat and power, where overall efficiency is what counts: Microgen lists 95% overall ([spec](https://stirling-tech.com/engine-only-heater-natural-gas-cogeneration/)). So electrical efficiency matters much less than size, cost and noise. That is why a 3% TEG is a reasonable choice here (own reasoning).

## What about a mains sump pump?

Lucas asked about a LINGXIAO 0.75 HP submersible sump pump (4,000 GPH at 5 ft, sold for draining hot tubs). Its listing gives no amps. Similar 3/4 HP sump pumps draw 7.1 to 7.5 A at 115 V ([Pentair Simer 3995](https://www.pentair.com/products/residential/water-supply-disposal/water-disposal-pumps/simer-3995-3-4-hp-thermoplastic-submersible-sump-pump-tethered-switch.html), [Goulds LSP07](https://www.supplyhouse.com/Goulds-Pumps-LSP0711F-LSP07-Series-Submersible-Sump-Pump-3-4-HP-115V-1-PH-57-GPM-20-Cord), strong, maker and distributor), which is about **860 W**. Motors also draw several times that for a moment when they start.

- **No quiet propane option runs it directly.** It needs about 20 times what a 40 W TEG makes and about 4 times a 200 to 250 W fuel cell. A 1 kW Stirling unit covers the running power but probably not the starting surge.
- **A battery and inverter can run it.** Draining the 908 L tub at about 150 to 250 L/min takes about 4 to 6 minutes, about 0.1 kWh. A 12 V 100 Ah lithium battery (about 1.28 kWh) covers about a dozen drains, and a 40 W TEG puts back one drain's worth in about 2 to 3 hours of burner time. The inverter has to handle the motor's starting surge (own calc).
- **It's the wrong pump for circulating water through the heater.** It moves up to about 250 L/min, against the 6 L/min that a 1.58 GPM shower heater is built for. Joolca warns that pumps of 30 to 60+ L/min cause problems for its heater ([Joolca support](https://support.joolca.com/hc/en-us/articles/5482993757199), strong). Run around the clock it would use about 20 kWh a day, more than the tub needs to stay hot in winter. Being submerged, nearly all of that ends up heating the water, so it would act as an 860 W electric heater at electricity prices (own calc).

So keep the sump pump for draining, plugged in or on a battery, and use a 30 to 45 W 12 V pump for circulating through the propane heater.

## Why a TEG suits a hot tub in particular

- **The waste heat is not wasted.** A TEG on a camp stove throws away about 95% of the heat flowing through it. On a hot tub, the cold side can be cooled by the water being pumped into the tub, so that 95% still heats the tub. The electricity is close to free (own reasoning, not tested).
- **The burner and pump run together.** The pump only has to run while the burner heats. So the TEG only has to make power at the same time the flame is lit, which removes most of the need for storage.
- **The size works out.** 40 W at about 3% needs about 1.25 kW of heat, a small slice of the HOTTAP's 37,500 BTU (11 kW) burner.

## Where it breaks down

- **Holding temperature all day.** Making 40 W around the clock at 3% puts about 30 kWh of heat a day through the TEG. A tub only needs about 9 to 20 kWh a day even in a Waterloo winter (see 03). So the TEG can't power a pump that runs continuously without overheating the tub. A battery would carry the pump, sensors and controller between burns.
- **Always-on electronics.** An IoT controller and sensors need a few watts all the time, not just while the flame is lit. A small battery charged by the TEG during each burn would have to cover the gaps.
- **Where a plug is available, it isn't needed.** For an Airbnb tub next to a house (see 05), mains power is simpler. The TEG matters for off-grid spots: campsites, cottages with no outlet near the tub, events.
- **Not tested.** No hot tub product with a propane TEG was found. Real output depends on how hot the TEG's hot side gets and how well the water cools its cold side.

## Gaps

- Prices for TEG modules and a heat exchanger suitable for this.
- How hot the HOTTAP's flue or casing gets, and whether a TEG can be mounted on it without voiding certification.
- Pump and controller energy for an always-ready rental tub, as opposed to a 2-hour heat-up.
