# Freeze
#### More documentation can be found here at the [Custom Commands website!](https://dynocc.tk/freeze)
Usage: ```?freeze```

Description: Mutes everyone by setting their role to **FREEZE**

Code:
```{delete}
{silent}
{require:serverAdmin}
{!role all +freeze}
**<:thumbsup_blob:345039968693125120> Chat frozen**
```

What ```{delete}``` does: It deletes your message when you run the command.

What ```{silent}``` does: It will do it quietly, like a NINJA!!!

What ```{require:serverAdmin}``` does: It will not run the command unless the user has the ```serverAdmin``` role!

What ```{!role all +freeze}``` does: If they have the ```serverAdmin``` role, it gives everyone the role ```Freeze```!


Steps to make it work:
- Paste it in the response box
- Make sure that there a ```serverAdmin``` and a ```freeze``` role
- Last thing, have the ```freeze``` role not have the send messages permission!

Still need help? Join <a href="https://discord.gg/fACYsbu">our Discord Support Server!</a>
