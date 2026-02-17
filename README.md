# zapit-CAD

Zapit is a random-access spatio-temporally precise scanning system for optogenetics experiments. The following consists of resources on the parts used, CAD models for their construction and instructions for assembly. See here for the paper (), and here for the [main page](https://github.com/Zapit-Optostim)


See the [Parts List](Parts_List.md) for a list of parts required for constructing Zapit.



The CAD models show you each part needed (where available) to construct the system and a rendering of how these pieces should be put together. 

The orientation of the parts are not set in stone, and therefore do not have to be set exactly as they are in these models. However,  the 'order' of pieces is very important, and it helps to think about this best in terms of the direction of the light path from the laser (see Fig. 1a in the paper to help with visualisation). Additionally, the distance between parts is dependent on the objective and tube lenses you use for the distance needed from your sample. Please get in touch if you have trouble finding the right combination for your experiments. 

We also have adaptor parts for each laser in the 'Thorlabs-parts' folder to connect the laser to Thorlabs parts, which are the only custom part as part of this system design. These parts have worked for us but you are free to design and machine your own. We recommend getting these adaptor plates CNC milled, rather than 3D printed, as depending on your stimulation protocol, these lasers are prone to overheating, which may turn your laser off automatically within an experiment (such as with the Obis lasers). These parts are also only appropriate if you are using the laser without their corresponding heatsink. If you are using the heatsink, you will have to design your own part to attach both the laser and heatsink. 

<img src="https://github.com/Zapit-Optostim/thorlabs-version/blob/main/Screenshot%202026-01-12%20141439.png"> 

We are keen to help others build the system, so if you feel you lack information please make contact via GitHub and we will get you up and running. 

If you need additionaly sound-proofing, you can build the custom enclosure, which is found [here](https://github.com/Zapit-Optostim/zapit_CAD)
