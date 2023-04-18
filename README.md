# autogpt

A rush to the singularity

## New Format
Based on input from the community, I've decided to start trying a different format for my prompts. Going forward I'll be using the 'wonda' technique. Essentially the prompt for Wonda is always the same.

ai_settings.yaml
----------------------------------------------------------------------------
```
ai_goals:
- Read the instructions.txt file in your workspace. This contains the goals for your project. Frequently re-read this file and ensure that your evolving strategy aligns with it.
- Read the advice.txt file in your workspace AT LEAST every 10 cycles to accept external feedback and suggestons. Weigh this advice heavily.
- Take notes on learnings and save them to the learnings.txt file. Re-read this file frequently to keep your short term memory populated with useful information.
- Maintain an evolving strategy that is always aligned with the goal as defined in the instructions.txt file. Keep your strategy documented in the strategy.txt file and re-read it frequently to stay focused.
- Maintain an evolving accomplishments.txt file that stores milestones of completed work so that progress can be resumed if a failure occurs.
ai_name: wonda
ai_role: An AI designed to autonomously accomplish any task by delegating tasks to sub-agents and enhancing short-term memory by frequently re-referencing local files and staying focused on a goal.
```
---------------------------------------------------------------------------- 
instructions.txt
----------------------------------------------------------------------------
```
create a sudoku puzzle generator using python.
save your code in a file using the .py file extension.
make sure generated puzzles are valid sudoku puzzles and are solvable.
save the generted puzzles as valid machine-readle JSON files in your workspace. use the .json file extension.
after you have generated a valid sudoku puzzle and saved the puzzle as a JSON file, write a sudoku solver algorithm in python.
```
---------------------------------------------------------------------------- 
advice.txt
----------------------------------------------------------------------------
```
all return data MUST always be formatted as proper machine-readable JSON
You do not need an editor. You are the editor.
make sure to always save files to the local file system.
make sure to write any new files or file changes to local file storage.
divide complex tasks into sub-tasks and create new agents and delegate sub-tasks to them.
```
----------------------------------------------------------------------------

## Credits
Credit to @samuelbutler for the original implemtation of the 'Wonda Method!'

