# Frontend Mentor - Order Summary Component (The Mobile First)

**Table of Contents**

- [Frontend Mentor - Order Summary Component (The Mobile First)](#frontend-mentor---order-summary-component-the-mobile-first)
  - [Welcome! 👋](#welcome-)
  - [Links](#links)
  - [Overview](#overview)
  - [My Questions](#my-questions)
  - [Feedbacks](#feedbacks)
  - [Acknowledgments](#acknowledgments)
  - [Author](#author)

## Welcome! 👋

Welcome to my solution page. I hope you'll find some good implemantions for this project here.

![Order Summary Component](./design/desktop-preview.jpg)

## Links

- [My Live Site](https://adonmez04.github.io/Order-summary-component-v2.0/)

- [My Solution Page](https://www.frontendmentor.io/solutions/fem2ordersummarycomponentmobilefirst-yN7sJVBxnz)

- [The Challenge Page](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

## Overview

I completed this project twice. This time, I started the project with the mobile first perspective. Everything was easy for the mobile first but I felt an amatour, idk know. I would prefer the destop first solution but I have big issues with responsive design. :(

## My Questions

> Hi, everyone.
>
> I tried the mobile-first design for this solution. And I spent lots of time on it. I had some trouble BEM and I gave up. I'm not ready for BEM:) I focus on a simple solution. It should be basic and clean.
>
> Anyway, I can't align the background image for the mobile version. How can I do that?
>
> Thanks.
>
> Any feedback/thoughts are greatly appreciated!

## Feedbacks

**1. From Rostyslav Nazarenko:**

I struggled with aligning the background image. I started looking at how background works and continued from there. Played with it a bit and something worked

`background: var(--color-pale-blue) url("../images/pattern-background-mobile.svg") no-repeat top/contain;`

That is what I used but I looked at other solutions they add for desktop view later `repeat-x`
I would change the breakpoint for the desktop so it would trigger later. `480px`? probably more or less
image.png

On `:hover` change link should not be underlined.

There is an issue with using a instead of button but I myself am not sure which to use where. a when you direct a user to another page and button for any other interactions (actions).

That is probably all.

One thing only. As I understand it is not recommended to provide separate style sheets. For each one browser will send requests to the server and then fetch them back, which increases the load speed of the page

I wrote a lot, I hope it was helpful.

## Acknowledgments

- Thanks Rostyslav Nazarenko for your helpful comment. [@rostyslav-nazarenko](https://www.frontendmentor.io/profile/rostyslav-nazarenko)

## Author

- My Frontend Mentor Profile Page - [@adonmez04](https://www.frontendmentor.io/profile/adonmez04)
- For those of you reading this, have a nice day!
