Description
-----------

gb, aka Greenbar, is a command line filter which, by default, inverts every other line of its input.
In this way, it's reminiscent of greenbar paper.

Usage
-----

% tail -f /var/log/httpd/access_log | gb

or to highlight lines that contain the word "named":

% tail -f /var/log/syslog/daemon.log | gb named

Author
------
John P. Speno john@macspeno.com


Thanks
------

Credit to M. Sirota for the original idea and awk implementation.
