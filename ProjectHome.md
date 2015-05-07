This is a library with Java and C++ wrappers to implement high resolution timers. We used these timers to count the ticks when doing performance analysis and stuff like that.

This library exploits the system dependent timers / clocks and provided a timer like interface to the same. The library, compiles and functions on Linux, Solaris and Windows. The attached file, has build scripts for Linux and Solaris. There is also a JAVA wrapper over the library, which uses JNI to use the timer interfaces.

I would like to thank Nikhil Deshpande and Chandraprakash Jain, by seniors at work, in helping me out while I was working on this tool.