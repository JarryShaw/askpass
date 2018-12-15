=======
AskPass
=======

The ``askpass`` utility for macOS. Originally inspired from the work of
`@theseal <https://github.com/theseal/ssh-askpass>`__, it is now also an
important component `MacDaily <https://github.com/JarryShaw/MacDaily>`__.

    See ``sudo(8)`` for more information.

Usage
=====

.. code:: shell

    askpass [-h|--help] [prompt]

.. image:: https://github.com/JarryShaw/AskPass/blob/master/sample/askpass.png

Installation
============

Homebrew
--------

.. code:: shell

    $ brew tap jarryshaw/tap
    $ brew install askpass
    # or simply, a one-liner
    $ brew install jarryshaw/tap/askpass

Manually
--------

.. code:: shell

    $ sudo cp askpass /usr/local/bin/
    $ cp askpass.plist ~/Library/LaunchAgents/
    $ ssh-add -c
