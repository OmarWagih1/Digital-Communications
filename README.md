# Digital-Communications

## **Binary Phase-Shift Keying Modulation (BPSK)**

### Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 0.7 with 100 samples per frame. The set size is 2 with 0 phase offset.

To Replicate the Ber Graph:
Open Matlab Console, type in bertool, this will open the bertool window , in the monte carlo tab choose the SLX filer and the range 
and press run.

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
* With Raised Cosine Filter

    ![BER Diagram](/BPSK/BerCos.png)

## **Frequency-shift Keying Modulation (FSK)**

### Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 2 with 6 Hz frequency seperation and 17 samples per symbol.

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
	
## **Quadrature phase-shift keying (QPSK)**
	
### Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 4 with pi/4 phase offset.

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
* With Raised Cosine Filter

    ![BER Diagram](/QPSK/BerCos.png)


## **Quadrature amplitude modulation (QAM16)**

### Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 16 with 0 rad phase offset and 1 Average Power.

### - Definition 
QAM conveys two analog message signals, or two digital bit streams, by changing (modulating) the amplitudes of two carrier waves, using the amplitude-shift keying (ASK) digital modulation scheme or amplitude modulation (AM) analog modulation scheme.. The channel used is an Additive white gaussian noise.


### - Before Additive Noise Channel
* Without Raised Cosine Filter:

    ![Regular](/QAM16/BeforeChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM16/BeforeChannelRaisedCosine.png) 
### - After Additive Noise Channel
* Without Raised Cosine Filter: 

    ![Regular](/QAM16/AfterChannel.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM16/AfterChannelRaisedCosine.png) 
### - BER Diagram
* Without Raised Cosine Filter

    ![BER Diagram](/QAM16/BerFigure.png)
* With Raised Cosine Filter

    ![BER Diagram](/QAM64/BerCos.png)
	
## **Quadrature amplitude modulation (QAM64)**
	
### Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67. Noise level is set to 10 Db for the scatter plots and Ber Figure is done on [-10,10] Db
Sample time is 1 with 100 samples per frame. The set size is 64 with 0 rad phase offset and 1 Average Power.

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
* With Raised Cosine Filter

    ![BER Diagram](/QAM64/BerCos.png)