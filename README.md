# Java7 Puppet Module
This module manages Oracle Java7.

This module has been tested against 3.0.1 on Ubuntu 12.04 and Debian 6.

Pull requests to add support for other operating systems are welcome.

*NOTE:* This module may only be used if you agree to the Oracle license: http://www.oracle.com/technetwork/java/javase/terms/license/

### Usage

    include java7

Pin version of Java:

    class { 'java7':
      pkg_version => '1.7.0_25',
    }

### Author
* Scott Smerchek <scott.smerchek@softekinc.com>

### Contributors:
* flosell: Added Debian 6 support
