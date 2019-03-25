## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 2 with 6 Hz frequency seperation and 17 samples per symbol.

## **Frequency-shift Keying Modulation (FSK)**
### - Definition 
Frequency-shift keying (FSK) is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal. The channel used is an Additive white gaussian noise.


### - Before Additive Noise Channel
* Without Raised Cosine Filter:

    ![Regular](/FSK/BeforeChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/FSK/BeforeChannelRaisedCosine.png) 
### - After Additive Noise Channel
* Without Raised Cosine Filter: 

    ![Regular](/FSK/AfterChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/FSK/AfterChannelRaisedCosine.png) 
### - BER Diagram
* Without Raised Cosine Filter

    ![BER Diagram](/FSK/BerFigure.png)
