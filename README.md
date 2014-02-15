simple-BkpTool
==============

quick `n dirty incremental bkpTool using rsync

set-up
======

    touch ~/.bkp_exclude
    touch ~/.bkp_include

include paths to be backed up in ``~/.bkp_include`` as in

    /etc
    /var/named
    /root
    /opt/stuff