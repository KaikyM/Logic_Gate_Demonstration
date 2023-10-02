# Logic Gate Demonstration

## Contextualization
I decided to recreate the basic logic gates in Tinkercad using simple electronics concepts.
The red lines represent binary 1, the black lines represent binary 0, and the grey lines are used solely to enhance the contrast for better visibility in the binary operation

## Logic Gates
<!-- <div align="rigth">
        <table border=1>
            <tr>
                <th colspan="2">Truth Table</th>
            </tr>
            <tr>
                <td align="center"></td>
                <td align="center"></td>
            </tr>
        </table>
    </div>
-->
### Buffer
This is a logic buffer that allows the passage of binary signals, both 0 and 1. I added a multimeter to make it more visible how the system behaves with the button

<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/1e8ac394-19d8-4eb2-a06c-b0acb1f322da"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="2">Truth Table</th>
        </tr>
        <tr> 
            <td align="center">A</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
    </table>
</div>

### NOT
Additionally, in this case, the Blue LED represents the negated binary 1 signal, and the Green LED represents the negated binary 0 signal 

<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/5cbed003-1411-442b-a8d7-44117f84ecb6"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="2">Truth Table</th>
        </tr>
        <tr> 
            <td align="center">A</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
    </table>
</div>

### OR
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/87e44650-6607-443f-ad0a-4e7270396dca"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
    </table>
</div>

### NOR
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/79403e26-a364-4767-b678-bec6dc2130d5"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
    </table>
</div>

### AND
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/f6509897-e6ee-450e-ac1a-f05cce13f50a"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
    </table>
</div>

### NAND
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/ec66430c-3848-4cfc-b4ea-b8d93ad64ee3"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
    </table>
</div>

### XOR
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/40a5e704-9ff5-4812-9ed4-d4767af3a572"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
    </table>
</div>

### XNOR
<img src = "https://github.com/KaikyM/Logic_Gate_Demonstration/assets/127446435/698f8433-2455-4cca-a31a-db74ba3a7761"
height = "300" width = "430">
<div align="rigth">
    <table border=1>
        <tr>
            <th colspan="3">Truth Table</th>
        </tr>
        <tr>
            <td align="center">A</td>
            <td align="center">B</td>
            <td align="center">Q</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">0</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td align="center">0</td>
            <td align="center">1</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">0</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td align="center">1</td>
            <td align="center">1</td>
            <td align="center">1</td>
        </tr>
    </table>
</div>

<!-- #### Components !-->

## Project in Tinkercad
Buffer https://www.tinkercad.com/things/2UbSH6YD6GU

NOT https://www.tinkercad.com/things/iFZzMfyULqs

OR https://www.tinkercad.com/things/jZmgBy2CNzQ

NOR https://www.tinkercad.com/things/hGWIy5TmLfg

AND https://www.tinkercad.com/things/4ykYVhkMHVY

NAND https://www.tinkercad.com/things/4ZIl00nm4VT

XOR https://www.tinkercad.com/things/70X8IBE0pKK
