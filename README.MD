
# Wheel of Fortune with python

this game is the project of the fourth course in Python 3 Programming Specialization. the Specialization is Offered By University of Michigan via Coursera.

## More details about the game 
There are num_human human players and num_computer computer players.
<br> Every player has some amount of money ($0 at the start of the game).
<br> Every player has a set of prizes (none at the start of the game).
<br> The goal is to guess a phrase within a category. 
<br> For example: Category: Artist & Song.
<br> Phrase: Whitney Houston’s I Will Always Love You.
<br> Players see the category and an obscured version of the phrase where every alphanumeric character in the phrase starts out as hidden (using underscores: _):
<br> Category: Artist & Song
<br> Phrase: _______ ______' _ ____ ______ ____ ___
<br> During their turn, every player spins the wheel to determine a prize amount and:
If the wheel lands on a cash square, players may do one of three actions:

<br> Guess any letter that hasn’t been guessed by typing a letter (a-z)

<br> Vowels (a, e, i, o, u) cost $250 to guess and can’t be guessed if the player doesn’t have enough money. All other letters are “free” to guess

<br> The player can guess any letter that hasn’t been guessed and gets that cash amount for every time that letter appears in the phrase

<br> If there is a prize, the user also gets that prize (in addition to any prizes they already had)

<br> If the letter does appear in the phrase, the user keeps their turn. Otherwise, it’s the next player’s turn

<br> Example: The user lands on $500 and guesses ‘W’

<br> There are three W’s in the phrase, so the player wins $1500.
Guess the complete phrase by typing a phrase (anything over one character that isn’t ‘pass’)

<br> If they are correct, they win the game
If they are incorrect, it is the next player’s turn
Pass their turn by entering 'pass'

<br> If the wheel lands on “lose a turn”, the player loses their turn and the game moves on to the next player

<br> If the wheel lands on “bankrupt”, the player loses their turn and loses their money but they keep all of the prizes they have won so far.

<br> The game continues until the entire phrase is revealed (or one player guesses the complete phrase)

