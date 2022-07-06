# Discord-CPU-Ram-flood
original exploit by Pybro, found in 2018

Ram flood and CPU overheat through Discord’s latest version
Required : 
-Windows 8, 10, 11
-Windows defender (or any other antiviruses but Win defender is tested)
-Discord’s application (not discord web)
At first, we have to get any php or other programming languages’ codes that windows defender’s algorithm knows
that as a threat or a virus, Like webshells

On this one we used 15 Opensource webshells that is known by the windows defender

**Any file and media sent through discord gets saved as a cache file, we will send all of our webshells to 
our victim twice and all of them gets saved in their discord’s cache, windows defender or obviously any 
anti-virus scans the recent modified files on your pc, it will 100% detect the webshells on victim’s PC and 
reactions to it, but somehow it can’t delete or quarantine the file so it keeps trying to detect it again and 
again and trying to solve the problem but it can’t, so the CPU usage and sometimes the RAM usage goes 
higher and higher untill the system gets slow or on low-end computers it may cause crashing

**this is Temporary and the cache file finally gets removed but on a medium computer, it takes for 
about 2 minutes for the CPU to go back normal**

If the victim is blocking any js file on their system this may not work



Auth : pybro & B.menace & Alipunisher
