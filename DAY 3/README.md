# PERFORMANCE MONITORING AND STATISTICS

top # Display and manage the top processes

mpstat 1 # Display processor related statistics

vmstat 1 # Display virtual memory statistics

iostat 1 # Display I/O statistics

tcpdump -i eth0 # Capture and display all packets on interface eth0

tcpdump -i eth0 'port 80' # Monitor all traffic on port 80 ( HTTP )

lsof # List all open files on the system

lsof -u user # List files opened by user

free -h # Display free and used memory ( -h for human readable, -m

for MB, -g for GB.)

watch df -h # Execute "df -h", showing periodic updates
