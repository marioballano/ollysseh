# Description

This OllyDbg plugin performs an in-memory scan of loaded modules to display some of their compiled options that aid in exploit development, originally it only supported '/SafeSEH', ASLR and NX flags have only recently been implemented.
  
# References

http://msdn2.microsoft.com/en-us/library/9a89h429(VS.80).aspx
http://www.microsoft.com/whdc/system/platform/firmware/PECOFF.mspx

# Greets

* Ruben Santamarta, from http://www.reversemode.com/, for helping me with an anoying unicode/mdi bug in my Visual Studio project! :-)
* poxyran: For implementing ASLR and NX checks.
