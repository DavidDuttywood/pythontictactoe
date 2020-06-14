# board
board = [
         "-", "-", "-",
         "-", "-", "-",
         "-", "-", "-",
        ]

current_player = "X"


def swap_player():
    global current_player
    if current_player == "X":
        current_player = "O"
    else:
        current_player = "X"


def display_board():
    print(board[0] + " | " + board[1] + " | " + board[2])
    print(board[3] + " | " + board[4] + " | " + board[5])
    print(board[6] + " | " + board[7] + " | " + board[8])


def play_game():
    display_board()
    handle_turn()
    swap_player()
    play_game()

def handle_turn():
    position = int(input("Choose a position from 1 to 9: "))
    board[position - 1] = current_player


play_game()

