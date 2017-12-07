# Currency input

Help users enter an amount of money in a specified currency.

## When to use this component

Use the Currency input component whenever you need users to tell you an amount of money in a particular currency, for example pounds sterling or euros.

## How it works

The Currency input component shows users which unit of currency they need to enter their amount in.

There are two ways to implement the Currency input component. You can use HTML or, if you are using [Nunjucks](https://mozilla.github.io/nunjucks/) or the [GOV.UK Prototype Kit](Insert prototype kit URL), you can use the Currency input macro.

[Example & codeblock for Currency input component]

### Preventing non-numeric characters
The component uses ```input type=”text”``` rather than ```type=number``` to ensure that all users can enter the decimal symbol.

A progressive enhancement has been applied to prevent non-numeric input. To use this enhancement, install the numeric input component or include ```numeric-input.js``` on the page and include the attribute ```data-non-numeric``` on the input.

## Research on this component
This component has been tested in a prototype of the apply for a temporary event notice service.
Read more about the [how the Currency input component has been tested and iterated](https://github.com/alphagov/govuk-design-system/wiki/Currency-input-testing-and-research).
