# Introduction

This is a drop-in replacement for java.util.Hashtable, written by
Dr. Cliff Click and donated to public domain. It is lock-free and
still multi-threaded safe. It can scale linearly to 768 CPUs. 

The repository was in sourceforge and seems to be not as well-known
as it should be. So I copied it here in the hope of letting more
java developers use it.

# Build

	javac build.java
	java build all

# Reference

You can also check out README.cliffc for more instructions.
There's also a video by Dr. Cliff Click talking about the lib:
(http://www.youtube.com/watch?v=k5FltpgKcVk)

Edward Wang