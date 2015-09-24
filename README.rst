nagios-hipchat
==================

This repo collect a series of script to operate hipchat related services an monitoring it using nagios. Typical application are: check for the status of a given user or room usage.

check_user_hipchat
^^^^^^^^^^^^^^^^^^^

The check_user_hipchat script is a nagios check script that can be used to check the availability of a user.

::

  check_user_hipchat [-t <hipchat_token>] -u <username>

The hipchat_token can also be provided via envs setting up the ``HIPCHAT_TOKEN`` var, in the case the command line args will override the env var.


check_room_hipchat
^^^^^^^^^^^^^^^^^^^

yet to come...
