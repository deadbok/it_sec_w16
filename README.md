# ITDEV Week 16 #

# Monitoring #

 * Keep track of s system.
 * Know what is going on.
 * Everything is running.

## Software ##

 * Nagios (status right now).
 * Zabbix (time series).
 * Observium.
 * Cacti

**Humans are good at looking at graphs**

If stuff is looking bad in the monitoring software and go on to the log-files.


# Assignment #

Get an SRX router to send logs to a Debian system.

Tasks:

 * Setup a SRX VM
 * Setup a Debian VM
 * Configure the network on the VM's
 * Configure the SRX to send the log-files. (root password: a123456)
 * Configure Debian to receive the logs. (root password: test)

# Syslog protocol #

Either UDP or TCP.

Syslog can use TLS.

# Assignment II #

I have created an (no variables, very simple, but its gonna be yuge) ansible
playbook to install an ELKS stack on the Debian VM.
I have turned the Elasticsearch and Logstash memory usage down, to save some
memory in the VM.
