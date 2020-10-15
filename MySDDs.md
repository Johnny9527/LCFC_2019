## Solution Design Documents (SDDs)

Before I joined the LCFC, our company has already run a Windchill PLM system for years, and it is mainly used in the business group
of Notebook manufacturing. In this repository, I will called this old PLM system as "NB-PLM". As our company want to expand business
into Server industry, therefore, the goal of my team was to establish a new PLM that will mainly focus on the business group of Server
manufacturing, and we called this new PLM system as "Server-PLM". In this repository, I will share parts of the internal SDDs that I
made in LCFC.

One of the solutions that I discussed and finalised with internal users was called "EDM-A40", and this solution was mainly focus on 
customising an brand new working process and document workflow for the Taipei-Server team.


![](https://github.com/Johnny9527/LCFC_2019/blob/main/Pictures/EDMA40_Process.png)

↑ The EDM-A40 Process

As the picture shows above, our key users of this requirement was the EE (Electronic Engineer) department under the Taipei-Server
team. They wanted us (Server-PLM team) to create a customized working process on Server-PLM in order to meet their requirement.

After a few internal meetings, I designed the EDM-A40 process, which contained both OOTB (Windchill standard functions) and customized
functions.

In this process, firstly, the EEs create an A40 document on the Server-PLM system then pass it to the layout team. Subsequently, the
engineers of layout team have to upload related files according to its details. After that, the customized functions will take care
the rest of the works under specific conditions.


![](https://github.com/Johnny9527/LCFC_2019/blob/main/Pictures/PracticeDefinition_.png)

↑ Details of every steps of the EDM-A40 process

