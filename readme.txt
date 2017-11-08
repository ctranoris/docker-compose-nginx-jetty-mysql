Check a related blog post at http://www.softwareagility.gr/index.php?q=node/32

A simple example for deploying nginx-jetty-mysql with docker composer


careful to change in jetty folder the home owner to owned by jetty:jetty (uid 999, gid 999):

sudo chown -R 999:999 home/
