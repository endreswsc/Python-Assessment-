
import random

def chatbot():
    print("ChatBot: Hi! I can chat with you or play a game. Type 'play' to start Rock-Paper-Scissors, or 'bye' to exit.")
    
    while True:
        user_input = input("You: ").lower()
        
        if user_input in ['bye', 'exit', 'quit']:
            print("ChatBot: Goodbye! 👋")
            break
        elif "play" in user_input or "game" in user_input:
            play_game()
        elif "hello" in user_input or "hi" in user_input:
            print("ChatBot: Hello there! Want to play Rock-Paper-Scissors?")
        elif "how are you" in user_input:
            print("ChatBot: I'm just a bunch of code, but I'm functioning well!")
        elif "your name" in user_input:
            print("ChatBot: I'm ChatBot, your friendly Python program.")
        elif "help" in user_input:
            print("ChatBot: You can say hello, ask my name, ask how I am, or type 'play' to start a game.")
        else:
            print("ChatBot: Hmm, I don't understand that yet.")

def play_game():
    print("ChatBot: Let's play Rock-Paper-Scissors! Type your choice (rock, paper, or scissors). Type 'stop' to quit the game.")
    
    choices = ["rock", "paper", "scissors"]
    
    while True:
        user_choice = input("You: ").lower()
        
        if user_choice == "stop":
            print("ChatBot: That was fun! Let me know if you want to play again.")
            break
        elif user_choice not in choices:
            print("ChatBot: Invalid choice. Please type rock, paper, or scissors.")
            continue
        
        bot_choice = random.choice(choices)
        print(f"ChatBot: I chose {bot_choice}.")

        if user_choice == bot_choice:
            print("ChatBot: It's a tie!")
        elif (user_choice == "rock" and bot_choice == "scissors") or \
             (user_choice == "scissors" and bot_choice == "paper") or \
             (user_choice == "paper" and bot_choice == "rock"):
            print("ChatBot: You win! 🎉")
        else:
            print("ChatBot: I win! 😎")

if __name__ == "__main__":
    chatbot()
