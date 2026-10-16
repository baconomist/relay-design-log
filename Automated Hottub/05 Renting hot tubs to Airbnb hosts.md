# Renting hot tubs to Airbnb hosts

16 Oct 2026

The idea: automate a cheap tub to the point where it is easy to rent out to Airbnb hosts, so they can charge more for their stays.

**Hosts have a real reason to want one.** AirDNA's 2024 data says homes with a hot tub earn noticeably more in winter. **But mobile hot tub rental already exists in Ontario.** Travellin' Tubs delivers a 4 to 6 person tub in Toronto, London and Muskoka for C$500 a weekend or C$1,080 a month. It does not market to Airbnb hosts, and its tub takes about 24 hours to heat. In Waterloo Region, a hot tub at a private home made available to guests is exempt from Ontario's public pool rules, as long as the right sign is posted. Nobody has asked a host yet whether they would rent one.

## Demand: what a hot tub does for a listing

| Finding | Source | Strength |
| --- | --- | --- |
| In winter, homes with a hot tub get **9% higher occupancy**, **32% higher nightly rates** and **52% more revenue per available night**. Sample: three-bedroom entire homes with at least 90 days of availability in 2024 | [AirDNA blog](https://www.airdna.co/blog/how-to-get-more-bookings-on-airbnb) | Medium. AirDNA is the standard source, but the page blocked us, so this is from its search snippet. 9% and 32% compound to about 44%, not 52%, and the post doesn't explain the gap |
| The same post says a hot tub home earns **22% more per night in winter** and **15% more in summer** | Same post | Medium. Doesn't match the 32% above |
| Airbnb has dedicated hot tub search pages for Canada, Muskoka and Ottawa | [Canada](https://www.airbnb.ca/canada/stays/hot-tub), [Muskoka](https://www.airbnb.com/muskoka-district-municipality-canada/stays/hot-tub), [Ottawa](https://www.airbnb.ca/ottawa-canada/stays/hot-tub) | Strong that the pages exist |

These are correlations across listings, not proof that adding a tub causes the lift. Homes with hot tubs may also be bigger or nicer in other ways.

**Rough host maths (own calc, assumed numbers).** On a cottage earning C$250 a night, a 22% lift is about C$55 a night. Booked 20 nights in a winter month, that is about C$1,100 more revenue, close to Travellin' Tubs' C$1,080 monthly rental before electricity. So renting a tub only clearly pays for a host at higher nightly rates, higher occupancy, or a cheaper rental than today's.

## Who already does this

| Company | What they offer | Price | Strength |
| --- | --- | --- | --- |
| [Travellin' Tubs](https://www.travellintubs.com/), Toronto, London, Muskoka, Vancouver, plus franchisees | Delivered 250-gallon RotoSpa for 4 to 6 adults, 120 V 15 A plug, locking cover. They deliver, fill and prime it. About **24 hours to reach 100°F**, longer in cold weather. Someone must be there at drop-off. No mention of Airbnb hosts | **C$500 weekend, C$650 week, C$800 two weeks, C$1,080 month**, plus HST. Holiday weeks C$700. Muskoka and Whistler cost more | Strong, company site |
| [PNW Mobile Spa](https://pnwmobilespa.com/), Seattle area | On-demand delivery of hot tubs, saunas and cold plunges | Not checked | Medium |
| South Whidbey, Washington operator | Mobile hot tub, needs a 110 V outlet, hose bib and flat ground reachable by truck and trailer | US$450 for 4 days, US$550 a week | Medium, [local news](https://www.southwhidbeyrecord.com/?p=92721) |
| [Swimply](https://en.wikipedia.org/wiki/Swimply) | Marketplace that rents out private pools and now hot tubs by the hour, in the US, Canada and Australia | Set by owners | Medium. A possible sales channel, not just a competitor |
| UK hot tub hire | Mature market. Typical pattern: deliver Wednesday so the tub is hot by Friday, collect Monday | [Add to Event guide](https://addtoevent.co.uk/blog/hot-tub-hire-prices) | Medium |

## Rules in Ontario

| Rule | Source | Strength |
| --- | --- | --- |
| Since 28 Oct 2022, a spa used only by the occupants of a single dwelling unit or hotel suite is exempt from Ontario's Public Pools regulation (Reg. 565). It must post a notice that it is not covered by the regulation and is used at your own risk. Public health can still inspect it after a complaint | [Simcoe Muskoka public health Q&A](https://www.simcoemuskokahealth.org/docs/default-source/topic-safewater/questions-and-answers-certain-public-spas-exemption.pdf?sfvrsn=2), [Toronto guidance](https://www.toronto.ca/wp-content/uploads/2023/01/9434-Guidance-for-Exempt-Public-SpasEN.pdf) | Strong |
| Region of Waterloo: private residential pools and spas made available to the public, with or without a fee, are exempt from Reg. 565, but owners must post specific signage. Points to the Ministry of Health's guidance on short-term residential pool rentals | [Region of Waterloo Public Health](https://www.regionofwaterloo.ca/programs-and-services/public-health/health-standards-for-businesses/recreational-safe-water/) | Strong |
| Many cities require hosts to hold a short-term rental licence, separate from anything about the tub | [Lodgify](https://www.lodgify.com/blog/start-an-airbnb-business-in-canada/) | Medium |

Not researched yet: insurance and liability for a tub owned by us on someone else's property, Airbnb's own rules on hot tubs, and propane rules for rental properties.

## What automation would have to do for this to work

None of this is evidence. It is what the research above implies an Airbnb rental tub would need, as a starting list for objectives.

- **Be hot when guests arrive.** Travellin' Tubs needs about 24 hours to heat. A tub that heats on a schedule tied to the booking calendar, or heats faster, removes a host chore and a guest complaint.
- **Keep the water safe between guests without the host.** Monitor sanitizer and pH, and flag a water change.
- **Not freeze.** Alert or self-protect before it gets cold enough to damage the tub, since cheap inflatables aren't rated below about 4°C (see 02).
- **Report remotely.** Temperature, faults, propane level if propane, and usage, to us and the host.
- **Heat at the cheapest time.** Off-peak heating cuts electricity costs about 20% (see 03).
- **Be safe unsupervised.** Locking cover, temperature cap, and the posted notice.

## Open questions for interviews

- Would hosts rent a tub, or would they rather buy one? The cheapest hard-shell found is about US$2,499 (see 02).
- What would they pay per month, and would the price have to beat Travellin' Tubs' C$1,080?
- What stops hosts adding a hot tub today: cost, maintenance, cleaning between guests, liability, or space?
- Would hosts let an outside company service a tub on their property between guests?
