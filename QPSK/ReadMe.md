## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 4 with pi/4 phase offset.

## **Quadrature phase-shift keying (QPSK)**
### - Definition 
QPSK uses four points on the constellation diagram, equispaced around a circle. With four phases, QPSK can encode two bits per symbol. The channel used is an Additive white gaussian noise.


### - Before Additive Noise Channel
* Without Raised Cosine Filter:

    ![Regular](/QPSK/BeforeChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QPSK/BeforeChannelRaisedCosine.png) 
### - After Additive Noise Channel
* Without Raised Cosine Filter: 

    ![Regular](/QPSK/AfterChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QPSK/AfterChannelRaisedCosine.png) 
### - BER Diagram
* Without Raised Cosine Filter

    ![BER Diagram](/QPSK/BerFigure.png)
