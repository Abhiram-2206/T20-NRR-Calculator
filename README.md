
T20 NET RUN RATE (NRR) CALCULATOR
==================================

A Python-based Net Run Rate (NRR) calculator that follows official ICC tournament rules for T20 cricket.

------------------------------------------------------------
ABOUT NET RUN RATE (NRR)
------------------------------------------------------------

NRR = (Total Runs Scored / Total Overs Faced)
      -
      (Total Runs Conceded / Total Overs Bowled)

Since cricket overs are not true decimals, this program:
- Converts overs to balls (base-6 system)
- Calculates run rate using: (Runs / Balls) * 6
- Applies ICC all-out rule correctly


------------------------------------------------------------
FEATURES
------------------------------------------------------------

- Multi-match NRR calculation
- Accurate overs-to-balls conversion
- ICC all-out rule implementation
- Clean and modular logic
- Command-line interface (CLI)


------------------------------------------------------------
ICC RULE IMPLEMENTED
------------------------------------------------------------

In T20 cricket:

1) If a team is all out before 20 overs,
   -> Full 20 overs (120 balls) are counted for NRR.

2) If a team finishes a chase early,
   -> Actual overs faced are counted.

3) If opponent is all out early,
   -> Full 20 overs are counted for bowling side.

This ensures official tournament-level accuracy.


------------------------------------------------------------
PROJECT STRUCTURE
------------------------------------------------------------

T20-NRR-Calculator
    NRR_Calculator.py
    README.md


------------------------------------------------------------
HOW TO RUN
------------------------------------------------------------

1) Make sure Python 3 is installed.
2) Run the script:

   python NRR_Calculator.py


------------------------------------------------------------
INPUT FORMAT
------------------------------------------------------------

Enter comma-separated values for multiple matches.

Example:

Enter runs scored: 187,177
Enter overs faced: 20,16.1
Enter wickets lost: 3,5
Enter runs conceded: 111,176
Enter overs bowled: 18.5,20
Enter wickets taken: 10,8


------------------------------------------------------------
EXAMPLE OUTPUT
------------------------------------------------------------

NRR: 2.890


------------------------------------------------------------
FUTURE IMPROVEMENTS
------------------------------------------------------------

- Points table generator
- Multi-team leaderboard
- Full tournament simulator
- OOP refactor
- GUI or Web version


------------------------------------------------------------
LICENSE
------------------------------------------------------------

MIT License


------------------------------------------------------------
AUTHOR
------------------------------------------------------------

Developed as a cricket analytics learning project applying 
programming logic to real-world tournament rules.

