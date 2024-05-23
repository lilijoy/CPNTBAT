# CPNTBAT
Mat data processed by FGI-GSRx receiver.   
The original data is tens of gigabytes, which is large and difficult to be disclosed. If you need, please contact me by email.    

## scenario
bs:BDS  
cs:GPS  
01: clean data  
03: 10 dB power advantage time spoofing  
04: 3 dB power advantage time spoofing  
05: 1 dB power advantage time spoofing  
06: 10 dB power advantage position spoofing  
07: 3 dB power advantage position spoofing  
08: 1 dB power advantage position spoofing  

## Column feature meaning
The dataset consists of 16 columns  
1: epoch  
2: satellite PRN  
3: C/N0 moving average  
4: C/N0 moving varience  
5: SQM moving average  
6: SQM moving varience  
7: pseudo-range residuals  
8: dopplor residuals  
9: Clock offset rate  
10: Clock offset  
11: dopplor  
12: Pseudo-range Doppler consistency  
13: spoofing label  
14: clock difference  
15: Median error of pseudo distance positioning residual  
16: Median error of Doppler velocity measurement residual  
