---
layout: inner
title: "Will the MTA's OMNY Rollout Leave Reduced Fare Riders Behind?"
permalink: /mta-omny-analysis
---
# Will the MTA's OMNY Rollout Leave Reduced Fare Riders Behind?

In 2017, the Metropolitan Transit Authority (MTA) announced plans to phase out physical MetroCards and replace them with a contactless fare payment system. The new system, eventually dubbed OMNY, would allow subway and bus riders to pay fares using digital wallets, contactless credit or debit cards, and, eventually, physical OMNY cards capable of tap-to-pay. The MetroCard phase-out was planned to be completed in 2023, but delays have pushed the expected completion date back indefinitely.

While OMNY might promise a bit of much-needed modernization to New York City’s transit system, the rollout has also raised concerns that some classes of reduced-fare riders will be left behind. The MTA currently offers two reduced-fare options:

1. Seniors & Disability, for riders who are 65 and older or have a qualifying disability; and
2. Fair Fares, for low-income riders.

Until OMNY, reduced-fare riders paid with a special MetroCard. But with the OMNY rollout’s emphasis on contactless payment methods, which require a smartphone or contactless credit or debit card to use, will these riders still be able to access their benefits? Among adults with household incomes below $30,000 per year, smartphone ownership [is only 76%](https://www.pewresearch.org/short-reads/2021/06/22/digital-divide-persists-even-as-americans-with-lower-incomes-make-gains-in-tech-adoption/). Among seniors, [it’s only 61%](https://www.pewresearch.org/short-reads/2022/01/13/share-of-those-65-and-older-who-are-tech-users-has-grown-in-the-past-decade/).

Furthermore, reduced-fare riders are busy people. They might not have the time or resources to [go through the effort](https://new.mta.info/fares/reduced-fare/omny#:~:text=Visit%20the%20OMNY,switch%20to%20OMNY.) of linking their benefits to a contactless payment method, or to seek out one of the [87 subway stations](https://www.amny.com/news/mta-omny-vending-machines-nyc-train-stations/#:~:text=NYC%20commuters%20can%20purchase%20OMNY,every%20borough%20except%20Staten%20Island.) that sells physical OMNY cards. ([A year ago](https://www.amny.com/transit/omny-machines-activated-nyc-subway-stations/), only six stations sold OMNY cards. And before that, the cards were only sold at select retailers like CVS and Walgreens.)

Considering the inconvenience that OMNY has so far presented to reduced-fare riders, have these customers been slower to adopt OMNY than those paying full fare? Has the phased OMNY rollout prepared riders for the eventual discontinuation of MetroCards?

Using the MTA’s [Subway Hourly Ridership dataset](https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-Beginning-July-2020/wujg-7c2s/about_data), which tallies ridership by station and fare type since February 2022, we can answer these questions. Also, by comparing ridership to [demographic data from the American Community Survey](https://data.census.gov/table/ACSDP1Y2022.DP05?t=Older%20Population) (ACS), we can estimate the share of eligible riders who use reduced-fare programs, for both MetroCard and OMNY, to determine if utilization differs between the groups.

Understanding how effectively (or ineffectively) the OMNY rollout has reached reduced-fare riders is critical for making sure seniors, low-income riders, and riders with disabilities aren’t left behind.

## Has OMNY Adoption Been Slower Among Reduced-Fare Riders?

Since OMNY readers were first installed in subway stations in 2019, it has become the preferred payment method of New York City subway riders. Meanwhile, traditional MetroCard swipes have been on the decline. In early 2024, OMNY ridership finally surpassed MetroCard:

<img src="/img/posts/MTA-OMNY/ridership.png" style="width:100%; height:auto;" />

(Note: All data discussed in this analysis runs through September 2024.)

This is a good sign for the future of OMNY. If OMNY ridership continues its current trajectory, it will eventually dwarf MetroCard, setting the MTA and its riders up for success when the MetroCard is someday discontinued.

What’s driving the decline in MetroCard usage? It’s almost entirely a decline in full-fare ridership:

<img src="/img/posts/MTA-OMNY/metrocard_fare_classes.png" style="width:100%; height:auto;" />

Full-fare MetroCard ridership has been cut nearly in half since 2022. Rides using an Unlimited 30-day or 7-day pass have also become slightly less common, likely because OMNY’s weekly [fare-capping](https://new.mta.info/fares/omny/fare-capping) feature serves a similar purpose. But ridership among Fair Fare and Seniors & Disability riders using MetroCards has hardly changed.

What’s driving the increase in OMNY usage? If you’d guessed that full-fare rides are the main source of OMNY ridership, you’d be correct. But you might be surprised by how much full-fare ridership defines OMNY rides:

<img src="/img/posts/MTA-OMNY/omny_fare_classes.png" style="width:100%; height:auto;" />

The other fare types are barely even visible! In September 2024, less than 1% of OMNY rides used the Fare Fair or Seniors & Disability benefit, compared to 18% of MetroCard rides. Part of the reason for that is that the Fair Fare low-income discount didn’t have an OMNY option until July of 2024. But the Seniors & Disability fare type, which has been compatible with OMNY for a while now, still only has about 380,000 monthly rides:

<img src="/img/posts/MTA-OMNY/omny_seniors.png" style="width:100%; height:auto;" />

What explains these trends? The MTA ridership data doesn’t differentiate between OMNY payments made by tapping a smartphone, contactless debit or credit cards, or physical OMNY cards, so we can’t know for certain. However, these patterns seem consistent with the story I alluded to above: Using Apple Pay, Google Pay, or a tap-to-pay credit card is a far more convenient way to pay than a MetroCard or physical OMNY card. For the majority of subway riders with a smartphone, this makes using OMNY preferable, especially considering its fare-capping and pay-as-you-go benefits.

For reduced-fare riders, the ability to keep accessing benefits was not instantaneous. Fare Fair riders didn’t get an OMNY option until this year. An OMNY option for Seniors & Disability became available [in June 2022](https://en.wikipedia.org/wiki/OMNY#:~:text=Reduced%2Dfare%20customers%20were%20allowed%20to%20use%20OMNY%20starting%20in%20June%202022%20using%20their%20own%20debit%20or%20credit%20cards%20which%20must%20be%20registered%20with%20OMNY.), but the process to link one’s benefits to a payment method still required extra effort. With MetroCards still accepted at all subway stations, Seniors & Disability riders have continued using their discounted MetroCards – and avoided transferring their benefits to OMNY – simply because it’s the path of least resistance.
