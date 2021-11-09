
# Tech Beyond the Myth

Forensic Report: Princess Induction Cooker Group 
===============


![](https://i.imgur.com/nbSAG6S.png)


:::warning
**Forensics of obsolescence** confronts us with the results of today's consumers' electronics industry model. By tearing apart broken everyday objects we uncover key topics such as systems thinking, supply chains, intellectual models, reverse engineering or programmed obsolescence. On top of it, by using a hands-on approach we introduce the use of fundamental technology hacking concepts: datasheets, multimeters, power supplies, electronic tools. We will document our findings by writing a **"forensic report"** of each artefact. 
:::


| Identity of the reporting agency       | MDEF                           |
|----------------------------------------|--------------------------------|
| Case identifier                        | Forensics of the Obsolescence  |
| Identity of the submitter              | Someone at the Fab Lab         |
| Date of receipt                        | 09/11/2021                     |
| Date of report                         | 09/11/2021                     |
| Identity and signature of the examiner | Kai, Busi, Vikrant, Pipa, Jeremy                     |
 

## Examination 

:::warning
Descriptive list of items submitted for examination, including serial number, brand and model
:::

Princess 
Slim Induction Cooker
Serial no.: 1304-303006


## Forensic Questions
:::warning
What does it do? How does it work? How it's built? Why it failed, or it wasn't used anymore?
:::
Is it an induction cooker? How does it work? Is it broken? Can we fix it? What is inside?

## Steps taken
:::warning
Research we carried out, i.e. Separating the components by type, searching for specific parts datasheets. Link datasheets and other relative documents.
:::
1. The unit was plugged in to an electrical outlet. Result: No signs of life.

2. The screws in the bottom cover were removed.

3. The bottom cover was removed.

4. The capacitors were discharged.

5. The screws holding the circuit boards in place were removed.

6. The circuit boards were wrmoved from the bottom cover.

7. The sleeve on the input fuse was cut and removed. Result: the fuse was intact.

8. The thermal paste was cleaned from the temperature probe.

9. The heat shrink around the input torroid was removed to reveal the loops of wire.

10. The Fan was unplugged and removed.

11. The induction coil was disconnected and removed.

12. The iser interface circuit board was unplugged and removed.

13. The heat sink was removed and the thermal paste was cleaned off
14. The heat shrink was cut and removed from the induction coil terminals to reveal the crimped connectors.

15. The user interface circuit board was powered directly with a power supply. Result: No signs of life. Perhaps something on this board is causing the problem with the device not powering on.

## Results
:::warning
Answers to the forensic questions. i.e. How many motors we find inside, does it contain a computer or microcontroller? Did the appliance failed, why?
:::

Components:

- Induction coil

- Temperature probe

- Heat sink

- Power and control circuit board (YS-CP2-EMC)

- User interface circuit board (YSB-62)

- Top glass cover (heat resistant glass ceramic)

- Bottom plastic cover

- Fan (ZHI YUAN DC FAN ZY DC-18V)

- Power cable

Failure mode: Unknown

Electrical components:

- Induction heater capacitors

- Induction cooker chip (HIGHWAY13A)

- Inductor cooker chip (HIGHWAY DRV1201)

- beeper

## Conclusions
:::warning
A summary of the overall report, in particular about the results.
:::

- At first nothing was working, so we disected it to see if any components were working, then we tried powering the user interface circuit board, which was not working.
- We got some components to turn on: the exhaust fan, the LED lights
- Conclusion: It doesn't work. Inconclusive as to the culprit

## Opinions
:::warning
What do you learn? What surprised you? 
:::
- The copper coil is perhaps worth selling.
- The circuit boards look like a city.
- Learned about heat sinks
- Noise filters
- Something so simple is actually so complex
- The user interface more interesting than expected

## Images and videos

![](https://i.imgur.com/pDNi1JQ.jpg)
![](https://i.imgur.com/rldP8SG.jpg)
![](https://i.imgur.com/sJQ5k3v.jpg)
![](https://i.imgur.com/i6rjL1X.gif)
The unscrewing and opening of the induction stove from the bottome
![](https://i.imgur.com/eCHWEav.gif)
The induction oven's user interface with sensing buttons 
![](https://i.imgur.com/WXUuyJZ.gif)
Powering of the LEDs of the user interface
![](https://i.imgur.com/oX2rYgI.gif)















