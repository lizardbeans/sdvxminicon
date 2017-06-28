# sdvxminicon
**Instructions here: http://consandstuff.pancakeapps.com/SOUNDVOLTEX/minicon**


Minicon Gallery http://imgur.com/a/BgS4V

The code is a modified version of this github repository:https://github.com/4yn/iivx

Upload using Arduino IDE 1.8.3

Tested only with 24ppr encoders.

## Part List

- 5mm laser cut clear acrylic $10-15
- 6pcs. 50x30mm chinese beatmania buttons $15 (led and switch included)
- 1pc. 30x30mm start buton $3 (led and switch included)
- 2pcs. cheap rotary encoder (24ppr) $10
- 2pcs. 22x20mm aluminum knobs $16
- 1pc. 50x50cm 5mm MDF plank (box walls) $2
- 1pc. 50x50cm 3mm MDF plank (box top and bottom door) $1
- 1pc. Arduino Leonardo PCB $18
- jumper wires pack $5
- 7pcs. crimp connectors $2 
- 2pcs. metal hinge $1 (for the door)
- 2pcs. magnetic lock $2 (for the door)
- 2pcs. 100 sandpaper $2
- 2pcs. 180 sandpaper $2

subtotal: $87

Want to change to SANWA buttons?
Add 6 12 dollar buttons instead of the chinese buttons.
Total: $144

Optional:
- 1pc. spray paint can $15 (matte white)

Tools:
- electric jigsaw
- electric sander
- electric drill

Skills:
- drilling- jigsaw-ing
- sanding
- soldering

**PIN LAYOUT (LEONARDO ARDUINO)**

<table><thead>
<tr>
<th>Button</th>
<th style="text-align: center">Pin #</th>
<th style="text-align: center">Button #</th>
<th style="text-align: center">LED Pin #</th>
</tr>
</thead><tbody>
<tr>
<td>Start</td>
<td style="text-align: center">13</td>
<td style="text-align: center">Button 1</td>
<td style="text-align: center">12</td>
</tr>
<tr>
<td>BT-A</td>
<td style="text-align: center">A5</td>
<td style="text-align: center">Button 2</td>
<td style="text-align: center">6</td>
</tr>
<tr>
<td>FX-L</td>
<td style="text-align: center">A4</td>
<td style="text-align: center">Button 3</td>
<td style="text-align: center">7</td>
</tr>
<tr>
<td>BT-B</td>
<td style="text-align: center">A3</td>
<td style="text-align: center">Button 4</td>
<td style="text-align: center">8</td>
</tr>
<tr>
<td>BT-C</td>
<td style="text-align: center">A2</td>
<td style="text-align: center">Button 5</td>
<td style="text-align: center">9</td>
</tr>
<tr>
<td>FX-R</td>
<td style="text-align: center">A1</td>
<td style="text-align: center">Button 6</td>
<td style="text-align: center">10</td>
</tr>
<tr>
<td>BT-D</td>
<td style="text-align: center">A0</td>
<td style="text-align: center">Button 7</td>
<td style="text-align: center">11</td>
</tr>
</tbody></table>


<table><thead>
<tr>
<th>ENCODERS</th>
<th style="text-align: center">DATA 1</th>
<th style="text-align: center">DATA 2</th>
</tr>
</thead><tbody>
<tr>
<td>Left knob (VOL-L)
<td style="text-align: center">0</td>
<td style="text-align: center">1</td>
</tr>
<tr>
<td>Right knob (VOL-R)
<td style="text-align: center">2</td>
<td style="text-align: center">3</td>
</tr>
</tbody></table>

>**If you're using 600ppr encoders you have to connect the encoders to the 5V pin for the 5v input (usually is the red wire)**

Any questions, troubleshooting or tips? Try my Discord server:

https://discord.gg/fknwz8s



