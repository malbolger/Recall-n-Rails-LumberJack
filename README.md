<div id="header" align="right">
	<h1>
  		GRAB IT HERE! <img src="https://s3.envato.com/files/148177745/Still.jpg" width="100"/>
	</h1>
</div>

# Recall-n-Rails-System   
- You will make your rails with Razor2Rail https://github.com/malbolger/Razor2Rail see video below for a guide on how I do it.

# Recall-n-Rails Lumberjack
- **Demonstration Video**
	- [![IMAGE ALT TEXT](https://user-images.githubusercontent.com/11452884/168937498-c38908ff-ac6e-4f6d-9456-3cbf74fd59a4.png)](https://www.youtube.com/watch?v=_5iBAGw_LBE "Recall -n- Rails Demo")
	 
## **Important!** ##
	- Remember the direction you are facing when you hit [record] on your macro, input this in Razor2Rail!
	- Turn off system message filtering in razor! We need these messages for the script!
	- Do not have other scripts or catagories named the same as these files!
	- Use a mount or you will need to set movementDelay over 400
	- Set your bank rune in your runebook as your default rune
	
- **RecallController** - This file controls where we go after we use the bank or run from a rail.
	- What we set in here:
		- Do we use tracking? (line 47)
		- Do we use summons? (line 50)
		- How many runes in our book are dedicated to harvesting? (line 57)
		- The name of the Runebooks( I started you off with 2 example runebook names) (line 374 and line 414)
		- The name of your rail files ([Runebook_1] starts at line 378 and [Runebook_2] at line 418)
		- If you keep my naming convention for your books and rail files you only need to change the random number to match the amount of runes in your book!

- **BankController** - This file controls turning our logs into boards, statshes them away, and restocks our regs.
	- What we set in here:
		- The restock agent we use for our regs (line 31)[regs should be in base of bank and restock 30 or more]
		- The organizer agent we use to dump boards to our bank (line 42)

- **Harvester** - This file controls harvesting, keeping our pet up, looking for reds, timings for movement, timeouts
	- What we set in here:
		- Do we use automatic movement? (line 31)
		- Movement delay to help with lagging off the rails (line 36)
		- How long until the whole script times out and goes into " red watch" mode (line 52)

# Razor2Rail

- **Rail Creation Video**
	- [![IMAGE ALT TEXT](https://user-images.githubusercontent.com/11452884/167266722-cae5765e-c830-42ac-aa7f-83e71f90dbd1.jpg)](https://www.youtube.com/watch?v=xAIKKuQ62sI "Rail Creation for Razor2Rail")

- **Instructions**
	- You will need to goto the starting point on your desired rail and ">info" yourself in game and write down your position

	- You will need to take note of the direction you are facing when you start recording. (Up, North, Right, East, Down, South, Left, West) these are the directions from 12 o'clock clockwise.

	- You will need to record a [macro] of the movements you would like this system to copy. 

	- You will need to go to my github at https://github.com/malbolger/Razor2Rail and get the program "Razor2Rail" follow the onscreen instructions. This program will spit out a rails.txt file in the base directory. 

	- You will need to copy the entire contents of this file to one of the rail files included that matches the starting point rune of this rail [Runebook_1][Book_1_Rail_1, Book_1_Rail_2, ect] where [Book_1_Rail_1] would be the first rune in the Runebook named [Runebook_1]
