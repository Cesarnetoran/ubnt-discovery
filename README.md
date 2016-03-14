# ubnt-discovery
#
# UBNT Discovery tool for linux
# www.github.com/sunblade/ubnt-discovery



1. Requirements

- Linux OS
- X server
- OpenJDK Runtime Environment
- sudo

2. Installation

Create ubnt directory under /opt
    mkdir /opt/ubnt

Copy below listed files to '/opt/ubnt' directory

    ubnt-discovery
    ubnt-discovery-v2.4.1.jar
    ubnt-logo.png

Set file permissions

    sudo chmod -R 664 * /opt/ubnt
    sudo chmod +x /opt/ubnt/ubnt-discovery

Create a symlink in '/usr/bin'

    ln -s /opt/ubnt/ubnt-discovery /usr/bin/ubnt-discovery

Check if PATCH contains '/usr/bin'

    echo "$PATH"|grep -q /usr/bin && echo "OK - /usr/bin found"

3. Running UBNT discovery tool

run 'ubnt-discovery'
