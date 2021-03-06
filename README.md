Nsploit -- Popping Boxes with Nmap
==================================
Nsploit is a library for the Nmap Scripting Engine that integrates Nmap with
Metasploit via XmlRPC, allowing for fast exploitation of vulnerable systems.

Dependencies
------------
* Nmap - Original library demonstrated with Nmap 5.00, current version tested
  with current SVN build (5.61TEST1)
* Metasploit - Original library demonstrated with MSF 3, current version
  tested with MSF 4.0.1
* libexpat Lua bindings - available on Ubuntu as liblua5.1-expat0

Authors
-------
The original author of Nsploit is Ryan Linn (@sussurro). Updated by Daniel
miller (@bonsaiviking)

Known Bugs
----------
* The config file, ~/.Nsploit, cannot contain extraneous whitespace, such as
  indentation. Not sure if this is a problem.
* Metasploit has switched from XmlRPC to MessagePack for transport, which
  means this project no longer works.
