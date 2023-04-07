A python based keylogger that runs in the terminal and logs individual keypresses as well as timestaps of when they're pressed, in CSV format. 

Orignally coded by me for a legitimate research project that attempted to identify keypresses based on vibrations, now it lives on as a testament to just how poor security is around keylogging, particularly on windows machines. 

Obviously this should only be used ethically and only on machines that **you own**. The program is deliberately designed to be blatantly obvious when it's running, so it can only run in an open command prompt.

## To use the keylogger
open a terminal, go to the project folder and run `python3 keylogger.py` on windows or `sudo python3 keylogger.py` on linux. Logs are stored in in the `keylogs` directory in the project (current working) directory. `ctrl-c` to exit.