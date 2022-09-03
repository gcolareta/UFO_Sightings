# UFO_Sightings
JavaScript, CSS, HTML


## Overview
In this project, I built a dynamic webpage that will accept user input to filter a search of UFO sightings. The webpage structure consists of a navigation bar containing a reset link that will clear the filtered results. It has a visually appealing title, a brief article describing the purpose of this project and inviting the users to explore the data and draw conclusions based on facts. The purpose of this visualization project is to raise awareness of the vast amount of evidence that UFOs might be out there.


## Results
Through the search criteria, users can filter the data based on one or multiple search criteria. The search results are then displayed in a table that will update the data based on user input.

For example, if a user enters a date, the table will display all the UFO sightings, from the Java Script array, observed on that date.

<img width="1268" alt="date" src="https://user-images.githubusercontent.com/104762216/188280023-13ca907b-f964-4bb8-bc17-2f6d454bcedb.png">

Users may also want to search by multiple criteria, such as state, country and shape of the sighting. The results will then be filtered and displayed in the table.

<img width="1274" alt="multiple_criteria" src="https://user-images.githubusercontent.com/104762216/188282342-8d0e2f40-f8d9-4b61-ad1a-4391a25b8202.png">


## Summary
Even though this visualization, presents the information in a clear and easy to understand way for users and it takes user's input, one limitation I observed was that the user would need to type in information that is actually in the source file in order to get a search result. For example, if a user wants to get information on sightings that happened in Peru and types "pe" as the country code, the website will return an empty search result. This could be frustrating for the user.

<img width="1276" alt="empty_search" src="https://user-images.githubusercontent.com/104762216/188282668-5f193e00-fdb1-411d-8eed-b05f5d1dff80.png">

To address this issue we could make the state, country, and shape filters a drop-down menu. This way, the user has the information available to select and search at the drop-down of a menu.

Another recommendation would be to allow the user to search for UFO sightings by month. In other words, in the date filter, we currently have a search by a specific date in the format mm/dd/yyyy. I believe that for data analysis purposes, having the option to group UFO sightings by month can reveal interesting trends for further study.

Lastly, in order to make user experience easier to navigate through the page, I would propose to move the "reset search" link, currently at the top of the page, and place it to the right of the "Filtered Search" title. Also, I would rename it "Reset Search" since that is the purpose of the link.
