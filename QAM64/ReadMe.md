## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 64 with 0 rad phase offset and 1 Average Power.

## **Quadrature amplitude modulation (QAM)**
### - Definition 
QAM conveys two analog message signals, or two digital bit streams, by changing (modulating) the amplitudes of two carrier waves, using the amplitude-shift keying (ASK) digital modulation scheme or amplitude modulation (AM) analog modulation scheme.. The channel used is an Additive white gaussian noise.


### - Before Additive Noise Channel
* Without Raised Cosine Filter:

    ![Regular](/QAM64/BeforeChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM64/BeforeChannelRaisedCosine.png) 
### - After Additive Noise Channel
* Without Raised Cosine Filter: 

    ![Regular](/QAM64/AfterChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM64/AfterChannelRaisedCosine.png) 
### - BER Diagram
* Without Raised Cosine Filter

    ![BER Diagram](/QAM64/BerFigure.png)
