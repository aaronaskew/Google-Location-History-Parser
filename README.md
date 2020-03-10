# Community Legal Services [Fall-2016]

This is a Hack4Impact Project for Community Legal Services. Try it out [here](http://hack4impact.github.io/cls).

## Team Members
* Krishna Bharathala (Project Manager)
* Abhinav Suri (Technical Lead)
* Santiago Buenahora
* Rachel Hong
* Katie Jiang
* Daniel Zhang

## Project

This app processes millions of Google Location data points into a CSV Files based on "bounding boxes" (i.e. ranges of time within regions of interest). The project is intended for use in worker dispute cases.

## Fork changelog [Mar 10, 2020]

* Adjustments for (new!?) Location History json data structure (couldn't find details on a data format change from google since July 2019, but the json parsing was failing for me)
* Auto set default name for each new bounding box
* New data export format (week column added rather than periodic weekly totals row - this allows consistent data format for each row and the use of a pivot table in Google Sheets / Excel to generate weekly summaries)
* Results modal now shows HTML table of results - TBD: does this cause issues for HUGE datasets? Might need to be a checkbox option to enable for smaller data sets.
* Minor content and layout updates, (unwired multi-step modal (not working!?))

## Demos

### Tutorial for downloading your location data
![](media/tutorial.gif)

### Uploading your location data
![](media/upload.gif)

### Creating bounding boxes
![](media/bounding_box.gif)

### Submitting your data and creating CSV
![](media/submit_csv.gif)



