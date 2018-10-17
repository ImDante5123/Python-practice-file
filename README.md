# Python-practice-file

import random
repeat = True
while repeat:
    print("You rolled",random.randint(1,6))
    print("Would you like to roll again? Y/N")
    repeat = "Y","y" in input()
