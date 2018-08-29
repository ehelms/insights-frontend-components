
# Donut Chart

This component is usefull to display x number of values to compare them to an overall value

```jsx
import React from 'react'
import { Donut } from '@red-hat-isnights/insights-frontend-components';

let DonutTotal = 75;

let DonutValues = [
    ['value1', 5],
    ['value2', 10],
    ['value3', 20],
    ['value4', 40]
];

<Donut values={DonutValues} total={DonutTotal} totalLabel='label for donut-hole' id='donut-identifier'/>;

```

## Donut with Legend

```jsx

<Donut values={DonutValues} total={DonutTotal} totalLabel='label for donut-hole' id='donut-identifier' withLegend/>;

```

## Props

```JS
{
    className: propTypes.string,
    height: propTypes.number,
    identifier: propTypes.string,
    values: propTypes.array,
    width: propTypes.number,
    total: propTypes.number,
    totalLabel: propTypes.string,
    withLabel: propTypes.bool,
}
```