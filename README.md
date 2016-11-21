# nhs-5in1-immunisation
Number, and percent, of children who have completed their primary immunisation course of the DTP/Pol/Hib vaccine by 24 months of age: [Publication](http://isdscotland.org/Health-Topics/Child-Health/Publications).

The DTP/Pol/Hib (or 5-in-1) vaccine protects against 5 diseases: Diphtheria, Tetanus, Pertussis, Polio and Haemophilus influenzae type b.

It should also be noted that children with a missing or invalid postcode have been excluded. As a result uptake rates may not exactly match those already published on the ISD Child Health Immunisations page.

Source: Scottish Immunisation and Recall System (SIRS), ISD Scotland.
                                                                     
Statistics provided by NHS Information Services Division:  http://statistics.gov.scot/data/dtp-pol-hib-uptake-by-24-months

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-5in1-immunisation.git
```

Install npm dependencies

```
cd nhs-5in1-immunisation
npm install
```

Run the API (from the nhs-5in1-immunisation directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
