# Homework. Module 1. Variables, Data Types & Functions Basics

## Overview

Complete each task in its corresponding JavaScript file:

- `task-1.js`
- `task-2.js`
- `task-3.js`

After implementing each solution, paste the provided test code below your function and leave it unchanged so your mentor can verify the results.

---

# Task 1. Droid Order

Complete this task in **`task-1.js`**.

A repair droid sales station is ready to launch, but the sales department still needs software to process customer orders.

## Requirements

Declare a function named `makeTransaction` that accepts two parameters:

- `quantity` — the number of droids ordered.
- `pricePerDroid` — the price of a single droid.

Complete the function so that it returns the following string:

```text
You ordered <quantity> droids worth <totalPrice> credits!
```

Where:

- `<quantity>` is the number of ordered droids.
- `<totalPrice>` is the total cost of the order.

### Test your solution

Copy the following code below your function:

```javascript
console.log(makeTransaction(5, 3000));
// "You ordered 5 droids worth 15000 credits!"

console.log(makeTransaction(3, 1000));
// "You ordered 3 droids worth 3000 credits!"

console.log(makeTransaction(10, 500));
// "You ordered 10 droids worth 5000 credits!"
```

> **Do not remove these test cases.** Leave them in your solution for your mentor to review.

## Review Checklist

- [x] - The `makeTransaction(quantity, pricePerDroid)` function is declared.
- [x] - `makeTransaction(5, 3000)` returns `"You ordered 5 droids worth 15000 credits!"`.
- [x] - `makeTransaction(3, 1000)` returns `"You ordered 3 droids worth 3000 credits!"`.
- [x] - `makeTransaction(10, 500)` returns `"You ordered 10 droids worth 5000 credits!"`.
- [x] - All test results are printed to the console.
- [x] - The function returns the correct value for any valid arguments.

---

# Task 2. Product Shipping

Complete this task in **`task-2.js`**.

## Requirements

Declare a function named `getShippingMessage` that accepts three parameters:

- `country` — the destination country.
- `price` — the total cost of the purchased items.
- `deliveryFee` — the shipping cost.

Complete the function so that it returns the following string:

```text
Shipping to <country> will cost <totalPrice> credits
```

Where:

- `<country>` is the destination country.
- `<totalPrice>` is the total order cost, including shipping.

### Test your solution

Copy the following code below your function:

```javascript
console.log(getShippingMessage("Australia", 120, 50));
// "Shipping to Australia will cost 170 credits"

console.log(getShippingMessage("Germany", 80, 20));
// "Shipping to Germany will cost 100 credits"

console.log(getShippingMessage("Sweden", 100, 20));
// "Shipping to Sweden will cost 120 credits"
```

> **Do not remove these test cases.** Leave them in your solution for your mentor to review.

## Review Checklist

- [x] - The `getShippingMessage(country, price, deliveryFee)` function is declared.
- [x] - `getShippingMessage("Australia", 120, 50)` returns `"Shipping to Australia will cost 170 credits"`.
- [x] - `getShippingMessage("Germany", 80, 20)` returns `"Shipping to Germany will cost 100 credits"`.
- [x] - `getShippingMessage("Sweden", 100, 20)` returns `"Shipping to Sweden will cost 120 credits"`.
- [x] - The function returns the correct value for any valid arguments.

---

# Task 3. Element Width

Complete this task in **`task-3.js`**.

## Requirements

Declare a function named `getElementWidth` that accepts three parameters:

- `content` — the content width.
- `padding` — the horizontal padding value for each side.
- `border` — the border width for each side.

All parameters are strings in the format:

```text
Npx
```

where `N` can be an integer or a decimal number.

Complete the function so that it returns a **number** representing the total width of the element.

Assume the element uses:

```css
box-sizing: border-box;
```

### Test your solution

Copy the following code below your function:

```javascript
console.log(getElementWidth("50px", "8px", "4px"));
// 74

console.log(getElementWidth("60px", "12px", "8.5px"));
// 101

console.log(getElementWidth("200px", "0px", "0px"));
// 200
```

> **Do not remove these test cases.** Leave them in your solution for your mentor to review.

## Review Checklist

- [x] - The `getElementWidth(content, padding, border)` function is declared.
- [x] - `getElementWidth("50px", "8px", "4px")` returns `74`.
- [x] - `getElementWidth("60px", "12px", "8.5px")` returns `101`.
- [x] - `getElementWidth("200px", "0px", "0px")` returns `200`.
- [x] - The function returns the correct value for any valid arguments.
