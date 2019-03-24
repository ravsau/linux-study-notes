## Runlevel
A runlevel is one of the modes that a Unix -based operating system will run in. Each runlevel has a certain number of services stopped or started, giving the user control over the behavior of the machine. There are seven runlevels ,0-6.

After the Linux kernel has booted, the /sbin/init program reads the **/etc/inittab** file to determine the behavior for each runlevel. 

**Unless the user specifies another value as a kernel boot parameter, the system will attempt to enter (start) the default runlevel.**



| ID |	Name |	Description         |
 ----| ------| ---------------------|
|0	 |Halt	 |Shuts down the system.|
|1	 |Single-user mode |	Mode for administrative tasks.|
|2	 |	Multi-user mode |	Does not configure network interfaces and does not export networks services.|
|3	 |	Multi-user mode with networking |	Starts the system normally.|
|4	 |	|Not used/user-definable	For special purposes.|
|5	 |	Start the system normally with appropriate display manager (with GUI) |	Same as runlevel 3 + display manager.|
|6	 |	Reboot |	Reboots the system.|



