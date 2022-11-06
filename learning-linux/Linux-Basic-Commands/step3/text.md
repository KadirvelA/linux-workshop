Display and manage the top processes

```plain
top
```{{exec}}
Interactive process viewer (top alternative)

```plain
htop
```{{exec}}

Display virtual memory statistics

```plain
vmstat 1
```{{exec}}

Display the last 100 syslog messages  (Use /var/log/messages for RHEL/Centos based systems.)

```plain
tail -100 /var/log/syslog
```{{exec}}

List all open files on the system

```plain
lsof
```{{exec}}

List files opened by user

```plain
lsof /var
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

