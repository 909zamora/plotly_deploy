# plotly_deploy

### Overview
In this challenge, I built a Biodiversity dashboard that pulled data from a json file and visualized it using html/css/js files. The visualization would display different a person's ID number that was associated with the top 10 bacteria in their belly button. The data from the json file contained information regarding the person's Ethnicity / Gender / Age / Location / BB Types / Washing frequency, all while using an ID number to keep their information confidential.

### Process & Coding
HTML - Brought everything together by referencing different scripts. 
-The script for the "sample.json" file imported the json data needed to power the charts/graphs & visualizations on the html page. 
-"Style.css" script provided the background color and the image background for the title. 
-"charts.js" script utilized d3 to allow the end user to use a selector for the drop down filters. Also used for loops to retrieve the sample data, integrating the append / text / property values with the selector. It also utilized Plotly in order to build bar data / Bubble data / Gauge Data


### Summary
The displays on the HTML graphed the bacteria cultures, showed a gauge that displayed the washing Frequency, and graphed the top 10 bacteria in that person's Belly Button. The below is an example of Test Subject ID #955
![image](https://user-images.githubusercontent.com/80786853/134571985-ea872377-e502-492a-91b1-f4c0f17c1730.png)
