print("Jack: Hello I'm Jack.What is your name?")
name=input("Your name: ")
print("Jack: Hi {}....So what do you want to know about our company?".format(name))
ques=input()

flag = True
while flag:
    
    if all(i in ques.lower() for i in ["company","name"]):
        print("Jack: Our company is ABC(PVT)Ltd.")
        
    elif all(i in ques.lower() for i in ["ceo","name"]):
        print("Jack: Our CEO is Mr. James Parker")
    elif any(i in ques.lower() for i in ["contact","address","telephone","email","mobile","location"]):
        print("Jack: Our company address is 125 Flower road,Colombo 7. Our email address is abc@gmail.com and the hotline is 0112378932.")
    elif any(i in ques.lower() for i in ["service","product","manufacture"]):
        print("Jack: Our company is developing Artificial Intelligence based enterprise software products.")
    else:
        print("Jack: Your question is not clear {}.".format(name))
        
    print("------------------------------------------")    
    print("Jack: Do you want to know anything else? ")
    check=input("Continue (yes/no): ")
    if check.lower()=="yes":
        print("Jack: Okay. what do you want to know? ")
        ques=input()
    else:
        print("Jack: Nice to chat with you. Have a nice day.")
        flag=False
