# Filling from a lake

16 Oct 2026

What if the unit could pump lake water into the tub itself? **The pumping is easy. The hard parts are keeping the water safe and draining it without harming the lake.** The same 12 V pump that runs the heater can fill the 908 L tub in about 2.5 hours from up to 1.8 m above the lake surface. No permit is needed at this volume. Lake water at 39°C must be sanitized to hot tub standards, must never be used during a blue-green algae bloom, and must be dechlorinated and drained onto land, never back into the lake.

## Pumping

| Option | Fill time for 908 L | Power | Notes | Source and strength |
| --- | --- | --- | --- | --- |
| **12 V pump on shore** (Joolca-type, up to 6 L/min) | **About 2.5 hours** | 30 to 45 W, about 0.1 kWh per fill | Self-primes from up to **1.8 m below** the pump, so it must sit within 1.8 m above the lake surface. Can then push water up to 30 m uphill. Small enough to run from a battery recharged by a TEG (see 06) | [Joolca 12V pump](https://www.joolca.com/products/12v-pump), strong, maker. Fill time and energy own calc |
| **Submersible pump in the lake** (0.75 HP sump pump) | About 4 to 6 minutes | About 860 W | No suction limit, because it pushes from the lake. Needs mains power or a large battery and inverter (see 06) | Power from similar 3/4 HP pumps, see 06 |

Either way the intake needs a strainer held off the lake bottom, so it doesn't pull in sediment, weeds or small animals. The pump also needs protection against running dry when the intake comes out of the water.

## Heating lake water

Lake water is colder than tap water for much of the year. Heating 908 L to 38.9°C (own calc, with the 9.6 kW shower heater from 07 and propane at C$15 per 20 lb tank from 03):

| Lake water temperature | Heat needed | Time on propane | Propane cost | Time on the 1.36 kW electric heater |
| --- | --- | --- | --- | --- |
| 20°C (summer) | 20 kWh | About 2 hours | About C$3.00 | About 15 hours |
| 10°C (spring, fall) | 30.5 kWh | About 3.2 hours | About C$4.60 | About 22 hours |
| 4°C (near freezing) | 37 kWh | About 3.9 hours | About C$5.50 | About 27 hours |

Electric times are heat ÷ 1.36 kW, ignoring losses, so real times are longer, especially in the cold.

## Keeping the water safe

| Issue | What the source says | Source and strength |
| --- | --- | --- |
| **Hot tubs breed bacteria** | Legionella grows best in water at 25°C to 42°C (77°F to 108°F), which is hot tub temperature. A poorly kept tub can expose people to it even if they never get in. Pseudomonas causes "hot tub rash" | [CDC, hot tub rash](https://www.cdc.gov/healthy-swimming/prevention/preventing-hot-tub-rash.html), [CDC operator guidance](https://cdc.gov/healthy-swimming/toolkit/operating-public-pools-hot-tubs-and-splash-pads.html), strong |
| **Sanitizer targets** | Free chlorine at least 3 ppm, or bromine 4 to 8 ppm. pH 7.0 to 7.8. Replace all or part of the water weekly to monthly depending on use | [CDC](https://www.cdc.gov/healthy-swimming/prevention/preventing-hot-tub-rash.html), strong |
| **Lake water is dirtier than tap water** | Owners report lake water arriving brownish and clearing once chlorinated, and use a sediment filter on the fill hose. The organic matter likely uses up chlorine faster than treated tap water (own inference), so test more often | [Lake Winnipesaukee forum](https://www.winnipesaukee.com/forums/archive/index.php/t-28150.html), weak, owner reports |
| **Iron and metals** | Hose-end pre-filters are sold for metal-heavy rural water, rated at 2 GPM or less. One reviewer said the filter cleared the iron the first time but not the second | [Product page](https://thepoolshoppe.ca/shop/pro-aqua-hot-tub-pre-filter/), weak |
| **Blue-green algae blooms** | Ontario says to assume a bloom is toxic, avoid contact, and not bathe or swim in the water. Boiling does not destroy the toxins, so heating the tub won't make bloom water safe | [Ontario, blue-green algae](https://www.ontario.ca/page/blue-green-algae), [Lake Simcoe monitoring report](https://www.ontario.ca/document/lake-simcoe-15-year-monitoring-report/aquatic-life), strong |

The bloom rule is a hard limit: the unit must not fill from the lake during a bloom or a local health advisory. Whether a cheap sensor can detect a bloom was not researched.

## Rules in Ontario

| Rule | Detail | Source and strength |
| --- | --- | --- |
| **Taking lake water** | A Permit to Take Water is needed only for 50,000 L a day or more, and domestic use under 379,000 L a day is exempt. One 908 L fill is about 2% of the lower limit, so no permit is needed | [Ontario, water taking permissions](https://www.ontario.ca/page/environmental-permissions-water-taking), strong |
| **Never drain into the lake** | Hot tub water can contain chlorine, bromine, salt, algaecides and nonylphenols, which are toxic to fish, amphibians, birds and aquatic plants. In many provinces hot tub water is classed as grey water | [Love Your Lake](https://loveyourlake.ca/help-your-aquatic-neighbours-how-to-properly-drain-a-hot-tub/), [Watersheds Canada](https://watersheds.ca/hot-tubs-pools-and-freshwater-how-to-properly-drain-your-water/), medium, conservation groups |
| **How to drain** | Stop adding chemicals 1 to 2 weeks before, leave the cover off, or use a dechlorination puck. Test until chlorine is near zero (0.5 to 1 ppm or less). Drain slowly in small batches onto lawn or garden where it soaks in, away from slopes and water, and not on a rainy day. Storm drains lead straight to the lake | [Richmond Hill](https://richmondhill.ca/en/our-services/how-to-drain-a-pool-or-hot-tub.aspx), strong, municipality. Thresholds from US municipalities ([Bartlesville](https://www.cityofbartlesville.org/properly-drain-pool-hot-tub-water/), [Marion County](https://marionhealth.org/wp-content/uploads/2025/03/Residential-Swimming-Pool-Drainage-Fact-Sheet.pdf)) |

## Winter

Lake fills are realistically a spring to fall feature. In winter the lake is iced over, and the intake hose and pump will freeze unless they drain themselves after every fill. Not researched further.

## What the automated unit would have to do

These follow from the sources above. They are a starting list, not tested requirements.

1. **Fill:** run the pump until a level sensor says full. Stop if the intake runs dry. Filter sediment on the way in.
2. **Refuse to fill** during a known blue-green algae advisory.
3. **Sanitize:** dose chlorine or bromine to at least 3 ppm (chlorine) and keep pH at 7.0 to 7.8, and check it, since lake water uses chlorine faster.
4. **Heat** on propane for speed (see 07).
5. **Drain safely:** stop sanitizing or dechlorinate, confirm chlorine is near zero, then pump slowly onto land away from the shoreline. Never into the lake.
6. **Protect from freezing:** drain the intake hose and pump after each fill.

## Why it might matter for Airbnb hosts

Many cottages draw from a well or the lake, or have water trucked in, rather than having town water. A tub that fills itself from the lake would avoid draining a well or ordering a water delivery. That is a hypothesis to test in host interviews (see 05), not a finding.

## Gaps

- Lake water quality where we'd test (bacteria, iron, organic matter).
- Cost and reliability of sensors for chlorine, pH and cloudiness, and whether any cheap sensor can flag a bloom.
- 12 V pumps faster than 6 L/min.
- Whether public health treats a lake-filled rental hot tub differently.
