# Monero Ban List

A banlist for Monero nodes.

These nodes were found displaying behaviour that the normal Monero nodes would not do.

The total count of IP addresses hosting nodes showing this behaviour is currently over 1900.

False positives are not possible, some of these IP ranges are the same as LinkingLions: https://b10c.me/observations/06-linkinglion/  
The IPs from LinkingLion were not copied, they were found displaying this weird behaviour.

### Usage

To use download `ban_list.txt` and start `monerod` with `--ban-list /path/to/ban_list.txt` 
or add `ban-list=/path/to/ban_list.txt` to your `bitmonero.conf` file.
