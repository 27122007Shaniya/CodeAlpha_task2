# CodeAlpha_task2
Task2- Making a CHATBOT
print("🤖 Chatbot Started (Type 'exit' to stop)")

while True:
    
    user = input("You: ").lower()
    
    if user == "hi" or user == "hello":
        print("Bot: Hello! How can I help you?")
        
    elif user == "price":
        print("Bot: Our product price starts from ₹999.")
        
    elif user == "timing":
        print("Bot: We are open from 9 AM to 6 PM.")
        
    elif user == "location":
        print("Bot: We are located in Chennai.")
        
    elif user == "bye":
        print("Bot: Thank you! Visit again.")
        
    elif user == "exit":
        print("Bot: Chatbot Stopped 👋")
        break
        
    else:
        print("Bot: Sorry, I did not understand.")
