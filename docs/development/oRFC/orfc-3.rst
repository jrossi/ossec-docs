==================================
oRFC: 3 Rules/Decoder Requirements
==================================

OSSEC Coding Style Guide

+-----------+--------------------------------------------------------+
| Name      | Rules/Decoder Requirements for inclusion in OSSEC      |
+-----------+--------------------------------------------------------+
| Editor    | * Jeremy Rossi <jeremy at jeremyrossi dot com>         |
+-----------+--------------------------------------------------------+
| State     | Draft                                                  |
+-----------+--------------------------------------------------------+
| Origin    |                                                        |
+-----------+--------------------------------------------------------+


--------
Language
--------

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", 
"SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this 
document are to be interpreted as described in RFC 2119 [#]_.

------
Goals
------

This OSSEC oRFC is to detail the requirements and needs for including
new, and modifications to existing rules and decoders that are included
within OSSEC. The rules have the following goals

* Maximize testability in rules/decoders along with Code
* Minimize regressions in rules/decoders along with Code
* Define methods for saving log examples 
* Define methods for testing
* Trust the contributor.

