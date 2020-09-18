# Get in IT - Travelling Salesman Challenge Problem

This notebook is part of a coding challenge sponsored by get-in-IT and msg. The task is as follows: 

"Ein Foto vor dem Kölner Dom schießen, mal wieder eine Nürnberger Bratwurst essen und ein Abstecher zum Viktualienmarkt in München ist bestimmt auch drin – aber das funktioniert nur bei guter Planung. Solange Dienstreisen noch vermieden werden sollten, hast Du genug Zeit, um Deine Reiseroute auszuarbeiten.

In den letzten Monaten hast Du mit Deinem Team von msg an einem neuen Machine Learning-Framework gearbeitet. Du wurdest vom Team ausgewählt, das Know-How in allen 21 deutschen msg-Standorten an alle Kollegen weiterzugeben. Aber welche Reiseroute ist optimal, um möglichst effizient von einem Standort zum anderen zu kommen?"

The target is to reach the 21 German msg-sites with the shortest route possible.

https://www.get-in-it.de/coding-challenge?lp=true?utm_source=magazin&utm_medium=advertorial&utm_campaign=coding-challenge-2020

The creation of this route has been achieved with Googles OR Solver. First I created a distance matrix with all possible street distances. Then it has been run through the OR Solver which used a strategy called PATH_CHEAPEST_ARC: "Starting from a route "start" node, connect it to the node which produces the cheapest route segment, then extend the route by iterating on the last node added to the route." More info here: https://developers.google.com/optimization/routing/routing_options. 

![Solution](/Solution.JPG)
Format: ![Alt Text](url)

## Please open "Get_In_IT_Travelling_Salesman_Problem-publish.ipynb"

## You need an API key to run the routing, you can get one here: https://openrouteservice.org/

Update: I did not finished in first place but received some feedback from msg. They told me that the code was very well-written and structured. Some issues they pointed out. My code finished among the top 5. 
