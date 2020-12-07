# UFO Sightings on Multiple Criteria

## Overview

The purpose of this project is to develop a site allowing a table built from data imported from a javascript object to be filtered using multiple criteria input by the site user. The filtered table will display as soon as the user confirms the input of a filter (adds a filter value and presses enter).

## Results

![Unfiltered Table](https://github.com/MattK1454/UFOs/blob/main/static/images/Unfiltered%20Table.png)

When the user initially loads the page, the table containing all of the data from the javascript object will be loaded. See above.

![Table with one filter](https://github.com/MattK1454/UFOs/blob/main/static/images/1%20filter%20table.png)

Using the filter inputs provided, the user can enter a desired vaule for a specific filter and then press enter. Once the user pressses "Enter", the table will be scanned for all the value matching the specific filters entered value. In the example above, the value "1/1/2010" was entered into the "Date" filter. Once the Enter button was pushed, all of the rows in the table had their "date" column scanned and the rows that did not contain a match were filtered out to produce the table shown above.

![Table with two filters](https://github.com/MattK1454/UFOs/blob/main/static/images/2%20filter%20table.png)

The user can apply multiple filters by applying an additional fiter to an already filtered table. This is done by entering a value in an additional filter field after one or more filters have already been applied to the table. In the example above, the table was intially filtered for the date of "1/1/2010". After the date filter was confirmed and the table filtered, a value for the "City" filter was entered and confirmed. This resulted in the table shown above.

__Note: Each time the page is refreshed, the entire data set will be loaded and produce the complete unfiltered table.__


## Summary

Overall, the added filtering allows for the user to narrow down the list of sightings to specific criteria. One draw back is:
* The user would have to already know what they were looking for in order to achieve maximum benefit from the filter system.

Two possible additions to the site might be:

* Make it so the filters can all be entered at one time and then a search button can be pressed so that multiple filters can be applied at the same time not just one after the other.
* Adding a comments filter option so the user could filter based on descriptions of an event, helping them further filter the table for their desired needs.

## References

1. Module 11 Challenge. (n.d.). Retrieved December 06, 2020, from https://courses.bootcampspot.com/courses/453/assignments/5576
