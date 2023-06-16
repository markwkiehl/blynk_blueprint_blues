# blynk_blueprint_blues
Connecting Blues (blues.io) IoT products to Blynk

# Functional Requirements
- Send data on a fixed interval from a Blues device to Blynk and display the data with appropriate Blynk widgets the Blynk app and Blynk web dashboard.
- The data sent could include all possible Blynk datastream data types, plus cellular quality, cellular strength, battery charge:
    - V0 sw  integer  0-1
    - V1 int  integer  0-255
    - V2 dbl  double  0.0-3.3
    - V3 enum  enumerable
    - V4 loc  location
    - V5 text  string
    - V6 cell_qual  double  0-100
    - V7 cell_str  double 0-100
    - V8 bat_chg  double 0-100 
- Include the ability for Blynk to send data back to the Blues hardware, causing it to react in response (remote control hardware with Blynk).  
