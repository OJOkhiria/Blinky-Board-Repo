# Blinky-Board-Repo
This is a starter project that uses a 555 timer in astable mode and a CD4017 IO expander to create a heart-shaped light-up board (with an optional Iron Man reference). It was made entirely with KiCad. PCB was custom-printed and hand-soldered using the resulting Gerber files. Full BOM is listed below and attached.
<img width="801" height="593" alt="Screenshot 2026-05-04 at 11 27 22 AM" src="https://github.com/user-attachments/assets/777c9b89-ef1e-43bc-80eb-2cc3346ed099" />

[Blinky Board .csv](https://github.com/user-attachments/files/27324070/Blinky.Board.csv)
Reference	Qty	Value	DNP	Exclude from BOM	Exclude from Board	Footprint	Datasheet
C1	1	0.01 uF				Capacitor_THT:CP_Radial_D5.0mm_P2.00mm	
C2	1	1 uF				Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm	
D1LED1,D2LED1,D5LED1,D6LED1,D7LED1,D8LED1,D9LED1,D10LED1,D11LED1,D12LED1	10	LED				LED_THT:LED_D3.0mm	
J1	1	Conn_01x02_Socket				Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical	
J2	1	Conn_01x01_Socket				Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical	
R1	1	1k				Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	
R2	1	470				Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	
RV1	1	50k				Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical	
U1	1	NE555P				Package_DIP:DIP-8_W7.62mm	http://www.ti.com/lit/ds/symlink/ne555.pdf
U2	1	4017				CMOS Decade Counter with 10 Decoded Outputs 16-PDIP -55 to 125:N16	http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf
