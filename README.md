Slot Machine Game:
This is a simple Python script that simulates a slot machine game. Players can deposit money, place bets, and spin the reels to win prizes based on the combinations of symbols.

Features:
Deposit: Players can deposit money into their virtual balance.
Place Bets: Players can choose the number of lines to bet on and the amount to bet per line.
Spin Reels: Players can spin the reels and see the outcome.
Check Winnings: The script calculates and displays the winnings based on the combinations of symbols.

Usage:
Run the Script: Execute the Python script to start the game.

python slot_machine.py

Deposit Money: Enter the amount you want to deposit into your virtual balance.

Place Bets: Choose the number of lines to bet on and the amount to bet per line.

Spin Reels: Press Enter to spin the reels and see the outcome.

Quit: Press 'q' to quit the game at any time.

Example:
def main():
    balance = deposit()
    while True:
        print(f"Current balance is ${balance}")
        answer = input("Press enter to play (q to quit)")
        if answer == "q":
            break
        balance += spin(balance)

    print(f"You left with ${balance}")

main()

Contributing:
Contributions are welcome! If you have any suggestions or improvements for this project, feel free to fork the repository and submit a pull request.
