ShoreLineEastGTFS
=================

GTFS schedule data for Connecticut's [Shore Line East RR](http://www.shorelineeast.com/index.php).
Also includes some Amtrak trains listed in the SLE schedule that accept SLE monthly tickets.

Created on a Saturday night, so guarantees of accuracy, but passed Google's GTFS
Validation tools.

Please feel free to make edits and keep it up-to-date.

Current calendars are valid through 31 Dec 2013, with exceptions for all holidays listed
on SLE's website.

**No Shapes.txt, nor fare implementations as of yet.**

The "mnrredundancy" branch has SLE #1610 removed from trips.txt, and all the
New Haven Union Station (NHU) stops removed from stop_times.txt. If used in conjunction
with [Metro-North's GTFS](http://www.mta.info/developers/download.html), trips can be 
combined.