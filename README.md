# SynologyWOL

Script based on synonet command.

1. Require Enviroment:
- Use root permission
    (Synonet which is used program is need to root permission)
- Synology NAS and PC is have to same network
    (It is access by mac address)

2. Support
- Synology DSM Scheduler
    (Because I use setting at work off time.)

3. How to?
    1) Download and Open wol.sh file.
    2) Change text [Wake PC MAC address] to Wake on lan PC's MAC address.
    3) Upload to Synology NAS folder
    
Use Terminal: 
1. login account.
2. write command : sudo -i 
3. write root password 
4. write bash command : bash /'volumeNumber/yourfilepath'/wol.sh
5. End!

Use schedule: 
1. Select Control panel. 
2. Select Work Scheduler
3. Create custom scheduler
4. User select 'root' -> Important!!
5. Select 'Work setting' tab
6. write bash command : bash /'volumeNumber/yourfilepath'/wol.sh
7. Select submit button
8. End!
  
