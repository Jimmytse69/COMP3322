# COMP3322 Modern Technologies on World Wide Web

## outline: 
* 5 Workshops
* 3 Assignments (will only upload after due day or not upload)
* 1 Project (will only upload after due day or not upload)

### Workshop 1 - HKU Custom Search Page:
* Fundamentals of Web Pages 
* part1: HTML
* part2: CSS 
* part3: Responsive Web Design
* deploy at http://i7.cs.hku.hk/~h3568932/Workshop1/index_WS1.html

### Assignment 1 - restructure and redesign HKU HK Study Webpages [due 28/2 23:59]
* part1: HTML
* correctness; diversity(not abusively using tables); integrity (same header, footer, etc)
* part2: CSS
* select and hover effect using pure CSS; Responsive Web Design; maintainability (single stylesheet)
* part3: peer review
* deploy at https://i7.cs.hku.hk/~c3322b/assign1/h3568932/index.html (require id and pw, for own record only)
* original webpages: https://hkstudy.hku.hk/

### Workshop 2 - retrieves real-time MTR train data via MTR Next Train Open Data API
* part1: Examine MTR Next Train Open Data
* https://data.gov.hk/en-data/dataset/mtr-data2-nexttrain-data
* understant the structure of the returned JSON string and its meaning.
* try to manually composing the request URL and get the data.
* https://rt.data.gov.hk/v1/transport/mtr/getSchedule.php
* (add ?line=[$line]&sta=[$station], where line and station is alias according to document)
* part2: Implement the program
* -HTML:
* fill in selection options for lines and stations
* -<script>(javascript):
* build a "database", list out all stations with asscociated class=[$line]
* check whether user selected different line, if so, switch to corresponding set of stations (addEventListener)
* -AJAX:
* add a fetch() request to request and get data according to different situation, (e.g. Normal, Special, Data Absence)
