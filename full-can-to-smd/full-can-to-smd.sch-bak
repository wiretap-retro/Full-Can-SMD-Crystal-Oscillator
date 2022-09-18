EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Full Can Clock to SMD"
Date "2021-08-23"
Rev "0.3"
Comp ""
Comment1 "3.3V SMD to 5V Full Can Adapter"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Oscillator:CXO_DIP14 X0
U 1 1 610A8CF9
P 5050 3750
F 0 "X0" H 5394 3796 50  0000 L CNN
F 1 "CXO_DIP14" H 5394 3705 50  0000 L CNN
F 2 "Oscillator:Oscillator_DIP-14" H 5500 3400 50  0001 C CNN
F 3 "http://cdn-reichelt.de/documents/datenblatt/B400/OSZI.pdf" H 4950 3750 50  0001 C CNN
	1    5050 3750
	1    0    0    -1  
$EndComp
$Comp
L Oscillator:ASCO X1
U 1 1 610AC7B7
P 6650 3750
F 0 "X1" H 7094 3796 50  0000 L CNN
F 1 "ASCO" H 7094 3705 50  0000 L CNN
F 2 "Oscillator:Oscillator_SMD_Abracon_ASV-4Pin_7.0x5.1mm" H 6750 3400 50  0001 C CNN
F 3 "https://abracon.com/Oscillators/ASCO.pdf" H 6425 3875 50  0001 C CNN
	1    6650 3750
	1    0    0    -1  
$EndComp
Text Label 4550 3750 0    50   ~ 0
EN
Text Label 5600 4200 0    50   ~ 0
3.3VDC
Text Label 6650 3300 0    50   ~ 0
3.3VDC
Text Label 5050 3300 0    50   ~ 0
5VDC
Text Label 7050 4000 0    50   ~ 0
3VCLK
Text Label 5350 4000 0    50   ~ 0
5VCLK
Wire Wire Line
	7050 3750 7050 4000
Wire Wire Line
	6650 3450 6650 3300
Wire Wire Line
	5050 3300 5050 3450
Wire Wire Line
	5350 3750 5350 4000
Wire Wire Line
	4750 3750 4550 3750
$Comp
L Device:CP_Small C1
U 1 1 610B68CA
P 4950 5650
F 0 "C1" H 5038 5696 50  0000 L CNN
F 1 "1uF" H 5038 5605 50  0000 L CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 4950 5650 50  0001 C CNN
F 3 "~" H 4950 5650 50  0001 C CNN
	1    4950 5650
	1    0    0    -1  
$EndComp
$Comp
L Device:CP_Small C2
U 1 1 610B6FD3
P 6550 5650
F 0 "C2" H 6638 5696 50  0000 L CNN
F 1 "1uF" H 6638 5605 50  0000 L CNN
F 2 "Capacitor_SMD:C_0805_2012Metric_Pad1.15x1.40mm_HandSolder" H 6550 5650 50  0001 C CNN
F 3 "~" H 6550 5650 50  0001 C CNN
	1    6550 5650
	1    0    0    -1  
$EndComp
Text Label 6800 5450 0    50   ~ 0
3.3VDC
$Comp
L power:GND #PWR0101
U 1 1 610B9261
P 6650 4200
F 0 "#PWR0101" H 6650 3950 50  0001 C CNN
F 1 "GND" H 6655 4027 50  0000 C CNN
F 2 "" H 6650 4200 50  0001 C CNN
F 3 "" H 6650 4200 50  0001 C CNN
	1    6650 4200
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0102
U 1 1 610B968A
P 5050 4200
F 0 "#PWR0102" H 5050 3950 50  0001 C CNN
F 1 "GND" H 5055 4027 50  0000 C CNN
F 2 "" H 5050 4200 50  0001 C CNN
F 3 "" H 5050 4200 50  0001 C CNN
	1    5050 4200
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0103
U 1 1 610B97CD
P 6550 5900
F 0 "#PWR0103" H 6550 5650 50  0001 C CNN
F 1 "GND" H 6555 5727 50  0000 C CNN
F 2 "" H 6550 5900 50  0001 C CNN
F 3 "" H 6550 5900 50  0001 C CNN
	1    6550 5900
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0104
U 1 1 610B9BDD
P 4950 5900
F 0 "#PWR0104" H 4950 5650 50  0001 C CNN
F 1 "GND" H 4955 5727 50  0000 C CNN
F 2 "" H 4950 5900 50  0001 C CNN
F 3 "" H 4950 5900 50  0001 C CNN
	1    4950 5900
	1    0    0    -1  
$EndComp
Wire Wire Line
	4950 5750 4950 5800
Text Label 4650 5350 0    50   ~ 0
5VDC
Wire Notes Line
	4550 4800 7350 4800
Wire Notes Line
	7350 4800 7350 6250
Wire Notes Line
	7350 6250 4550 6250
Wire Notes Line
	4550 6250 4550 4800
Text Notes 5650 6200 0    50   ~ 0
5V to 3.3V Circuit
Wire Wire Line
	6650 4050 6650 4200
Wire Wire Line
	5050 4050 5050 4200
