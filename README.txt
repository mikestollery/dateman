dateman
=======

Date Manipulator in perl

This contains a lot of superfluous files that has simply been cut-n-pasted from somewhere else
and I haven't bothered to cut out all the deadwood.

Also, I have doubts over its accuracy (a perl issue, I think) so this has been superceded by
datecalc, a PHP version which is part of Every Day Counts. This can be found here:

 - https://every1000.com/datecalc

One day I might separate datecalc into a stand-alone site.


To run dateman in dev environment:

 - localhost/dateman/cgi-bin/dateman.cgi

To release:

 - Upload dateman to stol.uk/htdocs
 - Make sure that stol.uk/htdocs/cgi-bin/dateman.cgi is executable (file permissions 755)
 - Remove from live site any occurrences of testpage.cgi and phpinfo.php

To run live:

 - http://stol.uk/dateman

