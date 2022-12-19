# popular-tools-for-hacking
# A simple Python script that offers the 5 most popular tools for each stage in the Cyber Kill Chain.
#  Password is : LetsHack

# Greet the user
print("Dear Hacker!")

# Ask for password
password = input("Please enter your password: ")

# Check password
if password == "LetsHack":
    # Offer stages of the Cyber Kill Chain
    print("Welcome to the Cyber Kill Chain! Please choose a stage:")
    print("1. Reconnaissance")
    print("2. Weaponization")
    print("3. Delivery")
    print("4. Exploitation")
    print("5. Installation")
    print("6. Command and Control")
    print("7. Actions on Objectives")

    # Get user's choice
    choice = input("Enter the number of the stage you want to learn about: ")

    # Offer tools for chosen stage
    if choice == "1":
        print("Here are the five most popular tools for Reconnaissance:")
        print("1. Maltego")
        print("2. Shodan")
        print("3. Whois")
        print("4. nslookup")
        print("5. dig")
    elif choice == "2":
        print("Here are the five most popular tools for Weaponization:")
        print("1. Metasploit")
        print("2. Veil-Evasion")
        print("3. SET")
        print("4. Arduino-Builder")
        print("5. msfpc")
    elif choice == "3":
        print("Here are the five most popular tools for Delivery:")
        print("1. Social Engineering Toolkit (SET)")
        print("2. Spear Phishing Toolkit (SPT)")
        print("3. Phishing Frenzy")
        print("4. Gophish")
        print("5. Hammer Social Engineer Toolkit (SET)")
    elif choice == "4":
        print("Here are the five most popular tools for Exploitation:")
        print("1. Metasploit")
        print("2. Canvas")
        print("3. Core Impact")
        print("4. Immunity Debugger")
        print("5. WinDBG")
    elif choice == "5":
        print("Here are the five most popular tools for Installation:")
        print("1. Cobalt Strike")
        print("2. Meterpreter")
        print("3. Empire")
        print("4. Koadic")
        print("5. PowerShell Empire")
    elif choice == "6":
        print("Here are the five most popular tools for Command and Control:")
        print("1. Cobalt Strike")
        print("2. Meterpreter")
        print("3. Empire")
        print("4. Koadic")
        print("5. PowerShell Empire")
    elif choice == "7":
        print("Here are the five most popular tools for Actions on Objectives:")
        print("1. Cobalt Strike")
        print("2. Meterpreter")
        print("3. Empire")
        print("4. Koadic")
        print("5. PowerShell Empire")
    else:
        print("Invalid choice. Please try again.")
else:
    print("Incorrect password")

print ("Happy Hacking")
