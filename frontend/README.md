# Frontend Challenge

This is the frontend technical challenge for candidates applying for an engineering role at Assetz Capital.

Please also read the [guidance](../README.md#guidance) and instructions for [submitting your task](../README.md#submitting-your-task).


## Task

Write an application in TypeScript using your frontend framework of choice that:
1. Fetches and displays [investor holdings](https://raw.githubusercontent.com/AssetzSMECapital/technical-challenge/master/data/holdings.json)
2. Add a responsive functionality for the layout, which will display one column on mobile
  devices, two columns on tablet devices, and three columns on desktops.
3. Add a modal that also displays the investor name, and account rate for the holding
4. Allow for the user to search by `investorName` and/or filter by `investmentAccount`
5. Add a button so that the data can be sorted by balance ascending, or descending
   1. we expect filters from point 4 to continue to work with the sorting functionality.
6. Add a button so that any sorting applied can be removed.
7. Add a button to display the total balance of the current investors displayed.

Don't worry about making a dazzling interface, basic aesthetics are welcome, but we're not assessing your design skills.


### API Information

The investor holdings can be retrieved at:

https://raw.githubusercontent.com/AssetzSMECapital/technical-challenge/master/data/holdings.json

And have the format:
```
{
    "investorId": number,
    "investmentAccount": string,
    "balance": string
}
```

The investors can be retrieved at:

https://raw.githubusercontent.com/AssetzSMECapital/technical-challenge/master/data/investors.json

And have the format:
```
{
    "investorId": number,
    "investorName": string
}
```

The investment account rates can be retrieved at:

https://raw.githubusercontent.com/AssetzSMECapital/technical-challenge/master/data/rates.json

And have the format:
```
{
    "investmentAccount": string, 
    "annualRate": number
}
```
