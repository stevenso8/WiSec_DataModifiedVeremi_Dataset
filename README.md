# WiSec_DataModifiedVeremi_Dataset
Modified Dataset for Physical Layer Analysis V2X

To cite this dataset please cite:

Steven So, Jonathan Petit, and David Starobinski. 2019. Physical Layer Plausibility Checks for, Misbehavior Detection in V2X Networks. In Proceedings of ACM WiSec Conference (WiSec’19). ACM, New York, NY, USA, Article 4,10 pages.


Each of the .mat files contain simulation data in Veremi. 
The following numbers correspond to different attack types:
•	Type 1 : Constant Position
•	Type 2: Constant Offset
•	Type 4: Random Position
•	Type 8: Random Offset
•	Type 16: Eventual Stop

The columns in each of the datasets correspond to the following fields:
1.	Type (3=BSM)
2.	Time BSM was received by the receiver
3.	Receiver ID
4.	Receiver X position
5.	Receiver Y position
6.	Receiver Z position
7.	Time BSM was transmitted 
8.	Transmitter ID
9.	BSM ID 
10.	Transmitter X position
11.	Transmitter Y position
12.	Transmitter Z position
13.	Transmitter X velocity
14.	Transmitter Y velocity
15.	Transmitter Z velocity
16.	RSSI of received signal
17.	Label (0=Normal Behavior)
