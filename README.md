# UFOs

## Overview of Project

The purpose of this project is to create a concise webpage with information about UFOs (Unidentified Flying Objects). This webpage contains an article about the UFOs and a table containing a lot of information about UFO sightings such as the date, city, state, country and shape of the UFO sightings. Originally this website had a single filter for the table of the date but a recent update to the website added more filters for the table. All filter bars have a default to show what to search in each filter. This website was created using JavaScript, HTML and CSS for styling.

## Results

This website is fairly basic but allows users to filter the results in the table to look for more specific results or nothing can be filtered and the entire table can be viewed. All search results must be in lowercase letters in order for the filters to work since that is how the data is formatted. Below is how the filter bars appear with their default results inside.
![Default Filter Results](https://github.com/likenberry/UFOs/blob/main/Resources/Default_filters.png)
The user simply has to type their search into one or more of the filter bars and hit the enter key. The table will then display the results that fit the entered criteria. Below is an example of a search for UFOs in the state of Florida ("fl") and "unknown" as the Shape.
![Example Search Results](https://github.com/likenberry/UFOs/blob/main/Resources/Example_search.png)
Finally this is an example of the search results in the table when using a single filter, in this case "tx" (Texas) was entered into the State filter.
![Texas Search Results](https://github.com/likenberry/UFOs/blob/main/Resources/TX_search.png)

## Summary

### Drawbacks to Design

- With the addition of more filters, the user can now search for a very specific UFO sighting this also allows for more errors in the results if there are any labeling errors in the raw data. Troubleshooting this would require doing a deep dive into the data which might be not be worth the time and effort it would take to fix any errors. - The entries also have to be case specific so entering capital letters in any of the filter search bars will not return results since all of the data is in lowercase letters. The table also has to be manually reset when search criteria are entered. - - Another drawback to this webpage is that there is no place for user input such as a suggestions box for further improvements or new articles or relevant information. - - - Finally only a single result can be entered in each filter meaning that if a user wanted to look at all of the UFO sightings in the states of California and Texas, they would have to search for California sightings and then Texas.

### Future Recommendations

- While this webiste is a great source of information for general information about UFOs and has the ability to filter and search for sightings, the sightings will remain static so it might be a good idea to have a place on the website where users could enter their own UFO sightings to be added to the table. This would allow the webpage to remain relevant with updated sightings.
- Another recommendation for this webpage would be to include more visual evidence such as pictures or drawings of UFOs which might allow users identify more potential UFOs in the future.
- One last recommendation for this webpage would be to include some very basic plots with summary information regarding the most common shape, city, country, state, and date of UFOs sightings which might give insight into locations for future sightings or the most common types of UFOs.

## Resources

- Data: data.js
- Software: Visual Studio Code 1.62.3, JavaScript, html, CSS
