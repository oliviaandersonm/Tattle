Logging
=======

When Tattle runs, it emits log messages about what it is doing. 

By default, these logs can be found in ``$TATTLE_HOME/var/log/tattle.log``

If you would rather Tattle log to another directory, simply overwrite the ``logging_directory`` in ``$TATTLE_HOME/etc/tattle/logging.yml`` 

Levels
-------

The default setup for logging is to log only ``WARN`` messages and below.  You can turn on ``debug`` if you wish by editing ``$TATTLE_HOME/etc/tattle/logging.yaml`` and changing the level.
