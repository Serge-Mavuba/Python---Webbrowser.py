import webbrowser
# allow to open webbrowsers via our code
import time
# will delay the loop with the sleep function
import random
# allow the desired output to run randomly 

# create a while loop that will consistantly run until we kill it via the terminal ("Ctrl + C")
while True: 
    # create a variable & using the random.choice() method, we'll specify a list of website(s)
    # in our sequence that will be selected randomly
    sites = random.choice(['https://www.youtube.com/watch?v=C-u5WLJ9Yk4', 'https://www.linkedin.com/in/geethalakshmi-prasanna-360604205', 
    'http://www.linkedin.com/in/nosa-precious-okundaye'])
    # using the open() method, webbrowser will  open our pre-selected sites
    webbrowser.open(sites)
    # using the sleep()method, the program will loop itself; in this case each selected sites will load itsef
    # according to our 'seconds' variable
    # Note: the randrage() method will tell the program to run the loop at specified intervals ranging from 1-8 seconds
    seconds = random.randrange(1,8)
    time.sleep(seconds)
