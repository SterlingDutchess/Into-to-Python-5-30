def greeting():

    friends = ["Mark, "Emily", "John"]
    time = input("What time is it ?")
    time = int(time)
    
    for name in friends:
        if time < 7:
            print("Hello", name, "party starts at 7pm")
        elif time == 7:
            print("Hello", name, "you are right on time")
        else:
            print("Hello", name, "you are late")
        
        
greeting()
