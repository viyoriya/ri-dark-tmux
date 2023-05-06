###### tmux config with fontawesome


    1. Make a backup of old tmux config
    2. install fontawesome font 
    3. install ufw (optional)
    4. Provide sudo execute permission (if you install ufw)


###### for ufw add this in ` /etc/sudoers ` 
    
###### <font size="1">  `     :Cmnd_Alias UFWSTATUS = /usr/sbin/ufw status ` </font>

###### add the UFWSTATUS variable in end of usr permission  ex:

###### <font size="1">  `     : <login_user_name> ALL= NOPASSWD: /usr/bin/mount, /usr/bin/umount, /usr/bin/tee, UFWSTATUS ` </font>

###### terminal screenshot

![terminal](https://github.com/viyoriya/tmux/blob/main/screenshot/2023-terminal.png "terminal screenshot")

###### tty screenshot

![tty](https://github.com/viyoriya/tmux/blob/main/screenshot/2023-tty.png "tty screenshot")
  
