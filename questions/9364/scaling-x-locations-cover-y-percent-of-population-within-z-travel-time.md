## Scaling: X locations cover Y percent of population within Z travel time

- posted by: [Alex I](https://stackexchange.com/users/2048845/alex-i) on 2016-05-31
- tagged: `business-model`, `data`
- score: 4

<p>I'm doing some initial feasibility planning for a business which is location-based (something that has fixed locations/stores, and the customer has to come to it).  Regardless of the question of <em>where</em> to put the stores, I'd like to be able to figure out the number of locations needed for any particular degree of market coverage, assuming some maximum travel time (assuming the locations are perfectly placed).  For example, is 50% of the population of the US within 30 minutes travel of (let's) say 1000 locations?  Is there a database or software package that can conveniently do this type of modelling?  I'm also very interested in the same data for other countries/regions, eg Europe, China, India.</p>



## Answer 9369

- posted by: [Mowzer](https://stackexchange.com/users/1803081/mowzer) on 2016-05-31
- score: 2

<p>You can (rough order of magnitude) ROOM estimate by taking the total amount of area you wish to cover (say, the total land mass of the country or region) and divide that number by the total coverage area of an average retail <em>point</em>.</p>

<p>Total points necessary &equals; Percentage of population you wish to cover &times; Total coverage area &div;  Coverage area of average retail point</p>

<p>Area of average retail point &equals; &pi; &times; r<sup>2</sup>,</p>

<p>where r is the radius of the area you wish each point to cover. Say, 30 miles, in your example.</p>

<p>If there are high population center metro areas as well as rural areas, and you want to improve the accuracy of your estimation, just apply the formula to each metro area individually. Then add up the results. In that case, you would probably want to build a spreadsheet to keep track of all the metro areas and the calculations for each.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
