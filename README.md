# Exchange-Rate

- We're going to be building an exchange rate calculator
- to use the fetch API to make an each HTTP request to a third party API to get some exchange rates

## HTML explained

- In container, will have two currency divisions, each will have exchange rate code select box and amout inputs
- be default we will show USD to INR, and we have the swap button as well

## CSS explained

- style all elements and center to the view port
- for select dropdowns, we disable the default brower apperance and apply custom styles

## JS explained

- select the DOM elements we need, currency-one and two, amount-one and two, rate element & swap button
- call the Event Listeners for all required elements
- fetch the exchange rate api dynamically
- find the rate, by data.rates of currency element two and update the rate element info
- amount two value will calculate the amount one value multiples with rate
-

## Resources

- Currency codes list: https://gist.github.com/AmrMekkawy/a5425a4dd4e453a4eb4d
- SVG select dropdown icon: https://stackoverflow.com/questions/54207098/how-to-add-an-svg-icon-as-select-dropdown-arrow
- Background Position userful article: https://stackoverflow.com/questions/51731106/using-percentage-values-with-background-position-on-a-linear-gradient/51734530#51734530
- Exchange Rate API: https://api.exchangerate-api.com/v4/latest/INR
- find all the names(keys) of any object: Object.keys(ReqObjName)
- Background gradient by https://uigradients.com/#Ohhappiness

## Demo
