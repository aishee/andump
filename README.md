# Andump
Tools dump memory for android.

### Usage
```Bash
python dump.py -pid <PID> -saddr <start_addr> -eaddr <end_addr>
```
* &lt;PID&gt;: process pid
* &lt;start_addr&gt;: start address dump
* &lt;end_addr&gt;: end address dump

<br>
<br>

#### Example<br>
```Bash
python dump.py -pid 1317 -saddr b41ac000 -eaddr b41af000
```
