# Introduction 

PLANT uml declaration files for [C4-model](https://c4model.com/) styles and objects in puml syntax based on the [following open source project](https://github.com/RicardoNiepel/C4-PlantUML).

Extended by some additional macros for deployment etc. and some style enhancments


# Supported Diagrams

the following diagramms are available:

## System Context & System Landscape diagrams
* Import: `!includeurl https://raw.githubusercontent.com/romanruthofer/c4-puml/master/C4_Context.puml`
* Macros: Person, Person_Ext, System, System_Ext, SystemDb, SystemDb_Ext, Boundary, System_Boundary, Enterprise_Boundary, System_Boundary_Passive

## Container diagram 
based on Context diagram
* Import: `!includeurl https://raw.githubusercontent.com/romanruthofer/c4-puml/master/C4_Container.puml`
* Additional Macros: Container, ContainerDb, Container_Boundary, ContainerPassive, ContainerApp, ContainerDbPassive
## Deplyoment diagram 
based on Container diagram
* Import: `!includeurl !includeurl https://raw.githubusercontent.com/romanruthofer/c4-puml/master/C4_Deployment.puml`
* Additional Macros: Node, NodePassive
## Component diagram
based on Container diagram
* Import: `!includeurl !includeurl https://raw.githubusercontent.com/romanruthofer/c4-puml/master/C4_Component.puml`
* Additional Macros: Component, ComponentDb

## Dynamic diagram 
based on Component diagram
* Import: `!includeurl !includeurl https://raw.githubusercontent.com/romanruthofer/c4-puml/master/C4_Deployment.puml`
* Additional Macros: Interact, Interact_Back

