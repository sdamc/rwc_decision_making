# Product overview
Product for decision making analysis of the rugby tier 1 nations's games

Objectives:
1- Create a tool for video analysis
2- Automate data ingestion from the tool
3- Create ML models to analyse data and to create predictions
4- Create a dataviz to show results

1 Rugby Video Analysys Tool:

Step 1:
Define the output data and business rules to be extracted from the videos.

The final product will be focused on on decision making analysis in open play. On each phase play, there will be recorded an action and the corresponding outcome.
Data will be completed by joining with the lineup and substitutions from each game, so it will be possible to get insight based on each lineup, with focus on the main decision makers.
Attributes:

* PlayId (one indexing number for each play, created automatically)
Fixed for each play:
  * Minute (it will be used to join with the lineup. It is also source for timeline analysis)
  * Field Position (1 - opposing 22m; 2- own half; 3- opposing half; 4- opposing 22m)
  * Play type (scrum, lineout, tap kick, kickoff or counterattack)

Variables inside a play:
* Phase number (starts with 0 for set pieces, counter attack and restarts)
* Point of attack (A- Inside the 3rd defender; B- after the 3rd defender but before the winger; C- ball goes to the wing)
* Decision (Pass, Carry...)
* Outcome (Gainline Success, Gainline Failure, Linebreak...)


Step 2:
Define the GUI.

Step 3:
Identify the computer vision library or framework for video analysis. 
Tensorflow for object detection (ball, player, field position).




