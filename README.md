#Basic Chatbot 
def chatbot():
    print("ChatBot: Hello! Type 'bye' to exit.")

    while True:
        user = input("You: ")

        if user == "hello" or user == "hi":
            print("ChatBot: Hi! Nice to meet you.")

        elif user == "how are you":
            print("ChatBot: I'm fine, thanks! How about you?")

        elif user == "what is your name":
            print("ChatBot: My name is Python Bot.")

        elif user == "who made you":
            print("ChatBot: I was created using Python.")

        elif user == "thank you" or user == "thanks":
            print("ChatBot: You're welcome!")

        elif user == "bye":
            print("ChatBot: Goodbye! Have a great day.")
            break

        else:
            print("ChatBot: Sorry, I don't understand that.")

# Run the chatbot
chatbot()
