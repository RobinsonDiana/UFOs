# UFOs
## Project Overview

The objective of this project is to build an interactive webpage for end users to get more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.
## Resources
- Data Source: UFO data
- Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0
## Results
## Search Criteria Procedure
### Index page
The page can be refreshed either by clicking the UFO sightings word or the icon behind it at the top left corner of the page.

![Index page](https://user-images.githubusercontent.com/109990578/197449368-c26e7f97-39a3-4dc4-bae9-7a37db988844.png)


### Filtering by event date

The desired date is entered, the change is detected and the table is updated accordingly.

![filtering ondate](https://user-images.githubusercontent.com/109990578/197450139-ef5b8c03-acd3-4e8f-be14-8f7f0c28ae9b.png)


### Filtering by city

The desired city is entered, the change is detected and the table updated.

![filter by cities](https://user-images.githubusercontent.com/109990578/197450570-4e05f62f-0be3-44ee-9423-ae9636c10556.png)


### Filter by ccountry

The desired country is entered, the change is detected and the table is updated.

![filter by country](https://user-images.githubusercontent.com/109990578/197450967-e2af14ec-ed11-4619-9b9c-b2787b84e908.png)

### Filtering by state and shape
The user enters the desired state and shape(triangle) observed, the changes are detected and the table is updated accordingly.

![filter by shape](https://user-images.githubusercontent.com/109990578/197451405-2a77018e-1eb8-4292-b4e4-317fe3cc2735.png)

Multiple parameters can be filtered.

## Summary
- One constraint of this design is that the filteration process is not flexible to the user.
- A way to address this would be to present drop-down lists including all filter values in place of the input fields.
Each list would need to update after a parameter is selected in any filter.
- Also, a filter clearing button can be added to clear the filter. 
