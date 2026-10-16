# Winter heating cost, electric vs propane

16 Oct 2026 (revised the same day: all-in electricity prices, real-world usage, and propane at C$15 per 20 lb tank)

Propane is assumed to cost **C$15 per 20 lb tank**, the Costco refill price. At that price, **propane and electricity are close, and electricity is a little cheaper** unless it is bought at on-peak prices. Propane comes to about 15¢ per kWh of heat, against 10.6¢ to 13.2¢ for electricity on off-peak or all-week pricing.

A November to March season for a good tub in regular use costs about **C$294 on propane** (about 20 tanks) and **C$208 to C$260 on electricity**. Propane's real advantages are speed (an 11 kW burner against a 1.5 to 3 kW electric heater) and not needing a 240 V circuit, not running cost.

## Cost per kWh of heat into the water

Fixed monthly electricity charges are left out, because a hot tub does not change them.

| Fuel | Cost per kWh of heat | How it was worked out |
| --- | --- | --- |
| Electricity, off-peak | **10.6¢** | 9.8¢ commodity, plus delivery, then rebate and HST (below) |
| Electricity, heater running evenly all week | **13.2¢** | 12.7¢ blended commodity. 64% of the week is off-peak, 18% mid-peak (15.7¢), 18% on-peak (20.3¢) |
| **Propane, C$15 per 20 lb tank** | **15.0¢** | C$15 ÷ 17.8 L = C$0.84/L. Each litre puts about 5.6 kWh into the water |
| Electricity, on-peak | **20.0¢** | 20.3¢ commodity |

