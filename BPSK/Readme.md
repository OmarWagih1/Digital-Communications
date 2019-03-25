## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 0.7 with 100 samples per frame. The set size is 2 with 0 phase offset.

## **Binary Phase-Shift Keying Modulation (BPSK)**
### - Definition 
BPSK is the simplest form of phase shift keying (PSK). It uses two phases which are separated by 180° and so can also be termed 2-PSK. The channel used is an Additive white gaussian noise.


### - Before Additive Noise Channel
* Without Raised Cosine Filter:

    ![Regular](/BPSK/BeforeChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/BPSK/BeforeChannelRaisedCosine.png) 
### - After Additive Noise Channel
* Without Raised Cosine Filter: 

    ![Regular](/BPSK/AfterChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/BPSK/AfterChannelRaisedCosine.png) 
### - BER Diagram
* Without Raised Cosine Filter

    ![BER Diagram](/BPSK/BerFigure.png)
