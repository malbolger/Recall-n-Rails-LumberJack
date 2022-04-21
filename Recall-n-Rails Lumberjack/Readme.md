# Recall-n-Rails Lumberjack
There are three main files (Harvester, BankController, RecallController) and then Rails that you will record, convert, and place into seperate folders to keep them tidy... RIGHT!?... right?

- RecallController - This file controls where we go after we use the bank or run from a rail.
	- What we set in here:
		- Do we use tracking? (line 33)
		- Do we use summons? (line 36)
		- How many runes in our book are dedicated to harvesting? (line 43)
		- The name of the Runebooks( I started you off with 2 example runebook names) (line 349 and line 389)
		- The name of your rail files ([Runebook_1] starts at line 353 and [Runebook_2] at line 393)
			+If you keep my naming convention for your books and rail files you only need to chage the random number to match the amount of runes in your book!

- BankController - This file controls turning our logs into boards, statshes them away, and restocks our regs.
	- What we set in here:
		- The restock agent we use for our regs (line 25)[regs should be in base of bank]
		- The organizer agent we use to dump boards to our bank (line 36)

- Harvester - This file controls harvesting, keeping our pet up, looking for reds, timings for movement, timeouts
	- What we set in here:
		- Do we use automatic movement? (line 17)
		- Movement delay to help with lagging off the rails (line 22)
		- How long until the whole script times out and goes into " red watch" mode (line 33)
		- How long until we timeout because of a GUMP or LAG (line 39)
		- How long before a swing it timed out and cannot perform another action without being told (line 45)

# Razor2Rail

- You will need to goto the starting point on your desired rail and ">info" yourself in game and write down your position

- You will need to take note of the direction you are facing when you start recording. (Up, North, Right, East, Down, South, Left, West) these are the directions from 12 o'clock clockwise.

- You will need to record a [macro] of the movements you would like this system to copy. 

- You will need to go to my github at https://github.com/malbolger/Razor2Rail and get the program "Razor2Rail" follow the onscreen instructions. This program will spit out a rails.txt file in the base directory. 

- You will need to copy the entire contents of this file to one of the rail files included that matches the starting point rune of this rail [Runebook_1][Book_1_Rail_1, Book_1_Rail_2, ect] where [Book_1_Rail_1] would be the first rune in the Runebook named [Runebook_1](default)

From this point you only need to goto your bank, click on the RecallController script and hit play! There will be some hiccups and reds have learnt my frequent spots and some have begin.

© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
