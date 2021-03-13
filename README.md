# UFOs

## Overview of Project: 
Explain the purpose of this analysis.
Dana asked for help to create a webpage that sifts through thousands of datapoints on UFOs, with recordings of sightings logging info such as date of sighting, location, duration, shape and more. We built a webpage to sort listings by date, but then Dana wanted it to be a bit more dynamic––filtering additionally by city, state, country, and shape.

## Results: 
### How To Use The Table Effectively
This updated table is quite handy to see how many sightings happened on a particular date, filtered by geographic areas and/or by their particular shape. In order to use the filtered table effectively, one must choose a date in which to conduct the search, or filter, and hit 'enter'. Without a date prescribed, a result simply will not work.
![Table_noFilter](https://github.com/andeevosters/Pewlett_Hackard_Analysis/blob/main/Visuals/unique_titles_90398.png)

Once a date is chosen, you can further refine your table by entering any or all of the other filters as desired, and hitting 'enter' after the last filter inputted. For instance, you might be interested to know how many sightings took place on January 13, 2010 in the United States (answer = 3).
[Table_USfilter] 

Upon further filtering, we see that one of those was round.
[Table_USshapeFilter]


## Summary: 
This table provides a great alternative to parsing through rows upon rows of data points to find the results you might be looking for. As the table stands, it this webpage has some drawbacks, which are addressed below, along with a few recommendations on how to improve the webpage for a more effective sighting-parsing experience.

### Drawback
The filter requires searching by a particular date, but there may be a myriad of reasons to search a list of UFO sightings for reasons other than to see the number, locations, and types of sightings on any given day. Perhaps someone might want to see how many sightings were triangular? Perhaps there is a trend of where triangular appearances take place (maybe they're all along the east coast, for example). It is likely that people would like to do a quick search of the sightings in or near their hometown, as another example of a search not based on a date.

### Additional Recommendations
* Instead of making 'datetime' a fixed filter, it could become an optional filter, just like 'city', state', country', and 'shape'. This would allow users to search any which way they choose.

* By allowing inputs not to be case-sensitive, or to be given drop-down menus for their search would likely increase the number of results people are given with a search. 
	* This is because the data is all saved as lower-case, and proper names are not typically searched that way. 
	* In regards to a drop-down, this would help people to know not to search for the United States as such, but rather as "us".
	* Alternatively, the data itself could be cleaned up and formatted for optimal search results.
