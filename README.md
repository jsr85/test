---
description: About
---

# Netool 10.7 manual

NETool is a steady-state, near-wellbore, and completion hydraulics simulator. It permits quick execution and for wells to be designed based on optimized production responses from the well. Production parameters are generated as outputs on a case-by-case basis in an independent Results Viewer program: that is, Tubing and Annulus Flow rates and Velocities, Flow into the Annulus and Tubing, and Tubing and Annulus pressures. All results are generated on the basis of a Black Oil formulation for PVT data and reservoir flow modeling, using a Productivity Index \(PI\) model.

### NETool comprises three primary components:

* Model Builder \(preprocessor\)
* Numerical Simulator
* Results Viewer \(post processor\)

### The key characteristics of NETool operation are: 

#### Fast Execution 

You can perform NETool Simulations in a matter of seconds or minutes rather than the hours or days a traditional reservoir simulator requires. Fast execution of simulations allows you to revise well design during the drilling of the well, when time is crucial. A common use of NETool is to revise the completion design based on log data. NETool allows design revision to occur between the time the log data is acquired and the time the completion is run, while maintaining continuous operations on the rig.

#### Easy Data Input 

NETool is set up in such a way that revisions to the geologic model are not required for making well performance calculations based on data acquired during drilling. You can directly enter log data. NETool imports reservoir engineering data sets in common formats, such as Eclipse and Nexus file set format.

#### Complex Well Hydraulics Complex well:

* Simultaneous Tubing and Annulus Flow — Simultaneous solution of flow in the tubing and annulus, between the tubing and annulus, and between the annulus and reservoir. Porous material in the annulus space can also be considered, that is, with a gravel pack or a situation where the open annulus collapses causing the annulus to be filled.
* Automatic Solution of Flow Directions — This allows for design of completions where the flow in the annulus is both up and down the well, opposite direction of flow as in Stinger case. From a design point of view this is an obvious requirement, but is numerically somewhat difficult to achieve.
* Completion Specific Flow Correlations — NETool includes numerous options for the pressure drop through completion components.

#### Modeling Reservoir Flow Using PI Models

Flow from the reservoir \(or into the reservoir in the case of an injection well\) is modeled using various PI models, including Steady State and Semi-Steady State cases. The PI equations used are also affected by the angle of the wellbore deviation.

#### Black Oil Formulation 

The simulator uses a black oil formulation for managing PVT data in either three-phase, two-phase, or single-phase modes.

\*\*\*\*

## Introduction and Theory

* What NETool is and is not designed for. Applications and possible workflows.
* Building a case from wizard, without wizard, Eclipse data import.
* Main input parameters, building a simple ML well, learning to use NETool plots viewer \(compare plots, export, etc\).
* Using different completion combinations \(liners, packers, screens, ICDs\).
* Logs and deviation survey import, PLT analysis. 

## Exercises

* ‘My first well’
* Build a Case from Scratch with a “Wizard”
* Adding a lateral to an existing mainbore
* Directional survey and log import
* PLT analysis and History Matching
* Perforation Shot Density Sensitivity Balancing inflow profiles with Screens and ICD \(screen+bp vs. screen+ICD\)
* Introduction to Inflow Control Devices: theory and applications.
* ICD types, their purpose and difference.
* Common production workflows. Modeling well as a whole without nodal analysis.
* Exporting NETool well designs into Eclipse\Nexus.
* ICD, ICV, zonal isolation
* Sand erosion.
* Dumpflood
* ESP
* Gas lift
* Wellhead choke and liquid loading
* Model calibration
* External plots.

