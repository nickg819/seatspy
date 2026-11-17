# SeatSpy

A phone app for live poker that keeps a read on every player at your table and shows you how to exploit them.

<p>
  <img src="docs/screens/table-read.webp" width="165" alt="The table in Simple Mode, with a plain line on how to play each seated player">
  <img src="docs/screens/howto.webp" width="165" alt="How to Exploit Them for one player, split into Go after them and Hold back">
  <img src="docs/screens/saved.webp" width="165" alt="Saved Players, a list of players with their type icons">
  <img src="docs/screens/glossary.webp" width="165" alt="The Glossary, with every player type and term">
</p>

## Why I Built It

I play live poker against a lot of the same people, at a home game, in cash games and at the casino. I’d learn how someone played and forget most of it by the next session. My reads ended up in my head, in a notes app or nowhere. Poker apps mostly track hands and bankroll, and their player notes rarely say what to do about a read.

SeatSpy ties every read to a plan. You spot the type, then go after the mistakes that type makes.

## How a Session Works

Tap a seat to add someone from your book, a stranger or one of tonight’s players waiting in the tray. Tag each player with a type, like Calling Station, NIT or Maniac, or let Quiz Me ask what you’ve seen and rank the likely types. Each player’s panel then says when to bluff them, when to bet for value and when to back off.

Reads stay with the player. The next time they sit down, you start where the last session left off.

## What Else Is in It

- Each player can hold up to three of the twelve types.
- Simple Mode shows three plain lines per type, and Full Detail adds stats, bet sizing and preflop play.
- Log What They Did records a play or a tell and the type it points to.
- Incognito Mode shows tagged seats as dots, so nobody next to you can read your screen.
- Learn has a poker glossary, a card for every type and quizzes on both.
- Equity Calculators work out showdown equity in Hold’em and Pot-Limit Omaha, double-board bomb pots included. Give up to nine players a hand or a range, paint ranges on a 13 by 13 grid and save the ones you use.
- What Is Equity? covers equity, outs and the price of a call in six short pages, and ends on a spot to guess.
- The ICM Calculator works out a deal at the end of a tournament, by ICM or by chip EV.

## Built With

SeatSpy is built with Expo and React Native, in TypeScript. Expo Router handles navigation, expo-sqlite keeps the book on the phone, and Reanimated and Gesture Handler run the table’s drag and press gestures. The equity calculators run on the phone too. They work a hand out exactly when the phone can finish in about three seconds, and run Monte Carlo deals when it can’t. EAS Build makes the iPhone and Android builds, and EAS Update ships fixes over the air.

## Get the App

Request beta access at [seatspy.app](https://seatspy.app/). iPhone testers get a TestFlight invite at the email on their Apple ID. On Android, install it from [seatspy.app/android](https://seatspy.app/android/).

## About This Repo

This repo is the project page, and the `docs` folder is the site at [seatspy.app](https://seatspy.app/), with the Privacy Policy and Terms of Use. The source code is private, and I’m not taking contributions. If something breaks, use Report a Bug in the app’s Settings.

## License

Copyright 2026 Nick Gassmann. All rights reserved.
