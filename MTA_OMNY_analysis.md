---
layout: inner
title: "Will the MTA's OMNY Rollout Leave Reduced-Fare Riders Behind?"
permalink: /mta-omny-analysis
---

# Will the MTA's OMNY Rollout Leave Reduced-Fare Riders Behind?

<img src="img/posts/MTA-OMNY/mta github thumbnail.jpg" style="width:auto; height:50%;" />

In 2017, the Metropolitan Transit Authority (MTA) announced plans to phase out physical MetroCards and replace them with a contactless fare payment system. The new system, eventually dubbed OMNY, would allow subway and bus riders to pay fares using digital wallets, contactless credit or debit cards, and, eventually, physical OMNY cards capable of tap-to-pay. The MetroCard phase-out was planned to be completed in 2023, but delays have pushed the expected completion date back indefinitely.

<br>

While OMNY might promise a bit of much-needed modernization to New York City’s transit system, the rollout has also raised concerns that some classes of reduced-fare riders will be left behind. The MTA currently offers two reduced-fare options: Seniors & Disability, for riders who are 65 and older or have a qualifying disability; and Fair Fares, for low-income riders.

<br>

Until OMNY, reduced-fare riders paid with a special MetroCard. But with the OMNY rollout’s emphasis on contactless payment methods, which require a smartphone or contactless credit or debit card to use, will these riders still be able to access their benefits? Among adults with household incomes below $30,000 per year, smartphone ownership [is only 76%](https://www.pewresearch.org/short-reads/2021/06/22/digital-divide-persists-even-as-americans-with-lower-incomes-make-gains-in-tech-adoption/). Among seniors, [it’s only 61%](https://www.pewresearch.org/short-reads/2022/01/13/share-of-those-65-and-older-who-are-tech-users-has-grown-in-the-past-decade/).

<br>

Furthermore, reduced-fare riders are busy people. They might not have the time or resources to [go through the effort](https://new.mta.info/fares/reduced-fare/omny#:~:text=Visit%20the%20OMNY,switch%20to%20OMNY.) of linking their benefits to a contactless payment method, or to seek out one of the [87 subway stations](https://www.amny.com/news/mta-omny-vending-machines-nyc-train-stations/#:~:text=NYC%20commuters%20can%20purchase%20OMNY,every%20borough%20except%20Staten%20Island.) that sells physical OMNY cards. ([A year ago](https://www.amny.com/transit/omny-machines-activated-nyc-subway-stations/), only six stations sold OMNY cards. And before that, the cards were only sold at select retailers like CVS and Walgreens.)

<br>

Considering the inconvenience that OMNY has so far presented to reduced-fare riders, have these customers been slower to adopt OMNY than those paying full fare? Has the phased OMNY rollout prepared riders for the eventual discontinuation of MetroCards?

<br>

Using the MTA’s [Subway Hourly Ridership dataset](https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-Beginning-July-2020/wujg-7c2s/about_data), which tallies ridership by station and fare type since February 2022, we can answer these questions. Also, by comparing ridership to [demographic data from the American Community Survey](https://data.census.gov/table/ACSDP1Y2022.DP05?t=Older%20Population) (ACS), we can estimate the share of eligible riders who use reduced-fare programs, for both MetroCard and OMNY, to determine if utilization differs between the groups.

<br>

Understanding how effectively (or ineffectively) the OMNY rollout has reached reduced-fare riders is critical for making sure seniors, low-income riders, and riders with disabilities aren’t left behind.

<br>

## Has OMNY Adoption Been Slower Among Reduced-Fare Riders?

Since OMNY readers were first installed in subway stations in 2019, it has become the preferred payment method of New York City subway riders. Meanwhile, traditional MetroCard swipes have been on the decline. In early 2024, OMNY ridership finally surpassed MetroCard:

<br>

<img src="/img/posts/MTA-OMNY/ridership.png" style="width:100%; height:auto;" />

<br>

(Note: All data discussed in this analysis runs through September 2024.)

<br>

This is a good sign for the future of OMNY. If OMNY ridership continues its current trajectory, it will eventually dwarf MetroCard, setting the MTA and its riders up for success when the MetroCard is someday discontinued.

<br>

What’s driving the decline in MetroCard usage? It’s almost entirely a decline in full-fare ridership:


<br>

<img src="/img/posts/MTA-OMNY/metrocard_fare_classes.png" style="width:100%; height:auto;" />

<br>

Full-fare MetroCard ridership has been cut nearly in half since 2022. Rides using an Unlimited 30-day or 7-day pass have also become slightly less common, likely because OMNY’s weekly [fare-capping](https://new.mta.info/fares/omny/fare-capping) feature serves a similar purpose. But ridership among Fair Fare and Seniors & Disability riders using MetroCards has hardly changed.

<br>

What’s driving the increase in OMNY usage? If you’d guessed that full-fare rides are the main source of OMNY ridership, you’d be correct. But you might be surprised by how much full-fare ridership defines OMNY rides:

<br>

<img src="/img/posts/MTA-OMNY/omny_fare_classes.png" style="width:100%; height:auto;" />

<br>

The other fare types are barely even visible! In September 2024, less than 1% of OMNY rides used the Fare Fair or Seniors & Disability benefit, compared to 18% of MetroCard rides. Part of the reason for that is that the Fair Fare low-income discount didn’t have an OMNY option until July of 2024. But the Seniors & Disability fare type, which has been compatible with OMNY for a while now, still only has about 380,000 monthly rides:

<br>

<img src="/img/posts/MTA-OMNY/omny_seniors.png" style="width:100%; height:auto;" />

<br>

What explains these trends? The MTA ridership data doesn’t differentiate between OMNY payments made by tapping a smartphone, contactless debit or credit cards, or physical OMNY cards, so we can’t know for certain. However, these patterns seem consistent with the story I alluded to above: Using Apple Pay, Google Pay, or a tap-to-pay credit card is a far more convenient way to pay than a MetroCard or physical OMNY card. For the majority of subway riders with a smartphone, this makes using OMNY preferable, especially considering its fare-capping and pay-as-you-go benefits.

<br>

For reduced-fare riders, the ability to keep accessing benefits was not instantaneous. Fare Fair riders didn’t get an OMNY option until this year. An OMNY option for Seniors & Disability became available [in June 2022](https://en.wikipedia.org/wiki/OMNY#:~:text=Reduced%2Dfare%20customers%20were%20allowed%20to%20use%20OMNY%20starting%20in%20June%202022%20using%20their%20own%20debit%20or%20credit%20cards%20which%20must%20be%20registered%20with%20OMNY.), but the process to link one’s benefits to a payment method still required extra effort. With MetroCards still accepted at all subway stations, Seniors & Disability riders have continued using their discounted MetroCards – and avoided transferring their benefits to OMNY – simply because it’s the path of least resistance.

<br>

## How Do Reduced-Fare Utilization Gaps Differ by Geography?

To get a sense of how the disparity in reduced-fare usage between MetroCard and OMNY riders relates to New York City’s geography, we can use the ACS Demographic and Housing Estimates dataset with a subset of the MTA ridership data. Using the share of an area that is 65 or older as a baseline, we can visualize how much of a gap there is between how many people are eligible for the Seniors & Disability fare, and how many actually use it. Note that this might actually underestimate the gap, since the ACS data does not include information on disabilities.

<br>

By determining where reduced-fare utilization is lower than expected among OMNY riders, we can assess where extra efforts should be made in the future to help reduced-fare riders transition their benefits to OMNY.

<br>

<div style="min-height:796px" id="datawrapper-vis-h7zwR"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/h7zwR/embed.js" charset="utf-8" data-target="#datawrapper-vis-h7zwR"></script><noscript><img src="https://datawrapper.dwcdn.net/h7zwR/full.png" alt="" /></noscript></div>

<br>

Under-utilization of the Seniors & Disability discount is fairly persistent throughout the city. In the worst cases, there is more than a 40% gap between the share of residents eligible for the benefit and the share of OMNY rides that used it. In particular, south Brooklyn and parts of Manhattan north of Grand Central are areas with high rates of under-utilization.

<br>

The map for MetroCard Seniors & Disability ridership is consistent with the story we’ve been telling:

<br>

<div style="min-height:823px" id="datawrapper-vis-vJoOw"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/vJoOw/embed.js" charset="utf-8" data-target="#datawrapper-vis-vJoOw"></script><noscript><img src="https://datawrapper.dwcdn.net/vJoOw/full.png" alt="" /></noscript></div>

<br>

Most stations have a much smaller under-utilization rate among MetroCard users. Large gaps persist in the same areas as for OMNY riders (i.e., in areas with lots of seniors), but there are far more stations where the utilization gap is closer to 10% than 20%.

<br>

## Conclusions

So far, the OMNY rollout has seen success among riders paying full fares. The tap-to-pay option is convenient and preferable to paying full-fare rates with a MetroCard. However, adoption of OMNY has been slower among reduced-fare riders. Part of the explanation is structural; the Fair Fares low-income discount was not compatible with OMNY for the first five years of the program’s existence.

<br>

Another part of the explanation is likely behavioral. Riders who have the choice between keeping their reduced-fare MetroCard and jumping through hoops to switch to OMNY, will continue using their MetroCard as long as it’s an option. This is suggested by the fact that the number of MetroCard rides using the Seniors & Disability benefit has not changed over the last two years, even as the number of full-fare MetroCard rides has plummeted.

<br>

Fortunately, the MTA recently announced [plans](https://new.mta.info/fares/reduced-fare/omny) to mail physical OMNY cards to all riders enrolled in reduced-fare programs. This will hopefully have a similar effect to making OMNY full-fare rides available instantaneously to anyone with a smartphone or contactless credit card. In fact, the MTA made OMNY student cards available to all NYC Public School students for the 2024-25 school year, partnering with schools for distribution. If this program is successful, it bodes well for the plan to mail OMNY cards to reduced-fare riders.

<br>

Beyond this important step, the MTA should continue to conduct outreach to transit riders who are eligible for reduced-fare programs, focusing especially on areas with large populations of seniors, low-income residents, and residents with disabilities. Taking these actions will help ensure that the OMNY rollout benefits all New Yorkers and that none are left behind.

<br>
