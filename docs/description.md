## Introduction

Pull this repo down

Follow the installation instructions https://docs.privategpt.dev/

Once completed, run `PGPT_PROFILES=local make run`

Visit http://localhost:8001

Feel free to add your own player to `player.yml`. Upload `enemies.yml` and `player.yml` via the UI and API

Provide a scenario: (Try this untested)

We have a 10 sided dice. If i roll a 10, an enemy will die immediately and it's health will go to 0. If i roll a 1, the attack will miss and the enemies health will remain the same. If i roll any other number, the attack will hit equal to the amount of damage of said attack

If an enemies health is greater than 0, the enemy will not die.

I'm the player [players name]. I'm going to attack a goblin with my fire blast skill. I rolled a 4. Tell me what happened to the goblin as a fantasy story? Do not mention any dice rolls.