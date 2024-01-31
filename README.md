# Blackjack

A simple yet entertaining text-based Blackjack game implemented in Python. This game is played against the computer, which acts as the dealer. The objective is to have a hand value closer to 21 than the dealer's without going over. This implementation includes basic features like dealing cards, calculating scores, and comparing outcomes.

Features

Simple Gameplay: Start the game with just a 'y' and play as many rounds as you wish.
Automatic Scoring: The game automatically calculates the scores based on the cards dealt.
Ace Handling: Aces can count as 11 or 1, depending on what is more favorable to the player.
Dealer Logic: The dealer automatically draws cards until reaching a minimum score of 17.
Clear Screen Functionality: Clears the terminal screen for a fresh start each game (works on both Windows and Unix-based systems).
End Game Conditions: Checks for Blackjack (Ace + 10) and compares scores to decide the outcome.

How to Play

Start the Game: Run the script and type 'y' when prompted to start playing.
Deal Cards: Initially, both the player and the dealer will receive two cards, but only one of the dealer's cards will be shown.
Decide to Hit or Stay: If your score is below 21, you can choose to "hit" (get another card) by typing 'y'. If you're satisfied with your score, type 'n' to "stay".
Dealer's Turn: After you decide to stay, the dealer will reveal their second card and may draw additional cards according to the game's rules.
Compare Scores: Once both you and the dealer are done drawing cards, scores are compared to determine the winner.
