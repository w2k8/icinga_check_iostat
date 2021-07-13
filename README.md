# icinga check_iostat

This plugin output contains all disk devices without the loop device

Sample output:
```
iostat|sda-r/s=14,77
iostat|sda-rkB/s=465,00
iostat|sda-rrqm/s=6,86
iostat|sda-%rrqm=31,72
iostat|sda-r_await=1,34
iostat|sda-rareq-sz=31,49
iostat|sda-w/s=6,13
iostat|sda-wkB/s=285,59
iostat|sda-wrqm/s=27,10
iostat|sda-%wrqm=81,56
iostat|sda-w_await=5,22
iostat|sda-wareq-sz=46,62
iostat|sda-d/s=1,40
iostat|sda-dkB/s=9563,63
iostat|sda-drqm/s=0,00
iostat|sda-%drqm=0,00
iostat|sda-d_await=1,05
iostat|sda-dareq-sz=6826,22
iostat|sda-aqu-sz=0,03
iostat|sda-%util=2,54
```
