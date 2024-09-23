# BlumAutoBot

<p>Blum Auto Bot is script that uses blum api to get points automatically without extra effort</p>
<p>copy your query link blum account in "url.txt" file which can support multi account(every line one account)</p>

___

config that you can change in config.json file
like Below

```json
{
    "interval": 5, 
    "auto_complete_task": false, 
    "auto_play_game": true, 
    "game_point": {
        "low": 240,
        "high": 250
    }
}
```

set auto_complete_task to true if you want to complete task automatically in blum
set auto_play_game to true if you want to script to use cards automatically to get point in range low and high gamepoint  
