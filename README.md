# 2-player-reaction-game-Verilog

## how to run
1. Make sure Vivado is installed on your device.
2. Download the zip file.
3. In folder, extract the zip file, then extract the Lab 5 done zip file.
4. Click on the Lab 5 Vivado Project File.
5. Once Vivado opens, click on Open Hardware Manager under the Flow Navigator, and make sure to connect to the BASTS3 board.
6 Once that is done, click on Program device.

## Description
BtnC is used to start each round of the game. There are 3 lights on the LEDs that will turn on in the middle of the board and will run back and forth for 8 seconds or until a player has pressed a button. A random target number is generated on the left-most anode of the 7 segment display. 

The player on the right gets a point if they press btnR when the LED lights up on the target switch. Their point is displayed on the right most anode of the 7 segment display. The player on the left gets a point if they press btnL when the LED lights up on the target switch. Their point is displayed to the left of player right's score.

If a player pressed their button on the incorrect LED, then the other player gains a point. 

The game is over if either player reaches 8 points. The right most led will light up if player right wins. The left most led lights up if the player left wins. Pressing btnU will reset the game, restting the scores to 0.
