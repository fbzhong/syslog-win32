#syslog-win32

This project is an update of [syslog-win32](http://syslog-win32.sourceforge.net/), only include client library and header files.

##Legal
Refer to original Legal Statement of syslog-win32:

    The source code of the daemon and the client library IS NOT COPYRIGHTED and is offered for use in the public domain. You may use, modify or distribute it freely.

    However, the project includes syslog header file, logger utility and the test based on it. This stuff is distributed under the BSD license.

    The daemon uses Glib, libiconv and libintl libraries and the binary distribution includes them under the LGPL license.


##Change Logs

* add **`set_syslog_host`** function, in order to set syslog server directly;
* make message compatible with **[rsyslog](http://www.rsyslog.com/)**, **[rfc5424](http://tools.ietf.org/html/rfc5424)**;
* add vs2008 VC project file;

##Known Issues

* no **TCP** supported, only **UDP**;
* no **[rfc5425](http://tools.ietf.org/html/rfc5425)** supported;
