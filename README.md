# splunk-walkthrough
Splunk Walkthrough

Téléchargement de Splunk
http://www.splunk.com/en_us/download/splunk-enterprise.html

Il propose des packages pour un vaste choix d'OS allant de linux à windows en passant par AIX et FreeBSD. Coté Linux, debian, rpm et un simple tgz sont au programme. 

Cela sera un debian pour ma part. 

Il demande la création d'un compte en obligeant à 
"Yes, I want to receive educational materials, product announcements and community event info via email from Splunk Inc. and its Subsidiaries. Read our email policy."

Soit...

sudo dpkg -i splunk-6.2.1-245427-linux-2.6-intel.deb

/opt/splunk/bin/splunk start
