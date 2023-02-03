# Plotly_Bellybutton_Biodiversity

## Overview
This project involved creating an interactive dashboard using Javascript and Plotly to investigate, visualize, and potentially analyze data regarding bellybutton biodiversity. The interactive component on the HTML page dashboard is a dropdown list where the user can select the individual ID number of those involved in the study. By selecting this ID number, the visualizations on the screen will change accordingly, showing the data associated with the person whose ID number was selected. 

## Project Background Information
A microbiology researcher is interested in studying proteins from bacteria that can be synthesized to taste like beef, therefore creating a synthetic alternative meat option. Roza, the lead researcher has partnered with an alternative meat startup called "Improbable Beef" to research candidate species for this project. Roza's hypothesis is that certain bacteria found in human bellybuttons, has proteins that can be synthesized to taste like beef - as strange as that may sound! The dashboard created here is drawing from the data she has collected from volunteers who have allowed the lab to collect their bellybutton bacteria. 

<img width="632" alt="Screenshot 2023-02-02 201239" src="https://user-images.githubusercontent.com/114960958/216487442-0bd36d22-4d7b-4c1d-84a6-451de3881247.png">

## Dashboard Details
The interactive component of this dashboard is shown in the top left under the title, "Test Subject ID No." which correlates to the ID number for each volunteer who participated in this research. Surrounding the dropdown menu, there are four panels that change each time a different ID number is selected and reflect the data associated with the person connected to that ID number. 

<img width="107" alt="Screenshot 2023-02-02 201404" src="https://user-images.githubusercontent.com/114960958/216488838-4d37b10a-efed-4cc4-840b-38faf767c7b8.png">

Below the dropdown menu, there is a small panel named "Demographic Info", which shows the basic demographic data associated with the person associated with the ID number selected. To the right of that panel, there is a bar graph, which shows the top ten types of bacteria found in the person whose ID number was selected. 

<img width="241" alt="Screenshot 2023-02-02 201418" src="https://user-images.githubusercontent.com/114960958/216488872-f608fc8b-399b-44e8-af11-bffcc9bcb7ad.png">

Since there are many different kinds of bacteria in one's bellybutton, this dashboard shows the top 10 types of bacteria for each volunteer. Continuing to the right, there is a gauge chart that shows the bellybutton washing frequency for that person. The number of scrubs per week could affect the amount or integrity of the bacteria that the lab can collect, so this data is helpful for the research as well. 


<img width="264" alt="Screenshot 2023-02-02 202411" src="https://user-images.githubusercontent.com/114960958/216488923-d8926647-53b5-49e7-a8a3-7c1f2edf747b.png">

Lastly, below these three panels is a bubble chart showing the amount of bacteria cultures found per sample taken. 

<img width="552" alt="Screenshot 2023-02-02 202427" src="https://user-images.githubusercontent.com/114960958/216488929-37aff881-5a42-42aa-9b9a-7c54caa18b31.png">

## Analysis and Questions
This dashboard is a great tool for the researchers to use in looking at the individual results for each volunteer, when looking at demographic information, top ten bacteria cultures found, scrubbing frequency, and cultures found per sample. However, in creating this dashboard, it is apparent that there is not a way to look at the trends among the whole group. This type of data pull and visualization would be helpful for the research team as they look at the most common bacteria types, for example. Although they can go through each individual and note the data manually, this can be labor intensive and there are other ways that Plotly and JavaScript could be used to portray a dashboard with visuals that show the data trends in the whole group of volunteers, using graphs similar to those in this dashboard (e.g. bar graphs and bubble graphs)
