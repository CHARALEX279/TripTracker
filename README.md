# TripTracker
##this is my first edit!
# telling you what day you will return after vacation or trip is over
days = {"sunday": 0, "monday": 1, "tuesday": 2, "wednesday": 3, "thursday": 4, "friday": 5, "saturday": 6}

startDays = input("What day will you leave?\n").lower()
lengthStay = int(input("How long will you stay\n"))
StartDay = days.get(startDays)

duration = int(StartDay) + lengthStay

backOn = duration % 7

print('You will be back on '+ list(days.keys())[list(days.values()).index(backOn)])
#LMAO THIS WHOLE AS TIME WEDNESDAY WAS SPELLED WORNG I'M DEAD. THAT TOOK ME AN HOUR LOLOLLLLLL
#this took alllllll my time lol

# from the interweb: Basically, it separates the dictionary's values in a list, finds the position of the
#value you have, and gets the key at that position.

#i'm sure you can make a normal list and use the index of the days since the values are set to the zero index, but idk how to return the index into a value...
#hold up
