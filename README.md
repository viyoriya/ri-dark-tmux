### tmux config with fontawesome (Ri-Dark theme)


    1. Make a backup of old tmux config
    2. install fontawesome font 
    3. add alias in .bashrc/.zshrc for tty conf
    4. install ufw (optional) and provide sudo execute permission (if you install ufw)

###### In .bashrc/.zshrc add this below line for accessing tmux in tty 

######  `  [[ $TERM = 'linux' ]] && alias tmux='tmux -u -f ~/.config/tmux/tmux.tty.conf' `  

###### for ufw add this in ` /etc/sudoers ` 
    
######  `     Cmnd_Alias UFWSTATUS = /usr/sbin/ufw status   `

###### add the UFWSTATUS variable in end of usr permission  ex:

######  `     <login_user_name> ALL= NOPASSWD: /usr/bin/mount, /usr/bin/umount, /usr/bin/tee, UFWSTATUS    ` 


###### terminal screenshot

![terminal](https://github.com/viyoriya/tmux/blob/main/screenshot/2023-terminal.png "terminal screenshot")

###### tty screenshot

![tty](https://github.com/viyoriya/tmux/blob/main/screenshot/2023-tty.png "tty screenshot")
  
