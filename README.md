# satcommands

Commands				
				
				
Systems	SYS			
Phone	PHONE			
GPS	GPS			
Power Supply	EPS			
IMU1	IMUI2C			
IMU2	IMUSPI			
Radio1	RADIO1			
Radio2	RADIO2			
System Manager	MGR			
Magnetorquers	MT			
MagX	MAGX			
MagY	MAGY			
MagZ	MAGZ			
Reaction Wheels	RW			
MotorX	MOTORX			
MotorY	MOTORY			
MotorZ	MOTORZ			
Temperature Master	TM			
TempX1	TEMPX1			
TempX2	TEMPX2			
TempY1	TEMPY1			
TempY2	TEMPY2			
TempZ1	TEMPZ1			
TempZ2	TEMPZ2			
IRArray Master	IR			
IRX1	IRX1			
IRX2	IRX2			
IRY1	IRY1			
IRY2	IRY2			
IRZ1	IRZ1			
IRZ2	IRZ2			
				
				
				
				
				
ACT	SYS		State Description	
NORMAL	SAT		Normal (has plenty of power)	
LOWPOWER	SAT		Low Power	
DEPLOY	SAT		Deploy Antenna	
DETUMBLE	SAT		Detumble Cubesat	
ADCS	SAT		Attitude Determination	
PHONE	SAT		Phone payload	
				
RESET	SAT		resetFunc();	Resets Portenta
TRANSMITDATA	SAT		MSG.movetoTransmitList(msg)	
DATALISTCLEAR	SAT		MSG.DataList.clear();	
MESSAGESLISTCLEAR	SAT		MSG.MessagesList.clear();	
TRANSMITLISTCLEAR	SAT		MSG.TransmitList.clear();	
TRANSMITTEDLISTCLEAR	SAT		MSG.TransmittedList.clear();	
START	<Subsystem>		addSystem(msg);	
				
MODE<XXX>	<Subsystem>		newMode(msg)	
OUTPUT	<Subsystem>		Output(msg)	
PLAY	<Subsystem>		play()	
PAUSE	<Subsystem>		pause()	
STOP	<Subsystem>		stop()	
OFF	<Subsystem>		off()	
SETSTATE	<Subsystem>	STATE:<State>	State(msg)	
UPDATE	<Subsystem>		Update(msg)	
ADDDATALIST	<Subsystem>		addDataList(msg)	
ADDTRANSMITLIST	<Subsystem>		addTransmitList(msg)	
STATUSUPDATE	<Subsystem>		statusUpdate(msg)	
<OTHER>	<Subsystem>		callNewFunction(msg);	
				
				
ACT	SYS			
Front/Back, Quality, ISO, Shutter speed, White Balance	PHONE			
CPHOTO(B,50%,100,250,CLOUDY)	PHONE			
CPHOTO(F,50%,100,100,AUTO)	PHONE			
CPHOTO(B,50%,100,250,CLOUDY)	PHONE			
CPHOTO(F,50%,100,100,AUTO)	PHONE			
CBURST(B,50%,100,10,CLOUDY)	PHONE			
CBURST(F,50%,100,500,CLOUDY)	PHONE			
CSTREAM(108.png,0)	PHONE			
CSTREAM(108.png,117)	PHONE			
CSTREAM(3858.jpg,0+)	PHONE			
CTIME	PHONE			
CGPS	PHONE			
				
				
ACT	SYS			
PINSON	MGR			
PINSOFF	MGR			
PHONEON	MGR			
BURNON	MGR			
IMUSPI	MGR			
IMU0	MGR			
IMU1	MGR			
IMU2	MGR			
I2C0	MGR			
I2C1	MGR			
I2C2	MGR			
L<PIN>	MGR			
H<PIN>	MGR			
W<PIN>	MGR			
?	MGR			
CHKCLOCKS	MGR			
CHKRADIO	MGR			
CHKCURRENTSTATE	MGR			
CHKALLSTATES	MGR			
CHKTEMPERATURE	MGR			
CHKBATTERY	MGR			
POWERLEVEL	MGR			
CHKROTATION	MGR			
CHKCORESYSTEMS	MGR			
CHKMESSAGES	MGR			
				
