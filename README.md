# UFOs

## Overview
The purpose of this project is to create a dynamic webpage showcasing a catelog of UFO sightings from various cities and states. This catelog will be shown in table form which may be filtered by any combination of:
- date
- city
- state
- country
- shape

## Results
Operation of the website is fairly straight forward if careful attention is paid to formatting your searches. Below is an example of a properly formatted search result:


<img width="1437" alt="search_results" src="https://user-images.githubusercontent.com/35434608/186772456-1a948ad7-6c6f-4671-abbd-ca978c6c2b89.png">


First choose a filter to start, type your search in the field provided, and the table will filter results as soon as you hit the enter key, or click away to anywhere else on the page. Proper formatting for each type of filter will be shown below.

Note: if the page is refreshed or reloaded, all filters will be removed and the table will return to its unfiltered state.

### Formatting searches
Here is a guide to properly format each type of filter:

- date: m/d/yyyy. There are no leading zeros in the dates, and date ranges from 1/1/2010 to 1/13/2010
- city: Must be all lower case, e.g., "benton"
- state: All lower case, two letter abbreviation, e.g., "ar".
- country: All lower case, two letter abbreviation, e.g., "us".
- shape: also lower case.

The input boxes have placeholder text to remind you of correct formatting as shown below:


<img width="373" alt="search_criteria" src="https://user-images.githubusercontent.com/35434608/186771724-704ff71b-7f13-4712-8185-83e2823541f0.png">


If a search is in the wrong format, there is a misspelling, or there are no results with your requested filters, you will see an empty table.


## Summary
An obvious drawback of this design is fragility of the filter function. Two improvements I would suggest are 
* More flexibility in formatting searches, the ability to capitalize cities, or full spelling of states for instance.

* Another improvement could be drop down menus that popup once you begin to type in a box to autocomplete the search. This would give you an idea of what results are available without you having to completely search your interest and come up with an empty table.
