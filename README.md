# CW Wars
Goal: Head to head CW decoding competition with an interactive spectator dashboard for live streaming.  

The software will have three components.  All of this is web based.  

Competitor software : This is the screen each competitor will see.  Users will enter in their callsign and after clicking the start button, the timer starts.
Internal Spectator Dashboard : This screen will be streamed in the background as a "status board" with touney brackets, past scores and also current scores/status of the current war.
External Spectator Dashboard : This will be a website all the viewers can view to interact with the current war.  

## Rules of the Game
- Two CW operators go head to head trying to decode as many callsigns in three 90 second rounds.
- Best 2 of 3 rounds will crown the winner.
- Each operator will compete with the same list of callsigns or words.
- Two speeds for competition (SST (Slow Speed Contest) and FST (Fast Speed Contest))
- SST starts at 10wpm
- FST starts at 25wpm
- Operators are given 1 callsign/word to decode
- Callsigns/words are sent at different pitches
- Each correct callsign in round 2, speed is increased by 1 WPM, incorrect calls are decreased by 1 WPM
- Operators type in CW callsign/words into the entry field and press enter to submit, spacebar repeats the current callsign.  Callsigns/words is not repeated after enter is selected.
- 1 point for each correct callsign/word
- Points are talled per round, after 3 rounds, if the score is tied for round 3, a 4th round is played with WPM increased by 1 WPM.

## Competitor Software (based on Morsle which is web based)
- Users pick their category (SST or FST)
- Operators start at the same speed based on their category
- Spacebar repeats the current callsign
- Selecting ENTER submits the current callsign
- No cw repeat after competitor submits a callsign
- If an operator enters a correct call, the speed of the next contact is increased by 1 WPM
- If an operator enters an incorrect call, the speed of the next contact is decreased by 1 WPM
- API call is avaliable to gather score and push calls into the stack of calls from external spectator dashboard

## Spectator Dashboard
- Spectators can see the next 2 callsigns to be sent to each operator
- On the spectator dashboard, past decoded callsigns/words are shown what calls were decoded correctly or incorrectly. 
- Spectators can pick callsigns for the operators to decode as the next call in line
- Real time operator stats are displayed, current score, # of correct calls, # of busted calls, currect WPM speed, speed they decoded each call at, graph over time of speed of the run.  

## Feature Requests
- Could give bonus points for X amount of calls correct in a row, last 15 seconds of each round is double the points, etc...
- Rounds could be different.  Round 1 - NA callsigns, Round 2- common words, Round 3 - international callsigns
- Could introduce QRM/QRN, etc...during the rounds
- Viewers are able to send superchats to enter in specific callsigns to get decoded
