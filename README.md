# Xeili (DEVELOPER BUILD)
Xeili is a discord bot built on Python using the discord.py library.

Special thanks to github user Pandentia for help with the code.

This branch is for the developer build of Xeili.

# B..but what's the difference?
This branch includes more stuff like Tracebacks and a few more code fixes.
The 'fragment' system has also been renamed to just 'module' as fragments was too corny.
All core commands now have a semi-proper checks (or as i like to call it, Confirm) instead of using ifs.
This branch is most likely gonna be more developped than the Master branch and eventually merged when ready.

# O..okay but, can I use it?
All you have to do is put your ID in utils/confirm.py and your token in Xeili.py and you're good to go.
To boot the bot on Windows or any OS you HAVE to have Redis installed.
Ports & Redis Database to be used can be set using --port and --db arguments.
Booting Xeili without arguments will result into connecting to Redis with the default configuration, Being port 6379 and Redis_Database 0.

Don't understand how to set it up? Well you can mention me in the following discord server: https://discord.gg/5sHTkKq

Default prefix is "test " can be changed in Xeili.py

# HELP I'M HAVING ISSUES!!!!11!
Open a damn Issue then.
(I accept both User-side and Bot-side issues.)

# Why this branch tho?
Cause I know I am gonna lose the code at some point.... Don't judge me.
