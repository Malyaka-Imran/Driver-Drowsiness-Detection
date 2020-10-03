This program is aimed at increasing road safety for drivers. It is called a Driving Drowsiness Detector, and mainly uses the library OpenCV in Python. We use the blink rate of the driver to detect how drowsy or tired they are. The more they blink, the more likely they are to be tired. The program detects blinks by using a threshold eye aspect ratio (EAR). Once the EAR of the driver surpasses that threshold, we know that they are blinking or their eyes are closed. If the state continues like that for longer than a threshold amount of time (ie. they are dozing off) or the EAR fluctuates above and below its threshold more than a certain number of times (i.e. they are blinking excessively, hence, they are tired and very likely to doze off), the program sets off an alarm and wakes them up. 
We believe this program has the potential to make road safety more affordable for people who can't afford expensive vehicles like Tesla that have these safety measures pre-installed. 

Citations:
1.	The correlation between blink rate and tiredness is statistically proven 	 by many studies. One is cited here: 
	https://www.ncbi.nlm.nih.gov/pubmed/15716219
2.  This project uses existing code from 
     https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/
     The existing code focused on detecting when a driver dozes off. We extended it to detect not just when the driver is dozing off, but also when they are very tired. This tells us when they are about to probably doze off and allows us to warn them beforehand. This functionality improves the safety level of the driver by making the program more preventative. 

Group Members: 
Ajey Gowda, Malyaka Imran, Mauricio Solorzano, Pavan Sharma, Rohit Rangan, 

Presented at: HackUmass 2019. 
