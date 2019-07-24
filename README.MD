<h2>Rock Paper Scissors Script with an LS extra</h2> 

<h3>Classic *!rps*</h3>

    Scissors cuts Paper 
    Paper covers Rock 
    Rock crushes Scissors 

Boring? Look further down

</h3>Lizard Spock *!rpsls*</h3>
    Scissors cuts Paper 
    Paper covers Rock 
    Rock crushes Lizard 
    Lizard poisons Spock 
    Spock smashes Scissors 
    Scissors decapitates Lizard 
    Lizard eats Paper 
    Paper disproves Spock 
    Spock vaporizes Rock 
    (and as it always has) Rock crushes Scissor

- http://www.samkass.com/theories/RPSSL.html
- https://bigbangtheory.fandom.com/wiki/Rock,_Paper,_Scissors,_Lizard,_Spock

<h3>Settings</h3>
* **Classic - command** (classic_command) - Command to play the classic "Rock, Paper, Scissors". Empty to disable
* **Lizard, Spock - command** (lizardspock_command) - Command to play "Rock, Paper, Scissors, Lizard, Spock". Empty to disable
* **Localisation** (localisation_file) - Name of the file containing desired localisation.
* **Winner gets currency** (reward) - Amount of Chatbot currency to give when someone wins against the bot.
* **User cooldown** (user_cooldown) - In seconds - Cooldown per user preventing abuse.

<h3>Localisation</h3>
**#** is a reserved characters for comments `# Comments in file`

2 language are supported for the moment but you can easily tweake the code to add yours.
1. Copy *local_en.txt* and rename it
2. Translate and customize your message
3. Add the new file name in this list (*UI_Config.json* line 21)

<h4>Messages parameters:</h4> 
- `{user}` : Username 
- `{phrase}` : Simple phrase like "Paper covers Rock". *N/A on equality*. 
- `{user_pick}` : Show user choice like "Paper" 
- `{bot_pick}` : Show bot choice like "Rock"

<h3>Usages vs bot</h3>
`!rps` + Rock, Paper or Scissors

`!rpsls` + Rock, Paper, Scissors, Lizard, Spock
