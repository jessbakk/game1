# Blackjack 

## Part 1 - Pseudocode



#### Variables

The current game can only be played between the Dealer and Player One.

The game is played with **ONE DECK** of 52 cards. 

Empty table to start before cards dealt. 

Player 1 has a pre-determined BANK when the game initializes for the FIRST TIME. Bank = $100

#### Cached Items 

##### currentBankBalance
    
    * store bank plus or minus their current bank balance 

##### cardsInUse
    
    * store current cards in use in an array

##### Functions 
initialize at index open

    * clean table 
    * player bet starts at $100

##### renderTable 

    * clears board after game 
    * clears bets - keeps ongoing balance of players current bank amount 
    * shuffle the deck
    * player places new bet and deduct from Bank

##### placeBet 

    * player will have to input bet amount 
        * if bet amount is larger than bank amount return alert to player 
        * or else deduct amount from their bank and push to holding area 
        * set new balance in their bank 

##### dealCard

    * player receives first card FACE UP -timeout to show cards one after the other 
    * dealer receives second card FACE DOWN 
    * player receives third card FACE UP 
    * dealer received fourth card FACE UP 
        

##### evaluateCards 

    * after card deal, if dealer has 2 cards
    * Evaluate dealers face down card
            * if face down card and face up card are equal to value of 21 
            * show both cards to view 
            * clear the table 
            * if cards of player 1
                * if player 1 cards are greater than 21
                    * alert player1 that they have busted 
                * else if player1 cards are less than or equal to 21 and p1 cards greater than dealers cards
                    * add double their bet to their bank
                * else if player1 cards equal dealers cards
                    * its a draw 
            * clean the table 

##### shuffleDeck

    * deck has 52 cards
    * all cards will hold their numeric value and face cards will be assigned 10, Ace is 1 or 11
    * use math random to randomize cards 





