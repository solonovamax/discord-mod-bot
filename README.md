### Request
"Hey cheeseits a need a new bot whenever your ready:  
`:mute USERNAME (timelimit in s, m, h, d)`  
`:purge (number) (purges the messages)`  
`:warn (username)`  
Can you also make it so it DM's the person when they got muted or warned"

### How to Use
- Create a new Discord bot
- Add the bot to your desired server
- Open `config.json` and fill in the information
- Run `setup.bat` and wait for it to automatically close when it's finished
- Run `run.bat` to run the bot

### Additional Information
I've put in error catches for absolutely everything that could go wrong with this script as far as user error is concerned, so instead of getting a confusing wall of "error text" in the console, it'll give you simple instructions for how to fix what's not working. Due to the error catching, you could technically skip all of the steps in the `How to Use` section and simply run `run.bat`, then go through and fix the errors one at a time. This code was written with user-friendliness in mind.