# TS-Nederdy-Challanges

## Steps

1. Fork this repo to your account
1. Before you start making changes create a new `develop` branch (`git checkout -b develop`)
1. Run `yarn install` in your terminar for install the dependencies

## Content Chanllange

You are given a list of temperatures that ocurred for major US cities over the past week. Temperature readings were taken ad inconsistent intervals. Process the temperature readings and create a function that will retun a summary of the temperature data for a given dat. The summary should include the following information:

1. Fisrt temperature reading for the day
1. Last temperature reading for the day
1. Highest temperature reading for the day
1. Lowest temperature reading for the day
1. Average of temperature readings that day

Description of the two function in the file `src/app.ts`

## Function Descriptions

The `processReadings` function will be called once with a list temperature readings and return nothing.

The `getTemperatureSummary` function will be called any number of items with a date and city, and returns the temperature summary for taht day in that city. If there is no temperature data for taht day and city, return null.

When you are finish the logic plear run the next command `yarn test` the test will return the correct answer if the functios are corrects

Recomendation: for a better performance and clean code please run the command `yarn format:write`

