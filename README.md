libRevenue
=======
Author: Rishi Ghosh

lib Revenue is a RunRev LiveCode Library that parses magnetic strip data. Track 1 and Track 2 data is parsed.
The following methods are supported. 


theDetectedIssuer [function]
-------------
+   Description: Parses the IIS and looks up against local database based on CC Num.
+   Examples: if theDetectedIssuer(tCardNum) is "MasterCard" then put "FALSE" into tVisa.
+   Parmeters: 
    +   pCardNum: A valid CC Num.


isOdd [function]
-------------
+   Description: No documentation yet.
+   Examples: No examples yet.
+   Parmeters: 
    +   pNum: No details for this parameter yet.


theLuhnCheck [function]
-------------
+   Description: Returns BOOL values based on the validity of the CC Num supplied.
+   Examples: No examples yet.
+   Parmeters: 
    +   pNumber: No details for this parameter yet.


theFasterLuhnCheck [function]
-------------
+   Description: A faster (but harder to undestand algorithm).
+   Examples: No examples yet.
+   Parmeters: 
    +   pNum: No details for this parameter yet.


parseTrack2 [function]
-------------
+   Description: Returns as much data as possible from the raw track data, including name, card number, expiry, etc.
+   Examples: No examples yet.
+   Parmeters: 
    +   pTrack2Data: No details for this parameter yet.


parseTrack1 [function]
-------------
+   Description: Returns as much data as possible from the raw track data, including name, card number, expiry, etc.
+   Examples: No examples yet.
+   Parmeters: 
    +   pTrack1Data: No details for this parameter yet.


countryNameFromCode [function]
-------------
+   Description: Detects country name from ISO code encoded into the track data.
+   Examples: No examples yet.
+   Parmeters: 
    +   pCode: No details for this parameter yet.



