# nso-kimt22-a2

this is the Assignment 2 for NSO (Network Security and Operations)

There are the IP's and the fixed IP's of the servers i used 

bastionNSO-- 188.95.227.77 -- 10.0.1.25
HAproxy-- 103.57.72.144  -- 10.0.1.24
devA-- 188.95.231.197  -- 10.0.1.17
devB-- 188.95.231.137  -- 10.0.1.13
devC-- 103.57.72.115  -- 10.0.1.15

where bastionNSO is acting as a jump server between local_host and webservers
and HAproxy is used as a load balancer for webservers 

the files are as follows:
config -- ssh configuration file
haproxy.cfg.j2 -- haproxy configuration file
site.yaml -- ansible playbook
hosts -- ansible inventory file
devApp.py -- Flask app

the ansible playbook can update the servers, install the required libraries,modules or extensions and then deploy the flask app.