$Comp
L SamacSys_Parts:SN74LV1T34DBVRG4 IC2
U 1 1 610BD107
P 5300 2350
F 0 "IC2" H 5850 2615 50  0000 C CNN
F 1 "SN74LV1T34DBVRG4" H 5850 2524 50  0000 C CNN
F 2 "SOT95P280X145-5N" H 6250 2450 50  0001 L CNN
F 3 "http://www.ti.com/lit/gpn/sn74lv1t34" H 6250 2350 50  0001 L CNN
F 4 "Single Power Supply BUFFER Logic Level Shifter (no enable)" H 6250 2250 50  0001 L CNN "Description"
F 5 "1.45" H 6250 2150 50  0001 L CNN "Height"
F 6 "595-SN74LV1T34DBVRG4" H 6250 2050 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.co.uk/ProductDetail/Texas-Instruments/SN74LV1T34DBVRG4?qs=vdi0iO8H4N10R%252Bt%252BjmxZrg%3D%3D" H 6250 1950 50  0001 L CNN "Mouser Price/Stock"
F 8 "Texas Instruments" H 6250 1850 50  0001 L CNN "Manufacturer_Name"
F 9 "SN74LV1T34DBVRG4" H 6250 1750 50  0001 L CNN "Manufacturer_Part_Number"
	1    5300 2350
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0105
U 1 1 610CACA6
P 5150 2650
F 0 "#PWR0105" H 5150 2400 50  0001 C CNN
F 1 "GND" H 5155 2477 50  0000 C CNN
F 2 "" H 5150 2650 50  0001 C CNN
F 3 "" H 5150 2650 50  0001 C CNN
	1    5150 2650
	1    0    0    -1  
$EndComp
Wire Wire Line
	5300 2550 5150 2550
Wire Wire Line
	5150 2550 5150 2650
Text Label 6600 2450 0    50   ~ 0
5VDC
Wire Wire Line
	6400 2450 6600 2450
Text Label 4900 2450 0    50   ~ 0
3VCLK
Text Label 6600 2350 0    50   ~ 0
5VCLK
Wire Wire Line
	6400 2350 6600 2350
Wire Wire Line
	4900 2450 5300 2450
$Comp
L SamacSys_Parts:ADP1710AUJZ-3.3-R7 IC1
U 1 1 610CC7CC
P 5400 5350
F 0 "IC1" H 5900 5615 50  0000 C CNN
F 1 "ADP1710AUJZ-3.3-R7" H 5900 5524 50  0000 C CNN
F 2 "SOT95P280X100-5N" H 6250 5450 50  0001 L CNN
F 3 "https://componentsearchengine.com/Datasheets/1/ADP1710AUJZ-3.3-R7.pdf" H 6250 5350 50  0001 L CNN
F 4 "LDO Voltage Regulators IC 150mA LDO CMOS" H 6250 5250 50  0001 L CNN "Description"
F 5 "1" H 6250 5150 50  0001 L CNN "Height"
F 6 "584-ADP1710AUJZ3.3R7" H 6250 5050 50  0001 L CNN "Mouser Part Number"
F 7 "https://www.mouser.com/Search/Refine.aspx?Keyword=584-ADP1710AUJZ3.3R7" H 6250 4950 50  0001 L CNN "Mouser Price/Stock"
F 8 "Linear Technology" H 6250 4850 50  0001 L CNN "Manufacturer_Name"
F 9 "ADP1710AUJZ-3.3-R7" H 6250 4750 50  0001 L CNN "Manufacturer_Part_Number"
	1    5400 5350
	1    0    0    -1  
$EndComp
Wire Wire Line
	4650 5350 4950 5350
Wire Wire Line
	5400 5450 5250 5450
Wire Wire Line
	5250 5450 5250 5800
Wire Wire Line
	5250 5800 4950 5800
Connection ~ 4950 5800
Wire Wire Line
	4950 5800 4950 5900
Wire Wire Line
	4950 5550 4950 5350
Connection ~ 4950 5350
Wire Wire Line
	4950 5350 5300 5350
Wire Wire Line
	5400 5550 5300 5550
Wire Wire Line
	5300 5550 5300 5350
Connection ~ 5300 5350
Wire Wire Line
	5300 5350 5400 5350
Wire Wire Line
	6400 5450 6550 5450
Wire Wire Line
	6550 5450 6550 5550
Connection ~ 6550 5450
Wire Wire Line
	6550 5450 6800 5450
Wire Wire Line
	6550 5750 6550 5900
Wire Notes Line
	4800 1950 7050 1950
Wire Notes Line
	7050 1950 7050 3000
Wire Notes Line
	7050 3000 4800 3000
Wire Notes Line
	4800 3000 4800 1950
Text Notes 5550 2950 0    50   ~ 0
Clock Level Shift
Wire Wire Line
	5600 4200 5900 4200
$Comp
L Connector_Generic:Conn_01x03 J1
U 1 1 6123B33B
P 6000 4400
F 0 "J1" V 5872 4580 50  0000 L CNN
F 1 "DISABLE" V 5963 4580 50  0000 L CNN
F 2 "Connector_PinHeader_2.00mm:PinHeader_1x03_P2.00mm_Vertical" H 6000 4400 50  0001 C CNN
F 3 "~" H 6000 4400 50  0001 C CNN
	1    6000 4400
	0    1    1    0   
$EndComp
Wire Wire Line
	6100 4200 6650 4200
Connection ~ 6650 4200
Wire Wire Line
	6250 3750 6000 3750
Wire Wire Line
	6000 3750 6000 4200
$EndSCHEMATC
