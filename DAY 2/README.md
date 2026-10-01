 # HARDWARE INFORMATION
 
cat /proc/cpuinfo # Display CPU information

cat /proc/meminfo # Display memory information

free -h # Display free and used memory ( -hfor human readable,

-mfor MB, -gfor GB.)

lspci -tv # Display PCI devices

lsusb -tv # Display USB devices

dmidecode # Display DMI/SMBIOS (hardware info) from theBIOS

hdparm -i /dev/sda # Show info about disk sda

hdparm -tT /dev/sda # Perform a read speed test on disk sda
