# Bridge-Block
Slightly modified script from the posted "Air Defense" script posted awhile back

Please NOTE: I'm NOT the original author of this script, just modified it for 
our network and management preferences. 

We found when testing the original "Air Defense" script that Wi-Fi was always turned 'ON' 
if no Wired connectivity was present and staff didn't like that so we pulled 
that portion out.  All worked well until the USB-C only Macs came along and we
found that Wi-Fi was always being disabled.  A check on all the adapters found
showed that the -Thunderbolt Bridge- was always listed as 'Active' and thus
Wi-Fi was disabled by the script.  The easiest modification was to simply 
avoid adding the Thunderbolt Bridge into the list/array of Wired adapters.

-CTM
