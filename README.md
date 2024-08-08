# Rack Robotics KICAD Templates
Templates for use by Rack Robotics, Inc. & friends

Design rules for JLCPCB PCBs are generated using the [JLCPCB design rules](https://jlcpcb.com/capabilities/pcb-capabilities). 
Design rules for PCBway PCBs are generated using the [PCBway design rules](https://www.pcbway.com/capabilities.html).

# Templates 
The included templates are: 

**Flex PCB Templates** 
- 4-layer 1 oz outer 0.5 oz inner FR4 PCB
- 2-layer 1 oz flex PCB 
- 2-layer 0.5 oz flex PCB
- 1-layer 1 oz aluminum PCB

# How to Use Templates in KiCAD 

To use these templates in KiCAD: 

- clone repo to local directory of choice 
- open KiCAD 
- select 'file' 
- click 'New Project from Template' 
- click 'User Templates
- select the local repo directory
- select your template of interest

A new KiCAD project will be created using the template you have selected. 

# Contribution 

**Rules for Contribution** 
 - ensure that templates follow up-to-date design rules from the indicated fabrication house (JLCPCB,PCBway, ect)
 - ensure that schematic 'page settings' are consistent with existing templates (issue date, revision convention, title, company)
 - ensure that PCB 'board setup' is consistent and accurate (physical setup, board finish, text & graphics, design rules)
 - name templates according to pcb type, layer count, copper weight, and fabrication house (JLCPCB, PCBway, ect)
 - ensure that info.html is updated for each template with the correct information
