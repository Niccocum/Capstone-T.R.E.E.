# T.R.E.E. - Terrestrial Risk Evaluation Effort 


Hi, 

We are T.R.E.E three Students from the Neue Fische Advanced Data Analytics bootcamp, that took place between June & September of 2022.  As our graduation project we chose to tackle one of the most pressing issues of our times, climate change and its effect on our environment. 

Therefore, we started the T.R.E.E project. Our goal was to map and analyze Berlin’s tree population, assigning profiles to each tree species found in Berlin’s parks and along its streets. These profiles, deeply rooted in scientific research on trees and environmental hazards, indicate every tree’s ability to withstand ever harsher climate conditions in central Europe due to climate change. 

Combining these profiles with the 800.000 trees that can be found in Berlin Open Datas ‘Baumbestand Berlin’ dataset, we managed to create a precise geospatial map of Berlin and its trees, in which every tree provides an individual datapoint.

These were then clustered to LORs – ‘Lebensweltlich Orientiere Räume’, a clustering method for Berlins city planning authority. Furthermore, we assigned each tree to its closest measuring stations for different environmental factors, for example: temperature, ground water level or precipitation: 

In total we created a 13-item scoring model, based on ecological knowledge in the team and research, that combined specific tree characteristics with weather and climate data as well as measurements on environmental stress factors, to calculate for example a "draught risk" parameter. For now, we decided not to weigh the individual parameters, since the reviewed literature did not provide enough scientific information to base a weighing upon. By looking at tree characteristics and environmental parameters, we were able to calculate normalized risk scores for every single tree. Which, when aggregated the trees in a given LOR, we could then calculate this area's risk score for its tree population. 

In total this resulted in a heatmap indicating the risk for the different areas of the city. Furthermore with every tree awarded it's own risk score, an aditional analyses based on species performance is possible. This shall help stakeholders to better allocate their resources to future proof the tree stock of Berlin. 



<img width="1253" alt="Heatmap" src="https://user-images.githubusercontent.com/107697741/189738713-a032a760-83a7-4510-96f2-42f3c9515ab5.png">

Due to time constraints a validation of the model was not possible, since it would demand in depth cooperation with the Grünflächenamt for real world data on tree health, or additional data gathering. From one location, that we managed to sample it became apparent that further adapting the model would be advised, for example to additionally account for tree age or a weighing of parameters.

As a further project a statistical analyses of the parameters, to identify the ones with the biggest impact, could provide additional insights, which can be used to refine the model.

This work is property of Jannik Hildebrand, Oliver Kurz and Nicola Rudow, if you want to use it please ask for written permission to do so. 
