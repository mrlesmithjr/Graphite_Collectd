Graphite_Collectd
=================

Graphite
--------
You can also install Graphite Carbon on the same server as logstash/kibana3 or on a totally separate server.

Install instructions.
chmod +x ./Graphite_Collectd/install_graphite_ubuntu.sh
sudo ./Graphite_Collectd/install_graphite_ubuntu.sh

Graphite will be running on tcp/8080 after the installer completes.
use your browser of choice and connect to http://IP|hostname:8080

Collectd
--------
You can use the collectd installer to install on any server that you want to send metrics to your Graphite Carbon instance. The installer will prompt for your Graphite Carbon server (use IP or hostname). It is also assumed that Graphite Carbon is listening on the default of tcp/2003.

Install instructions.
chmod +x ./Graphite_Collectd/install_collectd_ubuntu.sh
sudo ./Graphite_Collectd/install_collectd_ubuntu.sh

Visit Me
--------
http://everythingshouldbevirtual.com
@mrlesmithjr
