mailinfo
========

Parse and process email Received: headers

Usage:
mailinfo parses a single email message, provided on stdin, and outputs a summary of the Received: headers.

parsemailinfo parses the output of mailinfo, and outputs a plethora of output formats.

One really useful usage is "`cat message | mailinfo | parsemailinfo -t`".
