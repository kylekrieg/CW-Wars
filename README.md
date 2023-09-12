# CW Wars
Goal: Head to head CW decoding competition with an interactive spectator dashboard for live streaming.  

The software will have three components.  Competitor software, an internal spectator dashbaord and external interactive spectator dashboard.

## Rules of the Game
- Two CW operators go head to head trying to decode as many callsigns in 3 two min rounds.
- Best 2 of 3 rounds will crown the winner.
- Each operator will compete with the same list of callsigns or words.
- Two speeds for competition (SST (Slow Speed Contest) and FST (Fast Speed Contest))
- SST starts at 10wpm
- FST starts at 25wpm
- Operators are given 1 callsign/word to decode
- Callsigns/words are sent at different pitches
- Operators type in CW callsign/words into the entry field and press enter to submit
- 1 point for each correct callsign/word
- Operator with the most points wins

## Competitor Software (based on Rufxp)
- Operators start at the same speed based on their category.
- If an operator enters a correct call, the speed of the next contact is increased by 1 WPM.
- If an operator enters an incorrect call, the speed of the next contact is decreased by 1 WPM.

## Spectator Dashboard
- Spectators can see the next 2 callsigns to be sent to each operator
- On the spectator dashboard, past decoded callsigns/words are shown what calls were decoded correctly or incorrectly. 
- Spectators can pick callsigns for the operators to decode as the next call in line
- Real time operator stats are displayed, current score, # of correct calls, # of busted calls, currect WPM speed, speed they decoded each call at, graph over time of speed of the run.  

## Feature Requests
- Could give bonus points for X amount of calls correct in a row, last 15 seconds of each round is double the points, etc...
- Rounds could be different.  Round 1 - NA callsigns, Round 2- workds, Round 3 - international callsigns
- Could introduce QRM/QRN, etc...during the rounds
