CTPyClient
==========

Python Certificate Transparency client

A collection of utilities to explore CT log servers.

monitor.py
----------

This utility implements a very basic CT client to fetch entries
from a CT log and display the certificates that are retrieved.

Usage:

monitor.py [number of log entries relative to last log entry to fetch]

Requires:
pyopenssl
requests

Currently, monitor.py is hardcoded to use Google's log servers.
