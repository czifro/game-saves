# game-saves

Local Game Saves

## Instructions

Create new branch `<game-name>-master` and push to remotei. This will function as a
clean slate starting point for your game. DO NOT PUSH NEW COMMITS TO THIS BRANCH.

For new gameplays, branch off of `<game-name>-master` (recommended to use `<game-nme>` as prefix).

Temporarily start a new gameplay session just to generate save files, then close game. Move save files
to location of this git repo (note, to avoid potentially nuking local repo, move directory containing save files).

Now create a symbolic link that points the old save file location, to the new one. Commit changes to local repo.
This can function as starting point of gameplay in case you want to restart.

If possible, increase limit of auto-saves if the game supports it. Also, try to save frequently. Commit saves often
as this can allow you to revert back to an older save point in the game. This can allow you to explore different
paths and see the consequences of different actions.

