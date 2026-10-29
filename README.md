# CSS Flexbox Position Practice

## Project Overview

This project demonstrates how CSS Flexbox positions six colored boxes inside a full-screen container. The boxes move repeatedly through nine positions using CSS animations without JavaScript.

## Technologies Used

- HTML5 for the page structure.
- CSS3 for styling, Flexbox layout, and animation.

## How the Code Works

### 1. Flex Container

The `.flex-container` uses `display: flex` to arrange the boxes along the main axis. Its `height: 100vh` and `width: 100%` make it fill the viewport.

### 2. Flexbox Properties

- `justify-content`: positions the boxes horizontally.
- `align-items`: positions the boxes vertically.
- `gap`: adds spacing between boxes.
- `flex-shrink: 0`: prevents the boxes from shrinking below their specified size.

### 3. CSS Animation

The `@keyframes moveBoxes` rule changes `justify-content` and `align-items` at different percentages. The animation repeats indefinitely using `infinite`.

### 4. The Nine Positions

| Position | justify-content | align-items |
|---|---|---|
| Top Left | `flex-start` | `flex-start` |
| Top Center | `center` | `flex-start` |
| Top Right | `flex-end` | `flex-start` |
| Middle Left | `flex-start` | `center` |
| Center | `center` | `center` |
| Middle Right | `flex-end` | `center` |
| Bottom Left | `flex-start` | `flex-end` |
| Bottom Center | `center` | `flex-end` |
| Bottom Right | `flex-end` | `flex-end` |

## Screenshots

Add screenshots of the running animation here. Capture different positions to demonstrate the nine-position layout.

## Video Demonstration

Video link: TO BE ADDED

## GitHub Repository

Repository link: TO BE ADDED

## What I Learned

I learned how Flexbox uses `justify-content` and `align-items` to position elements horizontally and vertically. I also practiced CSS keyframes and infinite animations to move elements through different layouts without JavaScript.