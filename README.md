<sup>Project renamed from V-JX to VJX in December 2022 </sup>

# Project VJX
A fast glider for slopes and F3F competition. 

![VJX](images/V-JX_perspective_view.jpg "VJX perspective view")

VJX is a common project of Jochen Guenzel and Mario Perner where Jochen focuses on aerodynamic design and Mario on engineering and building of the model. 

Within this repository, we want to make a "full stack description" - i.e. from the aerodynamic design to the final build out of molds. As far as possible, we will make the calculations and plans available "open source" and thus also invite to a lively discussion, in which we all will hopefully be a bit smarter in the end.

#### Update 2024

A new wing, called [VJX.glide](wing.glide/README.md), is designed which complements the original VJX for medium to low conditions.

#### Update 2025

The original VJX wing has been revised and a little bit tamed to achieve better high lift capabilities. The new wing is called [VJX.race](wing.race/README.md). 

Have a look at [VJX Project Overview](#vjx-project-overview) for more information about the different developments and their current state. 

## Chapters

#### [Preliminary remarks on the procedure](#preliminary-remarks-on-the-procedure)

#### [Wing](wing/design/wing_design_1.md)
* [Design - Airfoil sections, planform, control surfaces](wing/design/wing_design_1.md) 
* [CAD](https://www.rc-network.de/threads/projekt-v-jx.11886149/post-12199653) - on RCN (de)
* [Molds and Build](https://www.rc-network.de/threads/projekt-v-jx.11886149/post-12201770) - on RCN (de)

#### [Wing VJX.glide](wing.glide/README.md)
#### [Wing VJX.race](wing.race/README.md)

####	[Tail](tail/tail_design.md)
* [Design - Tail, rudder](tail/tail_design.md) 
* [CAD and Molds](https://www.rc-network.de/threads/projekt-v-jx.11886149/post-12285083) - on RCN (de)

#### [Fuselage](fuselage/fuselage_design.md) 
* [Design - Outline, CAD](fuselage/fuselage_design.md) 
* [Molds](https://www.rc-network.de/threads/projekt-v-jx.11886149/post-12289032) - on RCN (de)

#### [Flight Experiences](#flight-experience)
#### [Project Overview](#vjx-project-overview)
#### [History](#project-history)
#### [Acknowledgement](#acknowledgements)


![VJX](images/V-JX_front_view.jpg "VJX perspective view")
## Preliminary remarks on the procedure

The approach with VJX is somehow atypical for the design of a new model. 

It all started with the [JX-GS airfoil family](https://github.com/jxjo/Airfoils/tree/main/JX-GS)   , which was developed specifically for F3F, but was not based on a specific model design.  In the course of time, however, thoughts matured as to what an optimal wing for this airfoil family should look like.  Which eventually resulted in a first wing design. 

Since a "proof of concept" of this wing design should be carried out as early as possible, the complete design of a new model was out of the question.   With a "test vehicle", the new wing should be put into the air as quickly as possible in order to test its performance. 

We opted for the ["Vantage"](https://ccm.in.ua/en/catalog/r-c-models/vantage/), Mario's current design for F3F/F3B.

The Vantage has perfect dimensions of a current F3F model, which makes the fuselage and tail very well suited to be equipped with a new wing module to evaluate the characteristics of VJX - also in comparison. 

In the development of a new plane, such a separate consideration of the individual components wing, tail and fuselage can be dangerous. The mutual interaction is too complex to achieve an optimized overall design. On the other hand, over the past 30 years, with countless great designs, a narrow design corridor has emerged as to what an optimal model for the F3F flight task should look like. 

Even if it may not be possible to achieve the last bit of improvement by looking at the main components separately, the procedure in the sense of "separation of concerns" of the individual components simplifies the overall development immensely.  As long as you move in the described design corridor, the probability of a "wrong design" is relatively low...

![Separation of concerns](images/Separation_of_concerns.png "Separation of concerns")

A further aspect or guideline for the aerodynamic design, including the profile structure, was: Wherever possible and sensible, a more defensive solution with a "wide optimum" was given preference over exhaustion in a narrow area. 

![Broad optimum](images/Broad_optimum.png "Broad optimum")

The danger of not hitting the "sweet spot" of a narrow optimum under competition flight conditions and thus having to accept significant performance losses far outweighs the prospect of minimal profits compared to a solution with a broad optimum.   

### Design Goals of VJX

"Pretty daring" you could say. To get involved in the round of excellent and mature F3F models such as the Freestylers, Pitbulls, Shintos, Vantage and the numerous other top models. To be even "better" in the end!

The key is certainly that there can no longer be a one-dimensional "better" in the current top models. Each model is practically unbeatable on its own. 

The difference lies in the specific characteristics of the models, which in their sum are decisive for whether a pilot controls an "optimal sports device" for him under certain conditions.

The property profile of VJX has been defined as follows with a comparative classification between o (=weak) and ooooo (=top).

|  Aspect                     | Score   |
|-----------------------------|---------|
| Speed range in F3F times    |         |
| ... over 50s			      |ooo     | 
| ... 40s – 50s			      |oooo    |
| ... below 40s			      |ooooo   |
| Acceleration				  |ooooo   |
| Minimum curve radius		  |ooo     |
| Speed in turn				  |ooooo   |
| Maneuverability 			  |ooooo   |
| Flight stability			  |oooo    |
| Good nature 	    		  |ooooo   |

Or more colloquially: "With good lift on the slope, it should be a fast, agile at the same time good-natured rocket ...".

The goal was set.  Now it's time to work!  😉

We'll start with the [Wing Design...](wing/design/wing_design_1.md) 

---

## Flight Experience

<img src="./images/V-JX_at_WC2022_2.jpg" width="45%" /> <img src="./images/V-JX_at_WC2022_3.jpg" width="45%" />
<p align="left">
<sup>VJX prototype at F3F WC 2022 with Vantage fuselage and tail flown by Thorsten Folkers - Photos courtesy Pierre Rondel </sup>
</p>

[<img src="https://img.youtube.com/vi/vzmBOqD7ym0/maxresdefault.jpg" width="45%" />](https://youtu.be/vzmBOqD7ym0)
[<img src="https://img.youtube.com/vi/EWIMaU6y8Lc/maxresdefault.jpg" width="45%" />](https://youtu.be/EWIMaU6y8Lc)
<p align="left">
<sup>VJX on a training flight and on WC round 1- Pilot Thorsten Folkers - Click to see on Youtube </sup>
</p>

First flight experiences up to now showed a very close behavior of VJX to the property profile which was defined when starting the project. 

VJX likes a wider, speed and energy oriented flight style. The faster, the better... Pilots emphasize the excellent acceleration when lift load is going towards 0 (Cl getting close to 0). 

Crucial for good flight results is the intensive use of flaps - both for the static deflection within a certain flight phase (bowling, enter course, on course) and also dynamically using snap flap to optimize for the current Cl load (curve acceleration). 
Although VJX is easy to fly being good-natured, VJX isn't "everybody darling" - it want's to be tweaked from pilots who want to get the best out of the model in regard to a certain flight style. This said, it's fascinating what Thorsten got out of VJX at F3F WC 2022 in such a short time of preparation!

## Project History 
- 2021 - June: Project start 
- 2021 - October: First prototype wing with vantage fuselage abd tail 
- 2022 - April: Flight evaluations started (brought some delay) 
- 2022 - July: Restart of flight evaluations with Tobias Reik and Thorsten Folkers
- 2022 - September: First F3F contest participation in Denmark / Sealand
- 2022 - October: F3F WC - several rounds flown by Thorsten Folkers
- 2024 - New VJX.glide for medium to low conditions
- 2025 - New VJX.race, a revision of the original VJX for medium to fast conditions  

## VJX Project Overview

The table shows the VJX family tree as of November 2025.

![VJX Project](images/VJX_project_overview.png)

to be continued... 

## Acknowledgements 

What would we do without great persons and their awesome contributions?
-	Mark Drela - xfoil
-	André Deperrois - Xflr5
-	Frank Ranis - FLZ_vortex 
-	Daniel Prosser -  Xoptfoil
-	and many others... 

A special thank you to my patient punching partners Tobias Schill, Peter Wick, Matthias Boese.

Have Fun!

Jochen Guenzel & Mario Perner 

![VJX](images/V-JX_top_view.jpg "VJX perspective view")

