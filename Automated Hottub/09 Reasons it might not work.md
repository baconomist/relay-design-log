# Reasons it might not work

16 Oct 2026

The case against the automated hot tub, from the research in 01 to 08. Most serious first. Each one is something to answer, test or design around, not a reason to stop.

## 1. App-controlled inflatables already exist

Bestway sells SaluSpa "Smart" models where you set the temperature, run a power-saving timer, manage filtration and control the bubbles from a phone ([Amazon, SaluSpa Hawaii EnergySense Smart Luxe](https://www.amazon.com/clp/B0C79K184K), medium, retailer). Intex PureSpa works with the Intex Link app, and one listing says it can schedule heating ([Family Handyman](https://www.familyhandyman.com/article/intex-inflatable-hot-tub/), medium). Hard-shell tubs have had app control for years.

**So "a hot tub you control from your phone" is not new.** Whatever we build has to do something these don't. Candidates from our research:
- Propane plus electric heating that picks the cheaper or faster one (03, 07)
- Fills itself from a lake and drains safely (08)
- Checks and doses sanitizer by itself (08)
- Runs off-grid, powering itself from the propane (06)
- Lets a rental company look after many tubs at many properties (05)

## 2. "Automated" still needs someone to visit every week

- **Propane:** a tub in regular winter use needs about 100 kWh of heat a week (03). One 20 lb tank holds about that much, so **someone swaps a tank about once a week**. A 100 lb tank would last about 5 times longer.
- **Water:** the CDC says to replace all or part of the water weekly to monthly depending on use ([CDC](https://cdc.gov/healthy-swimming/toolkit/operating-public-pools-hot-tubs-and-splash-pads.html)). Rental guests may expect fresh water.
- **Chemicals and filters** run out, and filters clog.

Automation can cut the work, but someone still has to visit. For an Airbnb service, that labour and driving is probably the main cost.

## 3. Cheap inflatables aren't built for this

- **Winter:** Intex says not below 4°C. One Bestway manual says it can't reach 40°C below -5°C and shouldn't be run below -10°C (02, 07). Waterloo's January average is -6.3°C.
- **Hot water from the propane heater:** a 41,000 BTU heater returns water at about 60°C (07), but the tub is designed for 40°C at most. Water that hot hitting the vinyl directly could damage it (own reasoning, not tested). The return needs to mix into the tub first.
- **Lifespan:** inflatables usually last a few seasons, not decades (02). Rental guests will be rougher on them than owners.
- **Warranty:** adding our own heater, pump and controller to a SaluSpa will probably void its warranty (not checked).

## 4. Propane brings safety problems

- **Outdoors only.** Propane burners give off carbon monoxide and can't be used indoors or in enclosed spaces (06).
- **Scalding** from the 60°C return water (07).
- **Freezing** cracks the heater unless it drains itself or keeps circulating (07).
- **A 20 lb tank in the cold** can barely supply a 41,000 BTU heater around -10°C (07).
- **Certification and rules:** these heaters are sold for outdoor showers and camping. Whether using one to heat a hot tub is within its approved use, and what Ontario's fuel safety regulator (TSSA) requires, was not checked.

## 5. Nobody has asked customers yet

- No Airbnb host, tub owner or rental company has been interviewed. The evidence for the need so far is Lucas's own tub and AirDNA's correlation between hot tubs and higher winter revenue (05). That correlation doesn't show that hosts would rent a tub.
- Travellin' Tubs already delivers tubs in Ontario for C$500 a weekend or C$1,080 a month (05). A host can also buy an inflatable for about C$500 (02).
- At C$250 a night, the extra revenue from a hot tub is about the same as Travellin' Tubs' monthly fee (05), so there may be little left for a new service.
- This is the same trap the team pivoted away from on 15 Oct: making sure we solve a need people actually have, not one we've invented.

## 6. Propane costs more to run than electricity

At C$15 a tank, propane costs about 15¢ per kWh of heat, against 10.6¢ to 13.2¢ for electricity (03). Propane's advantage is speed and keeping up with the cover off (07), not cost. If hosts don't value fast heating, propane is the expensive option.

## 7. Liability and rules for rentals

- In Waterloo Region, a private-home hot tub offered to guests is exempt from public pool rules only if the right sign is posted. Public health can still inspect after a complaint (05).
- Not researched yet: insurance for a tub we own on someone else's property, Airbnb's own hot tub rules, and liability if a guest is hurt (scalding, drowning, illness).
- Lake water adds algae-bloom days when the tub can't be filled, and rules about draining away from the shore (08).

## 8. Capstone risks

- **The demo.** If the design symposium is indoors, a propane burner can't be run there. We would need an outdoor demo, a video, or an electric-only demo mode. The university may also need to approve propane and large amounts of water in a lab (not checked).
- **Where the engineering is.** The tub, heater and pump are off-the-shelf. The engineering work has to be in the control system, sensing, safety and integration, and needs to be clearly more than an app.
- **Budget** (C$750 to C$800) should cover a tub, heater, pump and electronics (about C$1,100 for Lucas's setup, which the team already has), but sensors for water chemistry were not priced.

## What would most reduce these risks

1. **Interview Airbnb hosts and Travellin' Tubs customers** before designing anything (risk 5).
2. **Pick one feature the smart inflatables don't have** and make it the core of the design (risk 1).
3. **Measure Lucas's tub through a cold week:** heat loss, propane use and how often it needs attention (risks 2, 3, 6).
4. **Check heater certification, TSSA rules and the symposium venue** early (risks 4, 8).
