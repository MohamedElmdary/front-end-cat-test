# Front End Circle Test

<!--
> Main Layout

-   Question
-   Instructions?
-   Test Cases
-   Notes?

---- -->

## Questions

-   [Visa](#visa)
-   [Cards Animation](#cards-animation)
-   [Reactive System](#reactive-system)

### Visa

Question:  
Write an algorithm to verify the whether the card number is **valid** or **Invalid** (we assume main function called **verifyCardNumber**).

```js
function verifyCardNumber(cardNumber) {
    // your solution
}
```

Instructions:

1. Double every second digit from right to left. If doubling of a digit result in a two-digit number, add up the two digits to get a single-digit number.

```
4 3 8 8 5 7 6 0 1 8 4 0 2 6 2 6
|   |   |   |   |   |   |   |__ 2 * 2 = 4
|   |   |   |   |   |   |
|   |   |   |   |   |   |__ 2 * 2 = 4
|   |   |   |   |   |
|   |   |   |   |   |__ 4 * 2 = 8
|   |   |   |   |
|   |   |   |   |__ 1 * 2 = 2
|   |   |   |
|   |   |   |__ 6 * 2 = 12 (1 + 2 = 3)
|   |   |
|   |   |__ 5 * 2 = 10 (1 + 0 = 1)
|   |
|   |__ 8 * 2 = 16 (1 + 6 = 7)
|
|__ 4 * 2 = 8
```

2. Now add all single-digit numbers from **step 1**.
3. Add all digits in the odd places from right to left in the card number.
4. Sum the results from **step 2** and **step 3**.
5. If the result from **step 4** is divisible by 10, the card number is valid; otherwise, it's invalid.

Test Cases:

```
Input:
4388576018410707

Output:
Valid
```

```
Input:
4388576018402626

Output:
Invalid
```

### Card Animation

### Reactive System

---

<br />
<p align="center">@Cat Reloaded - Front End Circle Leader</p>
