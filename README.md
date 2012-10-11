#Monitor LSNs from MySQL and MySQL Variants#

Basic script based on [Baron Schwartz's blog post](http://www.mysqlperformanceblog.com/2008/11/21/how-to-calculate-a-good-innodb-log-file-size/) circa 2008.

##Description:##
The idea is to monitor the LSN of a server over a period of time. The output is a simple calculation of the number of megabytes per minute.

##Usage:##
You can provide an interval (in seconds) and the calculation with estimate the amount of MB per minute.