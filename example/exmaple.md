# ��� ��: Discord Bot
```python
...
import discord_fortuneTell
...
@bot.command(aliases=['�'])
async def today_fortune(ctx, *args):
    args = list(args)
    await ctx.send(discord_fortuneTell.out(args))
# my_bot�� �ۼ��� �ڵ�
```
```python
import erumyFortune
...
def out(args):
    ...
    return res_str
# src/discord_fortuneTell.py
```
[Discord.py](https://github.com/Rapptz/discord.py) ����� ���ڵ� ���� ���� � �˸� ����� �߰��� �����Դϴ�.
## ��� ���
---
������ �  
![](./img/tdy.png)  
----
������ �  
![](./img/tm.png)  
---
������� �
![](./img/smday.png)  
---