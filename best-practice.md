# A guide for the detection of weeds in mixed landscapes using remote sensing technologies

**Compiled by Dr Jane Kelly (Charles Sturt University)**

 ![Picture 1](RackMultipart20230302-1-z8asey_html_4f2c105310cf0455.gif)

# Table of contents

- [A guide for the detection of weeds in mixed landscapes using remote sensing technologies](#a-guide-for-the-detection-of-weeds-in-mixed-landscapes-using-remote-sensing-technologies)
  - [Introduction - remote weed detection](#introduction---remote-weed-detection)
  - [Aims and applications of remote detection](#aims-and-applications-of-remote-detection)
    - [1. Knowing your species and landscape](#1-knowing-your-species-and-landscape)
    - [2. Data capture platforms](#2-data-capture-platforms)
    - [3. Mission planning](#3-mission-planning)
    - [4. Ground truthing protocols](#4-ground-truthing-protocols)
    - [5. Environmental Sensors](#5-environmental-sensors)
    - [6. Data processing](#6-data-processing)
    - [7. Disadvantages of using remote sensing for weed control](#7-disadvantages-of-using-remote-sensing-for-weed-control)
    - [8. Publications](#8-publications)

## Introduction - remote weed detection

The detection of weeds in Australia has traditionally been undertaken by land managers as part of routine surveillance using manual ground searching methods. These methods have typically required significant labour, time, resources and expense to cover the distances required to obtain the data and as a result, datasets of mapped weed populations have often been limited.

Remote sensing offers an alternative approach to traditional manual weed surveillance methods, by facilitating the ability to detect distinctive plant species via the measurement of their individual reflected energy spectra at a distance. This process is commonly entitled, "remote weed detection".

Remote sensing in its broadest sense can be described as the process of recognizing and monitoring natural attributes of a location by measuring the emitted or reflected radiation. This is usually measured by sensors that are located at a distance, typically from an aerial platform, such as a satellite, aircraft or drone (also called an Unmanned Aerial vehicle, or UAV). Remote sensing is an efficient and cost-effective way to acquire geospatial data over large areas [2] and its use to assess weeds is a technology that is expanding across the globe.

However, there are numerous challenges associated with the use of this technology that are being encountered by those who wish to use it. Due to the highly technical nature of this field, there exists a real need to develop a set of introductory guidelines that could be used to educate those desiring to embark on the use of remote sensing for landscape weed detection and to address the challenges. It is hoped that this, combined with a progressive learning community will make these technologies more accessible to land managers into the future.

## Aims and applications of remote detection

### 1. Knowing your species and landscape

- Weed phenology and temporal changes (JK & HC)
- Look-alike species and phenology and temporal changes (JK & HC)
- Terrain features(JK & HC)
- Selecting a mapping site (RD)
- Terrain access (RD)
- Internet access for georeferencing (RD)

### 2. Data capture platforms

Ideas: Using project case studies to highlight aspects of each section – invite others to add their case studies to each section – could include a template to fill out on their work, with links to contacts/data.

#### Know your aerial platform

**Unmanned Aerial Vehicles (UAVs) – features and considerations**

UAVs come in a variety of types, shapes and sizes, with their design typically driven by application and endurance requirements. For example, large landscape surveys require UAV's that have long flight times and, in most cases, aeroplanes are a more suitable designed platform. Where smaller areas with variable terrain need to be covered then a multirotor may be more suitable.


Non-military, commercial UAV platform designs typically focus on aeroplanes, helicopters and multi-rotors. However, as the technology evolves there are numerous other UAV's that represent combinations of these designs. For survey related image capture, basic UAV platform examples are described below:

*Aeroplanes:*  
The electric-powered wing design is favoured by most manufactures in the survey market with average flight times ranging from 30-60 minutes equally approximately 180 - 300 acres in a single flight. Typically, these units are prepackaged with a high-resolution digital camera, while some also contain modified digital cameras capable of measuring a psuedo-NDVI. Flight height along with camera sensor and lens characteristics usually determines the size of pixel on the ground with spatial resolutions of 2- 4cm typically quoted by manufacturers. The flying wing designs are either catapult or hand launched allowing for greater portability in the field. The design typically provides good stability in windy environments with many manufactures quoting successful image capture in in winds up to 30-40 km/h. The leading manufacturers include the eBee Ag by SenseFly (approximately USD 25K) and AgEagle (approximately USD 15K), Trimble's UX5 (USD 50K) with many other suppliers now entering the survey UAV market. Commercial pricing is often dependent on the camera package and image processing choices associated with the plan. There are numerous other aeroplane designs such as high wing, mid wing, low wing platforms each having their own unique advantages and disadvantages related to flight duration, stability and takeoff and landing requirements. Most of these aeroplanes typically consists of a rigid wing with a predetermined airfoil capable of generating lift caused by the aeroplanes forward airspeed. Control surfaces such as the ailerons, elevator and rudder allow the aeroplanes direction and height to be controlled.

Larger platforms are also available and these are capable of carrying multiple payloads along with potentially delivering nutrients and herbicides. However, the larger wingspans typically limit the portability of these platforms due to their size along with many of the platforms typically have wheeled undercarriages that require designated areas suitable for taking off and landing. However, increased flight times and multiple camera systems (mutlispectral, optical, hyperspectral, thermal) may offer advantages for mapping or monitoring larger more complex agricultural systems.

**ToDo:** Fig. 1. Image of aeroplane here from Remy

*Multi-rotors*:  
Multi-rotors come in a number of designs e.g. quad, hex and octocopters named by the number of propellers used to launch the copter into the air. Multi-rotors can carry variable payloads depending on the design of the motor and propeller combination, but typical quadcopter systems have the greatest flight times but the least redundancy in terms of electronic or motor failure. Their ability to take off and hover directly at the site of interest along with their high maneuverability make them very useful in small survey applications. Flight times range from 10 minutes to up to 60 minutes in a very few high 7 end multi-copter platforms but flight times are typically reduced dramatically as payload is increased. The typical coverage ranges between 30-100 hectares for a 20-minute flight. DJI is one of the largest manufacturers of multi-copter turnkey systems along with 3DR Robotics whose open-source autopilot can be configured for a range of multi-copter, aeroplane and helicopter platforms. Pricing for multi-copter systems is extremely variable with DJI Phantom 3 quadcopter using a modified blue/NIR camera costing around USD $2500. Larger systems capable of carrying heavy payloads range in the USD$ 10-40K range. A good article showing a small range of the commercially available systems for agriculture can be found here: [http://dronelife.com/2015/10/14/7-best-agricultural-drones-market](http://dronelife.com/2015/10/14/7-best-agricultural-drones-market)

![](RackMultipart20230302-1-z8asey_html_39d114e45064a679.jpg)

**Fig. 2**. M600 **ToDo**(include description from Remy). Source: Dr Jane Kelly, CSU

*Helicopters:*  
Helicopters are to a lesser extent currently used for agricultural and environmental surveillance, typically because of their complexity and cost. Very few dedicated helicopter platforms have suitable reliable autopilot systems and those that do typically cost in the order of hundreds of thousands of dollars. However, many helicopter systems have great potential with the ability to land directly at the field site and hover extended periods of time. With further autopilot development, helicopters may benefit agriculture and environmental monitoring in areas outside remote sensing. Many of the large helicopters are capable of carrying large payloads in the order of 20-40kg for extended periods of times. This may be useful in areas such as herbicide and pesticide delivery along with nutrient delivery. A good example of the high-end helicopter is the Yamaha R-Max which is capable of carrying 28kg of payload and has both granular and liquid spraying capacities. Details of the R- MAX system can be found [here](http://rmax.yamaha-motor.com.au/specifications). Charles Sturt University and the author have developed a helicopter system capable of carrying a hyperspectral camera to determine if hyperspectral data enhances weed detection in weed trials.

Details can be found [here](http://www.caws.org.au/awc/2012/awc201211031.pdf).  

**Fig. 3.** **ToDo**Example of helicopter from Remy

**Fixed wing**

Features - considerations

**Satellite**

### 3. Mission planning  
Links to broad information, and including some more specifics associated with weeds. Could include the GeoNADIR pdf (with permission) on the website - Equipment, safety and flight regulations/restrictions - Planning software - Selecting altitudes/ pixel size - Weather, light and terrain
 - Flight path and map - Batteries, SD cards - Recording flight data

### 4. Ground truthing protocols
- What is ground truthing and when is it undertaken?
- What are ground control points and why are they important?
- Alignment of imagery and importance of spatial resolution
- Botannical data – lookalikes, phenological patterns, quadrats and placement, site data collection, equipment required
- Weather and landscape data
- Georeference data

### 5. Environmental Sensors

#### safety

#### image overlap and flight path design

#### altitude

#### camera angle

#### time of day and weather considerations

#### etc

#### General considerations

- limitations

#### RGB  

- Features
- Considerations
- Flight paths
- Sensor settings
- Data file management

#### Multispectral  

- Features
- Considerations
- Flight paths
- Sensor settings
- Data file management

#### Hyperspectral  

- Features
- Considerations
- Flight paths
- Sensor settings
- Data file management

### 6. Data processing  

**RGB imagery**

**MS imagery**

**HS imagery**

Ideas: Consideration of weed species with most suitable processing for each sensor – selection of models etc etc – here is what we did with each weed – contact details for those who have worked with the method they are interested in.

Use an infographic to show the processing path for each sensor –pathway diagram for each sensor. Could be clickable, to click on each section and where to find more information. Invitation to connect to COP to get more information and connect to those working in this space for support.

Create case study with HW to share as a template – may help to refine the infographic with steps.

Could have different sections targeting different levels of complexity – different section about processing for landholder to what we say to someone already working in processing.

#### Data records and outputs

- what format?
- shareable
- standardised
- measurement of error
- data storage and backup
- video or RGB images
- flight logs
- weather

#### Artificial Intelligence algorithms - detection

- automation
- common algorithms
- metadata and training datasets
- unsupervised learning
- limitations
- measurement of error
- no code and low code cloud platforms for AI (warnings)

### 7. Disadvantages of using remote sensing for weed control

Key core disadvantages of using remote sensing for weed control:
 - low image resolution
 - short flight time of drone plantforms
 - model error

-Weather and terrain, access

-Plant growth patterns

-Technology cost and access

-no code and low code cloud platforms for AI (warnings)

Etc


### 8. Publications  
Here is listed the publications, reports, conference papers from the project. This could be a separate page for each, or a summary of each paper, with main learnings set out in dotpoint form and a link to the paper.

Could have a spot to add further papers from COP members.

There should be a description of th COP and link to join

List or links to service providers for more assistance

**References**

Calvin Hung and Salah Sukkarieh, "Using robotic aircraft and intelligent surveillance systems for orange hawkweed detection," _Plant Protection_ , vol. 30, no. 3, pp. 100–102, 2015.
