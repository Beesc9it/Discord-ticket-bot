A cool Discord bot to manage tickets on your server 🎫

💬This is an open mini-project that allows you to make a ticket bot independently, intelligently configuring it to your needs, because it is an open code you do not need to buy me or another ticket bot hosting for him, you can quietly run it on your pc or on your hosting yourself!

⚙️Settings: This is the ticket bot manager.
In it you can quietly divide tickets into several reasons, from 4 to infinity, and customize them as you like, change the emoji, names, set up how and what role will moderate a certain ticket.

📖A little text guide 

1. First, in the root folder of the bot, go to the config.js file and insert your discord bot token in token: 'your token'.
2. Further in the events folder is interactionCreate.js this is the main code of the bot, there in the lines newTicket_ Court, newTicket_Guard, newTicket_Help, newTicket_Bank, you can completely replace what you want, most importantly leave newTicket_your text (after newTicket_ exactly exactly should be the name with label)
3. After that just below there is a case 'newTicket' and const roleMappings and there are our role IDs that moderate a particular ticket, you need to replace them with your role IDs (if you changed 'newTicket_ Court': for example to police, you need to replace it with newTicket_police, etc.)
4. Also below is permissionOverwrites where you also have to replace the role IDs with yours from line 114 of the code all the way down

🏁FINAL!
After you have done everything safely save the code and write !setup in the channel where you want the bot would place tickets!
