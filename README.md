name = (input("Tim/Jim/Ryan/Ruby/Kendi: "))
if name == ("Tim", "Jim", "Ryan", "Kendi"): 
    print("continue")
else:
    print("Please pick one of our doctors")
# Start of conversation between doctor and the patient
print("Hello my name is", name)
name_2 = input("What is your name: ")
print()
print("Hello", name_2)
print("How may i help you today. ")
print()
if name == "Tim":
    print("My name is Tim and i am your full service today")
elif name == "Jim":
    print("My name id Jim and i am at your full service today")    
elif name == "Ryan":
    print("My name is Ryan and i am at your full service today")
elif name == "Ruby":
    print("My name is Ruby and i am at your full service today")
elif name == "Kendi":
    print("My name is Kendi and i am at your full service today")
# Start of convo
print("So how are you doing today", name_2, "?")
state = input("Good/Bad: ")
if state == "Good":
    print("Ok then what has brought you here today")
elif "bad":
    print("Where don't we feel well")
print()    
explanation = input ()
if "chest" in explanation:
    print("Is there sharp pains which are short or prolonged pain:")
elif "head" in explanation:
    print("Is there a throbing pain")
elif "body" in explanation:
    print("where in the body specifically")
elif "leg" in explanation:
    print("Is it throbbing or a sharp pain")
else:
    print("ok")
print()
explanation_2 = input()
if "cold" in explanation_2:
    print("That is mild and syrup will do")
elif "something mild" in explanation_2:
    print("Okay we will sort a prescription")
else: 
    print("if nothing is bothering you we will release you")
# end
print()
print("It seems you are all good to go.We will schedule a follow up session")
goodbye = input()
if "Ok" or "ok" or "Thank you" or "Goodbye" or "Bye" in goodbye:
    print("Ok bye and thank you for trusting me to be your doctor.See you soon.")
