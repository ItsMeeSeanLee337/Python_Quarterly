#Sean Lee 1/29/19
#Quarter 2 Final:
#Python text adventure game where the user must make choices to help their family survive
#The more family members that survive, the more points the user gets
#Enhancements: Branching paths, multiple endings, replayability.

print ("Welcome to the Python trail!")
print ("\n")
print ("Our story begins in the year 1848.")
print ("You and your 8 person family are struggling to survive in the Old West.")
print ("You have decided to journey to the new state called california.")
print ("Before we begin pick your career and name.")
career = input("Are you a Hunter, Farmer, or a Soldier: ")
#careers: hunter farmer soldier
name = input("What is your name: ")
family = 8
print (name, "must get most of his family members safely to California.")
print ("The more people that survive the journey, the more points you get.")
print (name, "and his family first start in the city of New York")
print ("To get to the Great Midwest", name, "and his family must first pass the border of New York")
print ("Would you like to fight the border patrol, pay for a train ticket, or ride with other migrants?")
choice1 = input("Please type: Fight, Pay, or Ride: ")
#Choice1: fight the border patrol, pay the toll, ride with others
#Choice2: Buy food, steal food, or hunt for food
#Choice3: Confront the bandits, bargain with them, or sneak around.

if choice1=="Fight":
    if career == "Hunter":
        print ("Your skills as a hunter help you fight the border patrol. Unfortunately one of your family members die during the fight. You must continue the journey to California without them.")
        family1 = family - 1
    elif career=="Farmer":
        print ("Your inexperience in combat as a farmer causes you to lose two of your family members. You hold a funeral for the fallen but are forced to continue on.")
        family1 = family - 2
    else:
        print ("Your experience with weapons during your time in the army greatly helps you in your battle with the border patrol. None of your family members were hurt during the battle.")
        family1 = family - 0
elif choice1 == "Pay":
    if career == "Hunter":
        print ("As a hunter you are able to hunt for pelts in the wild. By selling those pelts you are able to make enough money to pay of the border patrol.")
        family1 = family - 0
    elif career == "Farmer":
        print ("Your skills as a farmer allow you to grow multiple cash crops. The money you make from selling these crops helps you to pay off the border patrol.")
        family1 = family - 0
    else:
        print ("You are able to sell some of your old military weapons during your life as a soldier. By selling the guns that you once owned, you are able to pay off the border patrol and continue on your way.")
        family1 = family - 0
else:
    print ("The other journeyers are more than happy to allow you to join them on their voyage to California. They believe that having a",  career, "amongst them will help them on their pilgrimage.")
    family1 = family - 0
print ("You and your family are able to make it to the Great Midwest by winter. However, most of your food supplies have run out. You have to choose to buy food, steal food, or hunt for food.")
choice2 = input("Please type: Buy, Steal, or Hunt: ")
if choice2 == "Buy":
    if career == "Hunter":
        print ("The long winter has a side-effect of putting many animals in hibernation. Even though you are able to sell enough pelts, the cold winter kills two of your family members.")
        family2 = family1 - 2
    elif career == "Farmer":
        print ("The long winter forces you to stockpile all the crops you grew during the summer. Even though you had a good harvest in the previous year, your stockpile is not enough to last the entire winter. The lack of food kills one of your family members in the end.")
        family2 = family1 -1
    else:
        print ("Had you not been in the military, your family would have starved during the winter months. Your former friends are able to help provide you and your family with extra rations, keeping everyone in your family alive.")
        family2 = family1 - 0
elif choice2 == "Steal":
    if career == "Hunter":
        print ("Your experience with weapons allows you to easily steal food from the grain stores. You and your family are able to steal enough food for the winter until spring arrives. In February, you and your family continue on the journey.")
        family2 = family1 = 0
    elif career == "Farmer":
        print ("You and your family fail in stealing the food for the winter. As a result, two of your family members are killed by the town sheriffs. In February, you and your family continue on the journey.")
        family2 = family1 - 2
    else:
        print ("Your experience in the military allows you to easily steal the food from the grain store. In February, you and your family continue on the journey.")
        family2 = family1 - 0
else:
    if career == "Hunter":
        print ("Your skills as a hunter allow you to easily find food for your family. In February, you and your family continue on the journey.")
        family2 = family1 - 0
    elif career == "Farmer":
        print ("Your skills as a farmer do little to help you hunt. As a result, two of your families members are killed. In February, you and your family continue on the journey.")
        family2 = family1 - 2
    else:
        print ("Your skills as a soldier do little to help find food. As a result, two of your families members are killed. In February, you and your family continue on the journey.")
        family2 = family1 - 2
print ("You and your family are on the final road to California! You see a group of bandits preparing to make an attack. You talk with your family and decide that you can either confront the bandits, bargain with them, or sneak around the road.")
choice3 = input("Please type: Confront, Bargain, Sneak: ")
if choice3 == "Confront":
    if career == "Hunter":
        print ("As a hunter, you use guerilla warfare to overpower the bandits. One of your family members is fatally wounded during the battle. Fortunately, you are able to finally make it to California with your remaining family members")
        family3 = family2 - 1
    elif career == "Farmer":
        print ("Without any experience in combat, three of your family members die. You lick your wounds, and continue on your way to California.")
        family3 = family2 - 3
    else:
        print ("Your military experience allows you to easily fight off the bandits. You receive no casualties and finally make it to California.")
        family3 = family2 - 0
elif choice3 == "Bargain":
    if career == "Hunter":
        print ("Your inexperience in bargaining with others forces you to flee the scene. When running away from the bandits, two of your family members are shot and killed. The rest of your family continue on to California.")
        family3 = family2 - 2
    elif career == "Farmer":
        print ("Having bargained with many during your time as a farmer, you are able to easily get by the Bandits with no trouble. You pass by the bandits with no trouble and continue to California.")
        family3 = family2 - 0
    else:
        print ("The bandits are easily intimidated by your status as a soldier. You are able to easily pass into California by using intimidation and manipulation tactics.")
        family3 = family2 - 0
else:
    print ("You sneak past the bandits at night and easily make it to California.")
    family3 = family2 - 0
print ("After many years you are able to finally make it to California!")
if family3 == 8:
    print ("All family members made it to California.", name, "and your family are finally able to strike it rich during the gold rush and live for the rest of your lives in luxury")
elif family3 <= 7 and family3 >= 4:
    print (name, "and your family struggle in the first months but are eventually able to live a fairly decent life in the new state of California.")
else:
    print (name, "and the remnants of his family are unable to do well in California. Slowly, each family member dies until eventually", name, "dies as well")
points = family3 * 100
print ("You got", points, "out of 800 points!")
