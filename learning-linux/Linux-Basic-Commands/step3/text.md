Display and manage the top processes

```plain
top
```{{exec}}
Interactive process viewer (top alternative)

```plain
htop
```{{exec}}

Display processor related statistics

```plain
mpstat 1
```{{exec}}

Display virtual memory statistics

```plain
vmstat 1
```{{exec}}

Display I/O statistics

```plain
iostat 1
```{{exec}}

Display the last 100 syslog messages  (Use /var/log/syslog for Debian based systems.)

```plain
tail -100 /var/log/messages
```{{exec}}

Capture and display all packets on interface eth0

```plain
tcpdump -i eth0
```{{exec}}

Monitor all traffic on port 80 ( HTTP )

```plain
tcpdump -i eth0 'port 80'
```{{exec}}

List all open files on the system

```plain
lsof
```{{exec}}

List files opened by user

```plain
lsof -u user
```{{exec}}

Display free and used memory ( -h for human readable, -m for MB, -g for GB.)

```plain
free -h
```{{exec}}

Execute "df -h", showing periodic updates

```plain
watch df -h
```{{exec}}


<br>

