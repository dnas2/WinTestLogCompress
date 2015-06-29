# WinTestLogCompress
Compress a DXpedition log generated by Win-Test

This program listens on Win-Test's UDP broadcast port for QSOs being added and compresses the QSO data to just a few bytes. (Win-Test is a commercial amateur radio contest logging program, which I am not related to. For details about Win-Test, see http://www.win-test.com)

Tested with Win-Test 4.15.0 in HF DXpedition mode. Other versions of Win-Test and other 'contest' templates may not work.

This has been designed for use on a particular amateur radio DXpedition and parts may need rewriting for use by other groups.

Requires .NET 4.5 and the program must be able to write to C:\logs to store the binaries created.