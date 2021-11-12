
# Tech Beyond the Myth

**Journal Index**

[TOC]
## Forensic Report: Princess Induction Cooker Group 


![](https://i.imgur.com/nbSAG6S.png)


:::
**Forensics of obsolescence** confronts us with the results of today's consumers' electronics industry model. By tearing apart broken everyday objects we uncover key topics such as systems thinking, supply chains, intellectual models, reverse engineering or programmed obsolescence. On top of it, by using a hands-on approach we introduce the use of fundamental technology hacking concepts: datasheets, multimeters, power supplies, electronic tools. We will document our findings by writing a **"forensic report"** of each artefact. 
:::


| Identity of the reporting agency       | MDEF                           |
|----------------------------------------|--------------------------------|
| Case identifier                        | Forensics of the Obsolescence  |
| Identity of the submitter              | Someone at the Fab Lab         |
| Date of receipt                        | 09/11/2021                     |
| Date of report                         | 09/11/2021                     |
| Identity and signature of the examiner | Kai, Busi, Vikrant, Pipa, Jeremy                     |
 
**Examination**

:::
Descriptive list of items submitted for examination, including serial number, brand and model
:::

Princess 

Slim Induction Cooker

Serial no.: 1304-303006


**Forensic Questions**

:::
What does it do? How does it work? How it's built? Why it failed, or it wasn't used anymore?
:::

Is it an induction cooker? How does it work? Is it broken? Can we fix it? What is inside?

**Steps taken**

:::
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

**Results**

:::
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

**Conclusions**

:::
A summary of the overall report, in particular about the results.
:::

- At first nothing was working, so we disected it to see if any components were working, then we tried powering the user interface circuit board, which was not working.

- We got some components to turn on: the exhaust fan, the LED lights.

- Conclusion: It doesn't work. Inconclusive as to the culprit


**Opinions**

:::
What do you learn? What surprised you? 
:::

- The copper coil is perhaps worth selling.

- The circuit boards look like a city.

- Learned about heat sinks.

- Noise filters.

- Something so simple is actually so complex.

- The user interface more interesting than expected.

 **Images and videos**

![](https://i.imgur.com/vx1IHwQ.jpg)

Induction cooker dissected

![](https://i.imgur.com/pDNi1JQ.jpg)
![](https://i.imgur.com/rldP8SG.jpg)
![](https://i.imgur.com/sJQ5k3v.jpg)
![](https://i.imgur.com/i6rjL1X.gif)

The unscrewing and opening of the induction stove from the bottome
![](https://i.imgur.com/NwtGPuP.png)
![](https://i.imgur.com/eCHWEav.gif)

The induction oven's user interface with sensing buttons 

![](https://i.imgur.com/WXUuyJZ.gif)

Powering of the LEDs of the user interface

![](https://i.imgur.com/oX2rYgI.gif)

## Data Recollection

**Eating Space at IAAC 🍝**
====================

Measuring the world / A world in data activity report.
**Andrea | Dídac | Kai | Rei | Ruben**

![](https://i.imgur.com/NN5hYXb.jpg)


**From objectives to the hypothesis**

**Brainstorming**
Multiple images about the brainstorming process:
![](https://media.giphy.com/media/hR5hrKJ8oBmELQYJPp/giphy.gif =730x)

![](https://i.imgur.com/WobCrxr.jpg)

![](https://i.imgur.com/fz6GUie.jpg)


**Project Goals**
**Objective:** 
I want to have a place to eat lunch inside IAAC.

**Question:** 
Are all spaces in IAAC in use at lunch time?

**Hypothesis:** 
- Lunch&Afternoon Data
"There is a space for a (covid-safe) lunch?"
- Morning Data
"Are there people in Iaac interested in having a space to have lunch?"


**From hypothesis to data**

**Tools selection**

![](https://i.imgur.com/xsEUGUi.jpg)


We decided to choose the PiCamera as a tool for the experiment. We thought it would be quite a practical way of checking the availability of IAAC spaces and counting people. However, a physical intervention would have been also an appropriate means to collect data for our case.

**Tool 🔧 usage documentation:**

We used the PiCamera to create timelapses in two different ways:
- POV timelapse: the camera was taking pictures while we moved around the different spaces of IAAC.
- Static timelapse: the camera was static in a specific place and captured everything that happened there.

For the camera settings, we decided to use a low resolution (320x240px) in order not to have heavy files. We also set the photo frequency to 1 picture per second to have enough information from people's movements.

![](https://media.giphy.com/media/7gzVLH8E2G7c5kYBWY/giphy.gif =730x)

**Data capturing strategy:**

Our strategy consisted of two main points: The first one was based on checking the different spaces of IAAC with the camera during lunchtime and seeing if there was people eating inside. Thanks to this, we could get information for both of our hypothesis.
The second one focused on testing the interest of people around a poster in the entrance communicating a supposed "Lunch Room" at IAAC's main hall. This would let us know about support for this idea.

Also, we had to change the strategy in the middle of the data collection since the PiCamera stopped working. Our intention there was to count the amount of people going to eat outside during lunchtime compared to the total of people at IAAC. However, we believe this wasn't a major problem for our research.

**Materials needed:**

Picamera, "LunchRoom" poster, Iaac map and personal interviews to people that were heating their food in the microwave or eating in the classrooms.

**Detail setup instructions:**

![](https://media.giphy.com/media/S8qC6M7fq0lmiJpHcG/giphy.gif =730x)

![](https://i.imgur.com/JsOASbS.jpg =365x)

![](https://i.imgur.com/1sAqZFU.jpg)

![](https://media.giphy.com/media/pW0DfHNUFL2OjZGOU5/giphy.gif =730x)

![](https://i.imgur.com/zSxMyNp.png)


**Data collected**

Describe the raw data you collected by posting a sample i.e. a picture, a screen capture, etc.

For privacy reasons we are not able to show the images captured by the Raspberry Pi. Two impressions of the data generated shown below.

"Where people are eating lunch inside IAAC building ": 

![](https://i.imgur.com/StuMKVz.png)

"People that was interested in the Lunch room poster":

![](https://media.giphy.com/media/AjsEIYMFUE2a97IuYm/giphy.gif =730x)
Video recorded with the PiCamera

![](https://i.imgur.com/yl1W9gn.png)

**Data capture**

**Data summary**

| Data Summary             |                    |
|--------------------------|--------------------|
| Project Title            |Where people are eating lunch inside IaaC building
| Capture Start            | 11-11-2021         |
| Capture End              | 11-11-2021         |
| Original Data Format     | Timelapse mp4  |
| Submitted format         | CSV file           |
| Total Data Points        | 28                |
| Number of datasets       | 1                  |
| Data Repository          | https://github.com/fablabbcn/mdef-a-world-in-data/blob/main/eating-space-at-iaac/LunchTime.csv|

| Data Summary             |                    |
|--------------------------|--------------------|
| Project Title            |People that was interested in the Lunch room poster       |
| Capture Start            | 12-11-2021         |
| Capture End              | 12-11-2021         |
| Original Data Format     | Timelapse mp4   |
| Submitted format         | CSV file           |
| Total Data Points        | 6
| Number of datasets       | 1                  |
| Data Repository          | https://github.com/fablabbcn/mdef-a-world-in-data/blob/main/eating-space-at-iaac/peopleinterestedinposter.csv |


### Data insights
![](https://i.imgur.com/JMpI1qZ.jpg)

Post at least two images of a chart, a screen-shoot of your data, that you used to prove if your hypothesis is false.
![](https://i.imgur.com/eTfS5eT.png)
![](https://i.imgur.com/K8Pi6uV.png)
![](https://i.imgur.com/RIhSWKY.png)

**REFLECTION**

**I want to have a place to eat lunch inside IAAC**

Are all spaces in IAAC in use?
Yes, but it depends on the day time.

By the data we collected at lunch time we saw that at that time, most spaces were empty and some occupied by the master’s students but regarding to each students master’s classrooms with a camera stick to Ruben's body. 
As for example, MDEF classroom was occupied by MDEF students, some ate there or in the main hall tables around the kitchen.

After lunch, we recollected some more data by going around with the camera and saw that all the spaces were occupied by master classes or office things.
We too, put the camera on the entrance to recollect data of how many people entered Iaac after lunch, but the video stopped unexpectedly and we lost that data. 

So with some help of how to recover the data, the today day morning, we made a "LunchRoom" fake poster of using the main hall as a lunch space and put it on the entrance to see people’s reactions and if they were interested on joining.


During the process of collecting this data, watching people through the camera, we collected that 49 of people in average didn’t looked at all, 15.5 in average looked, and 15.5 in average stopped to read.
We reflect that maybe the spot were we put the poster, wasn’t the best spot to it because there is more quantity of people that didn’t looked compared to the ones that did. Maybe if we had more time, we could change the spot to another one like in the bathroom or in another space that people is obligated to look; such as the gender expression group that selected the bathroom and at a simple view, they had a lot of reactions. So, instead of using a camera because of privacy if we choose the bathroom, we could make a more interactive intervention of people expressing how they feel about not having a lunch space, or were do they eat or if they like to occupy a space to have lunch, or maybe if they want to join to make the rooftop a more capable space to have lunch.

This take us to other questions regarding to the exercise of choosing a hypothesis sauce as, could we change the rooftop for this purpose?, were people eat during lunch time?, how many people don't eat at iaaac because ther is no common space?