**Propane inputs**
- **C$15 per 20 lb tank**, the Costco refill price (Lucas, 16 Oct). Treated as the full price paid. A 20 lb tank filled to 20 lb holds 9.07 kg, about 17.8 L at 0.51 kg/L.
- Propane holds 25.3 MJ/L, which is 7.03 kWh/L ([Statistics Canada](https://www150.statcan.gc.ca/n1/pub/11-526-s/2013002/t026-eng.htm), matches the [Clean Fuel Regulations](https://laws.justice.gc.ca/eng/regulations/SOR-2022-140/page-19.html)).
- Gas spa heaters are typically about 80% efficient ([Cedar Tubs](https://www.cedartubs.com/gas-electric-hot-tub-heating.html), medium, a seller), so each litre puts about 5.6 kWh into the water. A tank puts about **100 kWh** into the water.

**Electricity inputs**
- Commodity prices: off-peak 9.8¢, mid-peak 15.7¢, on-peak 20.3¢ per kWh, in force 1 Nov 2025 to 31 Oct 2026 ([OEB](https://oeb.ca/node/5346), strong). The OEB sets new prices every 1 November. The 2026 prices were not published when we checked.
- Delivery and regulatory charges per kWh, Enova Power, Waterloo residential zone, from 1 Jan 2026 ([Enova Power](https://enovapower.com/my-account/electricity-rates/), strong): network service 1.17¢, line connection 0.29¢ and wholesale market service 0.53¢, all times a 1.0353 line loss factor. Low voltage adds 0.04¢ and rate riders 0.02¢. Together that comes to **2.12¢/kWh**. The line loss factor also applies to the commodity price.
- Ontario Electricity Rebate of **23.5%** off the bill before HST ([OEB](https://oeb.ca/node/5346), strong), then 13% HST.
- So cost per kWh = (commodity x 1.0353 + 2.12¢) x 0.765 x 1.13. An electric resistance heater puts close to 100% of that into the water.

**Break-even.** At 80% heater efficiency, propane ties with all-week electricity (13.2¢) at about **C$13.20 a tank**. At C$15 a tank, it ties if the heater is about **90% efficient** (own calc). So the efficiency of the actual heater decides how close it is.

## How much heat a tub uses in winter

**Our estimate, cover on, nobody using it.** A 300-gallon hard-shell tub held at 38.9°C loses about 8.2 W for every degree between the water and the air. That figure comes from the sample energy label in the ANSI/APSP/ICC-14 standard: 192 W on standby with 102°F water and 60°F air ([standard via CEC](https://efiling.energy.ca.gov/GetDocument.aspx?tn=74378&DocumentContentId=13143), medium, an example label, not a database average). Outdoor temperatures are the monthly daily means for Region of Waterloo airport, 1991 to 2020 normals ([Environment Canada via Wikipedia](https://en.wikipedia.org/wiki/Kitchener,_Ontario), strong).

| Month | Mean outdoor °C | Heat needed |
| --- | --- | --- |
| Nov | 2.6 | 215 kWh |
| Dec | -2.8 | 255 kWh |
| Jan | -6.3 | 277 kWh (8.9 a day) |
| Feb | -5.9 | 248 kWh |
| Mar | -0.8 | 243 kWh |
| **Season** | | **1,238 kWh** |

**Published real-world figures are higher**, because they include soaking with the cover off, wind and older covers.

| Figure | Per day in winter | Source and strength |
| --- | --- | --- |
| Well-insulated 300-gallon tub at 38°C with a 4-inch cover, Ontario | 10 to 18 kWh | [getabetterquote.com](https://getabetterquote.com/guides/hot-tub-electrical-cost-ontario/), weak, rate assumptions not checked |
| Beachcomber 520, Bullfrog A8 and Hot Spring Envoy in an Alberta winter | About 8 to 13 kWh | [Peace Power](https://peacepower.ca/blog/the-real-cost-to-power-a-hot-tub-year-round), weak, an Alberta power retailer |
| Poorly insulated entry-level tub with aging equipment, Alberta winter | About 17 to 23 kWh | Same Peace Power page |
| SaluSpa inflatable, winter, covered | 6 to 10 kWh, temperature not stated | [SaluSpa Canada](https://saluspa.ca/power-consumption/), medium, maker |
| Hot Spring calculator, International Falls MN at 35°F | About 11 kWh | [Hot Spring](https://www.hotspring.com/blog/how-much-will-my-electric-bill-increase-new-hot-tub), medium, maker's calculator, our conversion from dollars |

None of these are measured logs. They are seller estimates.

## Cost for a November to March season

| Tub and use | Heat for the season | Electric, off-peak | Electric, all week | Propane at C$15 a tank |
| --- | --- | --- | --- | --- |
| Good hard-shell, cover on, not used (our estimate) | 1,238 kWh | $131 | $163 | $186 (about 12 tanks) |
| Good hard-shell, used regularly (about 13 kWh a day) | 1,963 kWh | $208 | $260 | $294 (about 20 tanks) |
| Poorly insulated tub (about 20 kWh a day) | 3,020 kWh | $320 | $399 | $453 (about 30 tanks) |

In January alone, a good tub in regular use costs about $43 to $53 on electricity and about **$60 on propane (about 4 tanks)**.

**Inflatable, about 177 US gallons.** One owner measured about 9 kWh a day at about 7°C outdoors ([lee.org](https://www.lee.org/blog/2024/04/08/inflatable-hot-tub-electricity-costs/), weak, a single data point), which works out to about 1.4 times the heat loss of the hard-shell tub. At Waterloo temperatures that is about 1,780 kWh for the season with the cover on: $189 to $235 on electricity and about $267 on propane (about 18 tanks). It would also be running outside its maker's rated range for most of the winter (see 02).

## Why propane feels like it should be cheaper

- **It is much faster.** A propane water heater like the HOTTAP puts out about 11 kW, so it heats a tub in about 2 hours. An inflatable's electric heater is 1.5 to 3 kW and takes most of a day. That is speed, not cost or efficiency.
- **It can't beat electric on efficiency.** An electric element puts close to 100% of its energy into the water. A propane heater loses about 20% up the flue.
- **Natural gas is the cheap one.** Most "gas beats electric" advice in Ontario is about natural gas, which is much cheaper per kWh than both propane and electricity. Natural gas prices were not researched here.
- **Electricity is expensive in many other places.** Where power costs 25¢ to 35¢ per kWh, propane at C$15 a tank wins clearly. Ontario power is relatively cheap, and the 23.5% rebate makes it cheaper.
- **On-peak electricity costs more than propane.** At 20¢, a tub that heats mostly on weekday mornings and evenings would be cheaper on propane.

## What this leaves out

- Whether the C$15 includes tax. If HST is added, propane is 16.9¢ per kWh of heat and a regular-use season is about $332.
- Fixed monthly electricity charges, which a hot tub does not change.
- Wiring cost. A 240 V circuit to a tub far from the house can cost hundreds to a couple of thousand dollars, which propane avoids. Not priced.
- Heat pump heaters, which would beat both fuels on running cost. Not researched.
- Electricity prices from 1 Nov 2026, not yet published.

## Next step: measure it

Lucas's home setup can replace the weakest inputs with real numbers. Weigh the propane tank before and after heating the tub from a known starting temperature to get the real heater efficiency. Put an energy meter on the SaluSpa for a cold week to get real heat loss.

## Relevance to an automated tub

The water stores a lot of heat. A 300-gallon tub holds about 1.3 kWh per degree, so in January it cools only about 1.7°C over a 6-hour on-peak window with the heater off (own calc). A controller that heats only at off-peak prices would cut the electricity price from 13.2¢ to 10.6¢ per kWh, about 20% less, without the water getting noticeably colder. A tub with both heaters could also pick the cheaper one each hour: electricity off-peak, propane on-peak.
