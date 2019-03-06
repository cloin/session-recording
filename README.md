# Showcase session recording in Cockpit web UI
*Depends on Cockpit installed and configured. See [ansible-cockpit](https://github.com/cloin/ansible-cockpit)*

Installs tlog package and cockpit session recording as well as puts a simple sssd.conf in place to record user sessions to demonstrate within Cockpit web UI.

This implements a simple [`sssd.conf`](https://github.com/cloin/session-recording/blob/master/templates/sssd.conf.j2) to record sessions of local users.

**TODO** currently the user needs to login to Cockpit, go under session recording and save config settings. Need to automate this. 

![Session recording gif](https://github.com/cloin/session-recording/blob/master/cockpit-session-recording.gif?raw=true)
