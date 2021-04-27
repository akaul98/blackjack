This is the blackjack game created with the help of python. 
 Rules of balckjack
 Players are each dealt two cards, face up or down depending on the casino and the table. In the U.S., the dealer is also dealt two cards, normally one up (exposed) and one down (hidden). In most other countries, the dealer only receives one card face up. The value of cards two through ten is their pip value (2 through 10). Face cards (Jack, Queen, and King) are all worth ten. Aces can be worth one or eleven. A hand's value is the sum of the card values. Players are allowed to draw additional cards to improve their hands. A hand with an ace valued as 11 is called "soft", meaning that the hand will not bust by taking an additional card. The value of the ace will become one to prevent the hand from exceeding 21. Otherwise, the hand is called "hard".

Once all the players have completed their hands, it is the dealer's turn. The dealer hand will not be completed if all players have either busted or received blackjacks. The dealer then reveals the hidden card and must hit until the cards total up to 17 points. At 17 points or higher the dealer must stay. (At most tables the dealer also hits on a "soft" 17, i.e. a hand containing an ace and one or more other cards totaling six.) You are betting that you have a better hand than the dealer. The better hand is the hand where the sum of the card values is closer to 21 without exceeding 21. The detailed outcome of the hand follows:

If the player is dealt an Ace and a ten-value card (called a "blackjack" or "natural"), and the dealer does not, the player wins and usually receives a bonus.
If the player exceeds a sum of 21 ("busts"), the player loses, even if the dealer also exceeds 21.
If the dealer exceeds 21 ("busts") and the player does not, the player wins.
If the player attains a final sum higher than the dealer and does not bust, the player wins.
If both dealer and player receive a blackjack or any other hands with the same sum called a "push", no one wins.
Blackjack has over 100 rule variations. Since the 1960s, blackjack has been a high-profile target of advantage players, particularly card counters, who track the profile of cards that have been dealt and adapt their wagers and playing strategies accordingly. In response, casinos have introduced counter-measures that can increase the difficulty of advantage play.

Apporach
 Step 1: We give some money to tyhe user and ask hikm if he wants to play or quit. 
 
 Step 2: Then create a function for all the fuction for suits,rank and value of each number.
 
 Step 3: Then we create a class called Card where we assign the values to each card with the help of suits and number
 
 Step 4: We calculate the values of score user got with the help of class hand
 
 Step 5: We create a class where we shuffle where we mix the deck to make sure its fair
 
 Step 6: While playing we deal 2 cards to the user and then give him a option of hit or Stand
 
 Step 7: If he says hit then we we draw him a card and then calculate the his score 
 
            Else we draw for oursleves and check who has a highest score the
 Step 8: We ask first the user has enough money to make a bet and if he doesn't we end the and if the user has enough balance we continue.
 
 Step 9: we end the game and ask the user if he wants to play again
 
 Output:
 
 Welcome to BlackJack! Get as close to 21 as you can without going over!
    Dealer hits until she reaches 17. Aces count as 1 or 11.
    Card output goes a letter followed by a number of face notation
 What amount of chips would you like to bet? (Enter whole integer please) 
10

Player Hand is: 
H9
D3
Player hand total is: 12
Dealer Hand is: 
DQ
 with another card hidden upside down
Hit or Stand? Press either h or s: 
h
Player hand is The hand has  H9 D3 D10

Player Hand is: 
H9
D3
D10
Player hand total is: 22
Dealer Hand is: 
SA
DQ
 --- for a total of 21
Chip Total: 90
Busted! Press 'd' to deal the cards again, or press 'q' to quit
