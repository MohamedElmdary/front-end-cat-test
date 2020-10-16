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

Question:  
Design a cards layout with the animation shown in the blow video. The card itself also required to be degined but just a single card design should be enough (Don't change data for every card).

Instructions:

1. Design the card layout using HTML/CSS
2. Make sure the card layout is horizontal scroll (y-axis).
3. Make sure card are correctly on top of each other.
4. Make sure first/last card doesn't go beyond the screen or the container.
5. Add the animation to cards.

Animation:  
Whenever the mouse hover over any card .. this card should go a little to top (x-axis) and all the cards on it's right side should be pushed away to give the user the ability to see the full card layout.

Video:  
[Cards Animation Video](https://drive.google.com/file/d/1jwfbXdyrwUZ45pZl2Vky01oJ8EU3RE-1/view?usp=sharing)

Notes:

1. You can design the same card as video or a better one from your mind it's totally fine.
2. Same animation is required (don't edit the animation).
3. This question required html/css only but it's ok if someone wanna add js (but it's 100% not required).

### Reactive System

---

<br />
<p align="center">@Cat Reloaded - Front End Circle Leader</p>
