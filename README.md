# M.Samitha-
import random

def get_fun_fact():
    # List of fun facts
    fun_facts = [
        "Honey never spoils. Archaeologists have found pots of honey in ancient Egyptian tombs that are over 3,000 years old and still edible.",
        "A day on Venus is longer than a year on Venus. It takes about 243 Earth days for Venus to rotate once, but only 225 Earth days to orbit the Sun.",
        "Bananas are berries, but strawberries are not.",
        "Octopuses have three hearts and blue blood.",
        "The Eiffel Tower can be 15 cm taller during the summer due to thermal expansion.",
        "There are more stars in the universe than grains of sand on all the world’s beaches.",
        "A single strand of spaghetti is called a 'spaghetto'.",
        "Wombat poop is cube-shaped.",
        "The shortest war in history lasted 38 to 45 minutes between Britain and Zanzibar on August 27, 1896.",
        "Hot water freezes faster than cold water. This phenomenon is known as the Mpemba effect."
    ]
    
    # Select a random fact
    random_fact = random.choice(fun_facts)
    return random_fact

# Generate and print a fun fact
print("Fun Fact: ", get_fun_fact())
