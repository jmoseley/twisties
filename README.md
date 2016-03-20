# twisties
A map routing program that produces "twisty" routes, preferred by motorcycles and other driving connoisseurs.

# Design Ideas
Current mapping solutions (such as Google maps) use pre-processing to speed up routing queries by dividing maps into detail layers (ie side streets, main roads, and highways), then routing accordingly within. A similar model could work in this instance, however the grouping of detail would not be based on speed/convenience of travel/time/distance but road preference (based on a "fun" factor) and other factors after.

http://stackoverflow.com/questions/430142/what-algorithms-compute-directions-from-point-a-to-point-b-on-a-map

## Fun Factor
The fun factor will need to be a heuristic based algorithm looking at factors like twistiness (related to delta of slope in the curves of the road), traffic, and road quality.

