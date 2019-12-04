# Linux_Shortcuts
This repo has mutiple useful Linux command
**Performance Preferences**
____________________________________________________
cat /sys/devices/system/cpu/cpufreq/policy*/energy_performance_preference <br/>
*Change preference: Change preference after echo* echo performance | sudo tee /sys/devices/system/cpu/cpufreq/policy*/energy_performance_preference

**Killing Process**
_____________________________________________________
*Check running processes:* ps aux | grep -i apt<br/>
Notice the key<br/>
*Kill process using:* sudo kill -9 <process id><br/>
*Kill all instances of a running program:* sudo killall apt apt-get<br/>

