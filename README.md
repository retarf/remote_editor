''' 
With Remote Editor you could edite remoute scripts using your favorite 
editor on your local machine.

Remote Editor is a script witch allow user to edit file on local 
machine and synchronize this file with file on remote machine. It is use 
to edit scripts on server from local machine.

ATTENTION:
    Remote Editor open connection on server throu netcat. It is availble 
to all host in local network, so there is a threat that someone else could 
connect to socket.

DEPEND ON:
    pyinotify
    netcat

'''
