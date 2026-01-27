# gantry-minimill
Milling machine project (gantry style, high performance epoxy concrete)


## Summary of the project

Inspired by stef110's work (https://www.cnczone.com/forums/vertical-mill-lathe-project-log/337318-cnc-forum-posts-6.html).

It is also inspired by scratchbuilt designs' benchtop gantry mill.



Basic materials ordered from the same places as him.

## 

## BOM (Bill Of Materials)

### Basics components 

* Silica aggregate      

    |Reference|Descr.|Amount|Link|
    |---|---|---|---|
    |SILIMIX® 282|granulation 0-4 mm||https://www.moertelshop.com/buy-SILIMIX-282-cheaply_5|

* Epoxy resin

### Steel

### Screws, nuts, washers

### Bearings, flanges, etc

* Rails     

    |Reference|Descr.|Amount|
    |---|---|---|
    |RGR25R670|670mm|1|
    |RGR25R750|750mm|1|
    |RGR25R900|900mm|1|

* Rollers       
    |Reference|Descr.|Amount|
    |---|---|---|
    |RGH25HAZAH|Narrow rollers|8|
    |RGW25HCZAH|Wide rollers|4|

* Bearings     

    |Reference|Descr.|Amount|Link|
    |---|---|---|---|
    |MBA15-E|80x80 Servo Motor Bracket (MBA15-E) for FK15|3|https://www.damencnc.com/en/80x80-servo-motor-bracket-mba15-e-for-fk15/a2113?search=mba15|
    |FK15|Fixed Ballscrew Support Unit|3|https://www.damencnc.com/en/fk15-fixed-ballscrew-support-units-c3-quality/a1433?search=fk15|
    |BF15-C3|Floating Ballscrew Support Unit|3|https://www.damencnc.com/en/bf15-c3-floating-ballscrew-support-unit-c3-quality/a1447?search=bf15|
    |MGD 20L|Round to Square Adapter for DIN type ballnuts|3|https://www.damencnc.com/en/mgd20l-round-to-square-adapter-for-din-type-ballnuts/a3280?search=mgd%2020l|

* Ball screws

    |Reference|Descr.|Amount|
    |---|---|---|
    |DFU2005|Total length 600 mm|1|
    |DFU2005|Total length 650 mm|1|
    |DFU2005|Total length 700 mm|1|

### Actuators

* Servos     

    |Reference|Descr.|Amount|Link|
    |---|---|---|---|
    |ECMA-C20807RS|AC Servo Motor 750W ECMA-C20807RS|2|https://www.damencnc.com/en/ac-servo-motor-750w-ecma-c20807rs/a815|
    |ECMA-C20807SS|AC Servo Motor 750W with Brake ECMA-C20807SS|1|https://www.damencnc.com/en/ac-servo-motor-750w-with-brake-ecma-c20807ss/a816|

* Spindle       

    https://vallder.com/product/atc-spindle-3-0kw/

### Sensors


## Assemblies



## Epoxy Concrete pouring

Stef states "```258kg of silimix and 28,5kg epoxy```". 

## Reasoning

The useful lengths for the x axis and y axis are : 

Thread - nut length * security coefficient in %

* 700mm screw   

    For the 700mm screw, 620mm is threaded, and the nut is 86mm

    620 - 86 = 534 mm -> 520mm usable for the table dimensions

    but for the x axis, it would be better to keep some distance for the toolchanger -> 120 mm on the side

    ```400 mm left ```


* 650mm screw       

    For the 650mm screw, 570mm is threaded, and the nut is 86mm

    570 - 86 = 484 mm -> ```460mm usable``` for the table dimensions

for the x axis (longitudinal), the ballscrew can be shorter, but for the y axis, since the spindle is narrower than the table, the screw has to be closer to the length of the rails.

750 rail -> 650 screw (484) -> 484/750 = 0.64 -> 5% more so it should be the longitudinal side but not that much of a gain.
900 rail -> 700 screw (534) -> 534/900 = 0.59 -> 

