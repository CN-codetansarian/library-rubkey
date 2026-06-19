![library rubkey](rubika.png)

# Rubkey

**Rubkey** is a Python library for building bots in the **Rubika** messenger. This library allows you to easily build your own bots with minimal code using the Rubika Bot API.

Whether you want to build a simple bot to respond to messages, or a complex bot with inline keypads and group management, Rubkey has it all for you. This library supports both **Sync** and **Async** methods and is suitable for small and large projects.

## Sample Code (Async)

```
import asyncio
from rubkey import AsyncBot

TOKEN = ""
bot = AsyncBot(token=TOKEN)

@bot.command("start")
async def start(msg):
    await msg.reply("hello")

async def main():
    await bot.run()

if __name__ == "__main__":
    asyncio.run(main())
```

MIT License

![Rubkey](rubkey.png)
