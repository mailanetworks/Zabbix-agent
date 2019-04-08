# Zabbix-agent
Zabbix Agent for vyos

Agent configurable using the same command line from System

After installation:

set system zabbix-agent ...

Possible completions:
<- buffer-send  Do not keep data longer than N seconds in buffer.
-   buffer-size  Maximum number of values in a memory buffer.
-   debug-level  debug level 0:no debug, 1:critical, 2:error, 3:warning 4:debug
-   enable-remote-commands  Enable remote commands.
-   host-metadata  Optional parameter that defines an item used for getting host metadata.
-   host-metadata-item   Optional parameter that defines an item used for getting host metadata.
-   hostname     Hostname
-   hostname-item   Item used for generating Hostname.
-   listen-ip    Listen IP addresses.
-   listen-port  Listen port:
-   log-file-size    Maximum size of log file in MB.
-   log-remote-commands    Enable logging of executed shell commands as warnings.
-   max-lines-per-second   Maximum number of new lines the agent will send per second.
-   refresh-active-checks  How often list of active checks is refreshed, in seconds.
-  server       IP addresses (or hostnames) of Zabbix servers.
-   server-active   IP:port (or hostname:port) pair of active check.
-  start-agents Number of pre-forked instances of zabbix_agentd.
-   timeout      Timeout seconds on processing./>
