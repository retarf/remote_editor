''' Remote editor is a script witch allow user to edit file on local 
machine and synchronize this file with file on remote machine. It is use 
to program script on server from local machine.

ATTENTION:
    Remote editor open connection on server throu netcat. It is availble 
to all host in local network, so there is a threat that someone else could 
connect to socket.

DEPEND ON:
    pyinotify
    netcat

'''
