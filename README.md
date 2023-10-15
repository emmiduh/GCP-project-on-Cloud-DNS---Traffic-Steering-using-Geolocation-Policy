# GCP-project-on-Cloud-DNS---Traffic-Steering-using-Geolocation-Policy

## In this project, I did the following:
* Enabled the compute and the Cloud DNS APIs from the CLI and verify that the APIs are enabled.
* Created fierwall rules to allow ssh and icmp into the clients VMs and HTTP on the webservers
* Launched 3 client VMs in separate regions
* Launch server VMs, one in each region except asia-south1, with a startup script to configure and setup apache2 web server.
* Set up environment viriables to hold the IP addresses of the web servers and create a private zone, for example.com domain
* Create a Geolocation routing policy using gcloud commands
* Tested the configuration and observed it worked as expected
