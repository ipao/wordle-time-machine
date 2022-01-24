# wordle-time-machine
 Time traveler of Wordle on selected day.

## Features

Wordle allows us to enjoy once a day,
but this script can unlock you to enjoy more times a day.

The Time Machine provides you two options:
1. Move to random date
2. Move to specific date

## How to Use

1. Add new bookmark on your browser.
2. Edit your bookmark URL with the script below.
```
javascript:(function()%7Blet%20s%3Ddocument.createElement('script')%3Bs.setAttribute('src'%2C'https%3A%2F%2Fipao.github.io%2Fwordle-time-machine%2Fwordle.js')%3Bdocument.body.appendChild(s)%3B%7D)();
```
3. Open [Wordle](https://www.powerlanguage.co.uk/wordle/).
4. Click the bookmark added.
5. Leave it blank OR enter a date in `yyyy-mm-dd`.
6. Enjoy Wordle.

##Known Issue

- Current streak will be reset after click the bookmark.
- The word number in shared message will not be changed from today number.
