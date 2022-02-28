This is a quick implimentation of a Xinput (xbox controller) to Twincat ADS bridge.

Xinput folder:
The microsoft xinput reference sample from the SDK has been slightly modified to reference the twincat ADS C++ DLL's 

You need to install those in c:\twincat\ for this to compile without changes.
ADS C++ DLL's (tc 1000 package on beckhoff website)

TCxinputBridge folder:
Twincat XAE project containing the appropriate data structures, to recieve them from the controller being polled by the xinput app.


Currently only the first controller is sent.
