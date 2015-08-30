brewpi-script
=============

This is the repository for the BrewPi Python script. The python script logs the data, monitors the temperature profile and communicates with the BrewPi slave and the web server

Modified by Lukas:

Installing the Influxdb:

On Dev System:
# for 32-bit systems
wget http://ftp.de.debian.org/debian/pool/main/i/influxdb/influxdb_0.9.2.1+dfsg1-1_i386.deb
sudo dpkg -i influxdb_latest_i386.deb

On Raspberry: http://demos.pihomeserver.fr/influxdb_0.8.6_armhf.deb

sudo install python-dateutil python-tz
Then, do:
wget http://ftp.de.debian.org/debian/pool/main/i/influxdb-python/python-influxdb_2.8.0-1_all.deb
sudo dpkg -i python-influxdb_2.8.0-1_all.deb

With this, InfluxDB and it's Python modules are installed
