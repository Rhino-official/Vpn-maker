# Vpn-maker
ubuntu used with python


Start a try block connect with Windscribe using os module

 

os.system("windscribe connect")
 

And, then start an infinite loop and write some lines under it.

 

Choose a random code from codelist using random module.
choiceCode = random.choice(codeList)
Create a random sleep for 15 to 20 min after which the IP of the system gets changed using time and random modules.
sleep(random.randrange(120,300))
Connect with the randomly chosen VPN code.
os.system("windscribe connect "+ choiceCode)
