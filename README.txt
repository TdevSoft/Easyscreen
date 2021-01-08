Run "sh copy_easyscreen_to_home_bin.sh" only once.
This will copy the easyscreen file into ~/bin and display the help for running it from next time from any directory.

help :
easyscreen list                         -> Shows running screens
easyscreen current                      -> Shows current screen name

easyscreen new <name>                   -> Create a screen with title <name> and attach to it
easyscreen reattach <name>              -> Reattach forcefully to a previously created screen session
easyscreen rename <old_name> <new_name> -> Rename a screen session

easyscreen kill <name>                  -> Kill a screen session from inside or outside the session
easyscreen kill_self                    -> Kill current screen session from inside the session

