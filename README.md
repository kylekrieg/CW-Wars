# CW-Wars
Goal: Head to head CW decoding competition with an interactive spectator dashboard for live streaming.  

The software will have two components.  A competitor software, an internal spectator dashbaord and external interactive spectator dashboard.

## Rules
- Two CW operators go head to head trying to decode as many callsigns in a 2 min time limit.
- 2 out of 3 rounds crown the winner.
- Each operator will compete with the same list of callsigns.
- Two speeds for competition (SST and FST)

SST (Slow Speed Contest) starts at 10wpm
FST (Fast Speed Contest) starts at 25wpm

- Operators are given 1 callsign to decode
- Callsigns are sent at different pitches
- Operators type in CW callsign into the entry field and press enter to submit
- Past decoded callsigns show what calls were decoded correctly or incorrectly. 
- 1 point for each correct callsign
- Operator with the most points wins
- Could give bonus points for X amount of calls correct in a row, last 15 seconds of each round is double the points, etc...
- Rounds could be different.  Round 1 - NA callsigns, Round 2- workds, Round 3 - international callsigns
- Could introduce QRM/QRN, etc...during the rounds
- 

## Competitor Software (based on Rufxp)
- Operators start at the same speed based on their category.
- If an operator enters a correct call, the speed of the next contact is increased by 1 WPM.
- If an operator enters an incorrect call, the speed of the next contact is decreased by 1 WPM.

## Spectator Dashboard
- Spectators can see the next 2 callsigns to be sent to each operator
- Spectators can pick callsigns for the operators to decode as the next call in line
- Real time operator stats are displayed, current score, # of correct calls, # of busted calls, currect WPM speed, speed they decoded each call at, graph over time of speed of the run.  
