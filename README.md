# SRAM 

## SPECIFICATION 

|       TYPE       |     VALUE     |
| ---------------- | ------------- |
|     Word Size    |    32 Bits    |
| Number of Words  |     1024      |
|   Address line   |      10       |
| Number of Words  |     1024      |
|     SRAM Size    |     4 KB      |

## Memory Design Complier

![](images/LIberate_degin_compiler.png)
![](images/Legato_memory_Solution.png)
![](images/Liberate_MX_server.png)

## Prelayout Simulation

### 6T SRAM Cell

SRAM Cell Circuit Schematic:

![](images/SRAM_Circuit.png)

SRAM Cell Write Operation Circuit Schematic:

![](images/Ciruit_Schematic_Write.png)


SRAM Write Operation:

![](images/Write_Operation.png)


SRAM Cell Read Operation Circuit Schematic:

![](images/Circuit_Schematic_Read.png)


SRAM Read Operation: 

![](images/Read_Operation.png)


### SRAM Stability Analysis: 

Static Noise Margin: 

Hold SNM:

![](images/Hold_SNM_Ciruit.png)

![](images/Hold_SNM.png)


Read SNM: 

![](images/Read_SNM_Circuit.png)

![](images/Read_SNM.png)

SNM<sub>Low</sub>  = 0.243V 

SNM<sub>High</sub> = 0.222V

Read SNM = min(SNM<sub>Low</sub> , SNM<sub>High</sub> ) = 0.222V
