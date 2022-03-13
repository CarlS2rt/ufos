# UFO Analysis

## Project Overview

This project creates an interactive, searchable web interface for researching UFO sightings. A data table of sighting details is loaded into the page and can be searched by end-users to see specific results based on various search criteria. 

## Results

Searching the data table is achieved through search filters added for various criteria. 

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/table_filter.png)

The table filters are all dynamic in that they will each update the table automatically upon entering and removing filter criteria. Results can then be tailored to the interests of the end-user. Searches can be performed on specific dates:

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/date_filter.png)

Searches can also be refined by location, including any combination of city, state, and country:

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/city_filter.png)

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/state_filter.png)

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/country_filter.png)

In addition to searching by time and location specifications, the end-user can also search by the shape of the UFO seen in the table entry:

![](https://raw.githubusercontent.com/CarlS2rt/ufos/main/images/shapes_filter.png)

As evidenced through the examples searches above, the search process is very user friendly to help end-users get to the data in which they are most interested.

## Summary

Overall, the web interface is very usable and aesthetically appealing. The main drawback of the current iteration of the page is that the search filters are case-sensitive and required exact matches to display results. Additional recommendations for development are as follows:

- create filters to allow near-matches and that ignore formatting and capitalization differences between the filter input and the table.
- the table could also benefit from ascending/descending sort options to display the oldest or newest dates in the table or to sort alphabetically by a location criteria.
- the webpage could also include a submission form for users to submit their own sightings to add to the table and further UFO research.