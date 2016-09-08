# Repository of linux commands I've used #
I forget things pretty easily, especially people's names and syntax. As such, I made this list 
so that I can have a quick place to reference when I've forgotten something.

## File System ##
`ls -a` shows hidden files
`find / -type d -name "*boolbd*" -print` find a folder containing a string, starting at root
`du -sh` get file size in directory, summarize and human-readable. Add `-c` for a grand total
`du -hs * | sort -h` get file size in directory, sorted by file size

## System Status ##
`tail -f /var/log/kern.log` Check kernel log to figure out why a process was killed