# How to read the Pairings and Standings

<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=3 --minlevel=1 -->

- [How to read the Pairings and Standings](#how-to-read-the-pairings-and-standings)
  - [Standings](#standings)
    - [Pos](#pos)
    - [NAME](#name)
    - [*Rtg](#rtg)
    - [*T](#t)
    - [*Fed](#fed)
    - [Pts](#pts)
    - [1...2](#12)
    - [Tiebreakers](#tiebreakers)
  - [Pairings](#pairings)

<!-- mdformat-toc end -->

The Swiss system is very popular in chess tournaments. That means there's some
sophisticated software out there for managing Swiss system tournaments... for
chess. I use chess software from VegaChess.com to manage the Swiss section of
tournament pairings. It's very convenient because it has several features that
are useful for me that aren't present on other apps like Challonge or
BinaryBeast.

However, since the software is designed with chess tournaments in mind only,
some of the output may seem confusing if you're not familiar already.

## Standings

For example, each week I post a standings table showing the relative rank of
each team's performance after the previous round. Here's a breakdown.

An asterisk means you can ignore this column: it is not relevant to anything in
the tournament.

### Pos

Position, or rank. A lower number is better.

### NAME

This is the name of the team being ranked.

### \*Rtg

Elo rating. This is the chess equivalent of MMR. Since teams in aren't rated,
it's not used.

### \*T

I don't even know what this is supposed to be for.

### \*Fed

Which of the many regional chess federations the player is from. I didn't fill
this in. So, the software filled "USA" as the default for everyone (of
course!).

### Pts

The number of points scored. This one is important.

### 1...2

Whether you won or lost in each round, and who against. As the tournament
progresses the results from each round will be filled in here. Because the
software thinks this is a chess tournament, it also thinks you played the white
or black side in each game. So `+W33` means you won against the team in
position 33 (see "Pos" column). `-B20` means you lost against the team in
position 20. +BYE or -BYE means you either got a bye or a forfeit. (It would be
nice if it didn't conflate byes with forfeits, but that's what it does.) You
can ignore the W and B in `+B10` or `-W24` etc.

### Tiebreakers

Everything after that is for the tiebreakers. How each tiebreaker works, and
the differences between them, is complicated. What you need to know is:

1. Ties are broken from left to right. The first tie breaker that is different
   between two teams breaks the tie.
1. The Pts column is the first tiebreaker. If there is a tie on points, the
   next tiebreaker (BucM) is used. And so on.

I get that these charts aren't super user friendly. There's a lot of info and
not all of it is relevant. If you have questions, let me know and I'll update
this post if necessary.

## Pairings

This one is a lot simpler, because you can ignore pretty much everything on it
except the team names. If there is the name of another team across from yours,
you're playing vs them in that round.

If it says "(bye)" or "(not paired)" or anything else of such, you're not
playing this round. Usually, "(not paired)" is for teams that have been
withdrawn from the tournament. "(bye)" is the free win you get if you're the
lucky one because we have an uneven number of teams being paired in that round.
