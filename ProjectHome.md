This is a Winsock Packet Editor with an easy to use plugin framework to expand its uses and analyze packets over the TCP(and UDP) protocol under Windows' Winsock library

Plugins can be written in C/C++/Python and even X86 assembly.
Basic functions will be to analyze Sent and Recieved packets via hooks into the executable that the program resides in. The main application runs from a dll which is injected with the supplied commandline loader/injector.