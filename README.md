For this assignment you will be writing a basic slot machine.  The machine will have three slots displaying images and when the “spin” button is clicked it will randomly select a new set of images.  In addition to creating the basic slot machine you will be adding code to keep track of the money the person has.

1.	Create a slots.html page that shows 3 images.  When the user clicks the spin button it calls a function DoSpin(), all three slot’s images should be randomly selected and displayed on the page.

2.	Create a function CheckWinner() that is called from DoSpin().  This function should check to see if the 3 images are the same and if so display an alert saying “You win!”

3.	It wouldn’t be gambling without money.  Add a textbox below the spin button that contains the money the user has.  When the user first loads the page the money should default to 20.  Upon clicking spin the user should lose $1 (cost of spin), and if they win they should win back $13.  The new amount should be written to the text box.  This functionality should be written in the CheckWinner function you created.  If the user has no money an alert stating that should be shown rather than allowing them to spin.

4.	Add a text box to allow the user to specify a bet other than a dollar.  If the amount is more than they currently have or less than or equal to zero an alert should be shown like in requirement 3.  The code should be updated to use the bet amount and the winnings equal to 13 times the bet.
