# Mess Meal Manager

Track mess meals, bazar costs and deposits — and split the bill fairly at month end.

**Live Demo:** https://nafiz-xd.github.io/mess-meal-manager/

## About

Mess Meal Manager is a single-page web app for hostel and mess students in Bangladesh. In a shared mess, members eat a different number of meals, take turns doing the bazar (market shopping), and deposit money into a common fund — working out who owes whom at month end is normally a messy notebook calculation. This app does it automatically: enter each day's meals and every bazar expense, and it calculates the meal rate and everyone's balance.

## Features

- **Members** — add and remove the people sharing the mess
- **Daily meal entry** — pick any date and enter each member's meals (half meals like 2.5 supported); past dates can be edited or deleted
- **Bazar expenses** — record date, item, cost in ৳, who paid, and the type: *Meal bazar* (goes into the meal rate) or *Shared* (split equally between all members)
- **Deposits** — record money each member puts into the mess fund
- **Automatic month summary**
  - Meal rate = total meal bazar cost ÷ total meals
  - Each member's meal cost = their meals × meal rate
  - Shared costs split equally
  - Bazar a member paid for out of pocket counts as their contribution, just like a deposit
  - Clear balance for everyone: who **owes** money and who **gets money back**
- **Close month & archive** — save the finished month's summary into a history list, then start a fresh month with one click (members are kept)
- **Sample data included** — 4 members with meals, bazar and deposits pre-loaded so the demo is alive on first open
- **No sign-up, works offline** — all data is stored in the browser's localStorage

## Tech

- HTML
- CSS
- JavaScript (vanilla, no frameworks or build step)

## Author

**Nafiz Bin Azad**
CSE student at Southeast University, Dhaka, Bangladesh
GitHub: [@nafiz-xd](https://github.com/nafiz-xd)
