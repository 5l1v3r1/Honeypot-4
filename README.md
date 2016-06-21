#Documentation
#Download Pentbox:

  Simply type in the following command in your terminal to download pentbox-1.8.

            root@MrMugiwara:~# git clone git@github.com:MrMugiwara/pentbox-1.8.git

#Run pentbox ruby script 
Change directory into pentbox folder

            root@MrMugiwara:~# cd pentbox-1.8/

            root@MrMugiwara:~/pentbox-1.8# ls

  Run pentbox using the following command

            root@MrMugiwara:~# ./pentbox.rb

#Setup a honeypot 
Use option 2 (Network Tools) and then option 3 (Honeypot).
<p>Finally for first test, choose option 1 (Fast Auto Configuration)
This opens up a honeypot in port 80.
Simply open browser and browse to http://10.0.2.15 (where 10.0.2.15 is your IP Address.
You should see an Access denied error.
and in the terminal you should see “HONEYPOT ACTIVATED ON PORT 80” followed by “INTRUSION ATTEMPT DETECTED”.</p>
![alt tag](https://github.com/MrMugiwara/pentbox-1.8/blob/master/other/honeypot.png)
</p>Now, if you do the same steps but this time select Option 2 (Manual Configuration), you should see more extra options </p>
![alt tag](https://github.com/MrMugiwara/pentbox-1.8/blob/master/other/honeyset.png)
<p>Do the same steps but select port 22 this time (SSH Port).<br> Then do a port forwarding in your home router to forward port external port 22 to this machines’ port 22. Alternatively, set it up in a VPS in your cloud server.<br> You’d be amazed how many bots out there scanning port SSH continuously.<br>
You know what you do then? You try to hack them back for MrMugiwara!</p>

Source: Pentbox
