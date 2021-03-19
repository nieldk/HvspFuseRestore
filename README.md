# HvspFuseRestore

    Restore the fuse bits of a ATtiny13 or ATtiny24/44/84 or ATtiny25/45/85 to factory default 
    using High-voltage Serial Programming (HVSP). 
    This will reset the RSTDISBL fuse bit and change back the RESET Pin
    from a I/O line to a Reset input. Now further ISP-programming is possible.
    
    Modified to do a Chiperase in case of locked target, which would fail to restore fuses.
    
    Credits to the original author: 
    Peter Fleury
    http://homepage.hispeed.ch/peterfleury/avr-hvsp-fuse-restore.html
