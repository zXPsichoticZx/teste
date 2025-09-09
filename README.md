[![Github Profile](https://img.shields.io/badge/Github-Yours_Jarvis-blueviolet?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/)
[![Library](https://img.shields.io/badge/Library-Python_v3.8-orange)](https://www.python.org/) 
[![Python](https://img.shields.io/badge/Python_Library-discord.py_v1.7.3-blue?style=flat&logo=python&logoColor=white)](https://discordpy.readthedocs.io/en/stable/) 
[![Github repo version](https://img.shields.io/badge/Discord_Online_Client-v3.1.0-brightgreen?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v3.1.0) 
[![Github Releases](https://img.shields.io/badge/Github-Releases-ff0000?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases) 
[![GitHub repo size](https://img.shields.io/github/repo-size/Yours-Jarvis/Discord-24-7-Online-Client?color=00ffff&label=Repository%20Size&logo=github)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/)
[![platform replit](https://img.shields.io/badge/Platform-Replit-000000?style=flat&logo=replit&logoColor=white)](https://replit.com/)

*<h1 align="">Discord-Online-Client <3</h1>*
*<h3>Make your Discord Bot/Account Online 24/7 ----</h3>*
> ***Discord 24-7 Online Client, [Python](https://www.python.org/) Script that helps you to keep your discord bot/account online 24/7.  Built with [discord.py](https://discordpy.readthedocs.io/en/stable/)***
----

*<h3>🚀 Starting ----</h3>*
***I will prefer to run it on repl.it as it gives more convinience than glitch website.. Go to repl.it [here](https://repl.it/).To gain free hacker plan, go to [here](https://repl.it/claim) and paste this code there***

***Code - Linux-Jarvis***

----
***A Code written in Python that helps you to keep your discord bot/account online 24/7***

***The [main.py](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/main/main.py) is the main file. [keep_alive.py](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/main/keep_alive.py) prevents your repl from going to sleep. (If you have a replit hacker plan, then you can delete [this file](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/main/keep_alive.py) and paste this code inside the [main.py](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/main/main.py) file :***

```py
import discord
import os
from discord.ext import commands

client = commands.Bot(command_prefix='..', self_bot=True, help_command=None)

@client.event
async def on_ready():
    activity = discord.Activity(type=discord.ActivityType.listening, name="Yours-Jarvis on Github") # Activity Types :- listening, watching, streaming, playing
    await client.change_presence(status=discord.Status.dnd, activity=activity)

client.run(os.getenv("TOKEN"), bot=False)
```
**DO NOT GIVE YOUR DISCORD TOKEN TO OTHERS!**
  
- ***Use [Uptime Robot](https://uptimerobot.com/) to make your repl online 24/7.***
- ***And Please Consider the Reading, [Setup to Uptime Robot.]()***

**IF YOU HAVE ANY DOUBTS REGARDING THIS, FEEL FREE TO [CONTACT ME!](https://github.com/Yours-Jarvis/)**

- ***You Can Find Me Here: ----***
- ***Discord:***

 [![Discord](https://img.shields.io/badge/Discord-Add_to_Jarvis-blueviolet?style=flat&logo=discord&logoColor=white)](https://discord.com/users/899961311771897877)
 [![Discord](https://img.shields.io/badge/Discord-Server_1-brightgreen?style=flat&logo=discord&logoColor=white)](https://discord.gg/kVKz4utJ9G)
 [![Discord](https://img.shields.io/badge/Discord-Server_2-brightgreen?style=flat&logo=discord&logoColor=white)](https://discord.gg/qeQ3VStAQ6)
 [![Discord](https://img.shields.io/badge/Discord-Server_3-brightgreen?style=flat&logo=discord&logoColor=white)](https://discord.gg/RrABUqmDUF)

**For repl.it users** -
- **Tap on this --**

 [![Replit Fork](https://img.shields.io/badge/Replit-Tap_on_this-000000?style=flat&logo=replit&logoColor=white)](https://replit.com/github/Yours-Jarvis/Discord-24-7-Online-Client/)

----

*<h3>🛠 Main.py Example Files ----</h3>*
***I Have Given you 2 Example Files of Main.py - [[main.py] Dc Account.example](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Account.example) Or [[main.py] Dc Bot.example](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Bot.example)***
  
- **[[main.py] Dc Account.example:](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Account.example)** ***This Code was helps you to keep your Discord Account online 24/7***

```py
import discord
import os
import keep_alive

from discord.ext import commands

client = commands.Bot(command_prefix='..', self_bot=True, help_command=None)

# <!-- Import Your Self Bot Commands <3 --> 

@client.event
async def on_ready():
    activity = discord.Activity(type=discord.ActivityType.listening, name="Yours-Jarvis on Github") # Activity Types :- listening, watching, streaming, playing
    await client.change_presence(status=discord.Status.dnd, activity=activity)

keep_alive.keep_alive()
client.run(os.getenv("TOKEN"), bot=False)
```  
***HOW TO USE IT: Copy the code from [[main.py] Dc Account.example](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Account.example) File and then paste your code inside the [main.py](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/main.py) File.***
<br> </br>
- **[[main.py] Dc Bot.example:](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Bot.example)** ***This Code was helps you to keep your Discord Bot online 24/7***

```py
import discord
import os
import keep_alive

from discord.ext import commands

client = commands.Bot(command_prefix='..')

# <!-- Import Your Bot Module/Commands <3 -->

@client.event
async def on_ready():
    activity = discord.Activity(type=discord.ActivityType.listening, name="Yours-Jarvis on Github") # Activity Types :- listening, watching, streaming, playing
    await client.change_presence(status=discord.Status.dnd, activity=activity)

keep_alive.keep_alive()
client.run(os.getenv("TOKEN"), bot=True) # if the line does't work so replace this line of code || client.run(os.getenv("TOKEN") ||
```
***HOW TO USE IT: Copy the code from [[main.py] Dc Bot.example](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/%5Bmain.py%5D%20Dc%20Bot.example) File and then paste your code inside the [main.py](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/blob/3feaaa0a5fcca1bdcd666ccd1f8e84a2075256f3/main.py) File.***

----


*<h3>🔥 Setup to Uptime Robot ----</h3>*
***After Completing all the required installments and the changes head over to [Uptime Robot](https://uptimerobot.com/) and login there..Choose the monitor as `https`.Then you would need a link..You could get the link in the web section of you project..First time if you dont run the project you could not see that section.Run the project and you could see it.Then paste the link in [uptime robot](https://uptimerobot.com/) and take any name and click monitor..And your project will be online 24/7..***

***We Are Also Gonna Add Some More New Amazing & Existing Features...***
***🚀 Please [follow](https://github.com/Yours-Jarvis) on [GitHub](https://github.com/Yours-Jarvis) to stay tuned with us for more Exciting future Updates like this.***

----

*<h3>✔ Discord-Online-Client Version ----</h3>*

- ***Current Version:***
  
  [![Github version](https://img.shields.io/badge/Version-3.1.0-success?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v3.1.0)
   
- ***Previous Version:***

  [![Github Releases](https://img.shields.io/badge/Github-Releases-ff0000?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases) [![Github version](https://img.shields.io/badge/Version-3.0.1-success?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v3.0.1) [![Github version](https://img.shields.io/badge/Version-2.1.0-success?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v2.1.0) [![Github version](https://img.shields.io/badge/Version-2.0.1-success?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v2.0.1) [![Github version](https://img.shields.io/badge/Version-1.0.1-success?style=flat&logo=github&logoColor=white)](https://github.com/Yours-Jarvis/Discord-24-7-Online-Client/releases/tag/v1.0.1)
----

> *<h4 align="center">⭐ Feel free to Star the Repository if this helped you!</h4>*
----
> *<h4 align="center">Discord-Online-Client © 2022 by Yours-Jarvis is licensed under GNU General Public License v3.0 and Attribution 4.0 International</h4>*
