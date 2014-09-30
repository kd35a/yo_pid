Yo Process Is Done (yo_pid)
======
##Send yourself a YO when your work is done##

> Inspired by Yoman from Andrew Duberstein: http://www.andrewduberstein.com/item/2014/11/28/yoman/

####Yo API Setup###
>1. Create an account with the Yo App
2. Obtain an API key from http://dev.justyo.co/
3. Replace {api key} in the code with your own API key

###Usage###
Run a command and Yo when it is done

`./yo_pid.sh -c '{COMMAND}' -u {YO_NAME}`

Monitor an already running PID and Yo when CPU time, memory percent, and processor being used stop changing. This is useful if you want to know when a process stops doing work, even if the PID is still active

`./yo_pid.sh -p {PID} -u {YO_NAME}`


http://dataneel.com
