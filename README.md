# UFO
### Overview of the analysis:
The point of this project was to further narrow downn search results for UFO sightings. The original html
document only allowed us to search sightings by the date which was limiting and didn't allow us to get more specific. We can now search by 
5 different categories to give us more detailed results from the search menu. We made this happen with the 
li code in our index.html file. This piece of code allowed us to create additional search boxes and add them to the "Filter Search" Menu. From there
we were instructed to delete the "Filter Table" button. With the button gone we needed additional code to perform a search based on the input that would return results based on the updated filters. That code was (d3.selectAll("input").on("change", updateFilters);)


## Results:
You perform searches by simply entering which information you want returned within the range. Meaning if we search for something thats not within the search range we will get a null result. If we wanted all the UFO sightings
that took place on the date of 1/1/2010 we would enter this date into the "Enter a Date" search bar.

![FEF80C30-7025-4513-8CAD-3ED4700D0433_4_5005_c](https://user-images.githubusercontent.com/112785655/205192166-0f833d68-01e1-4d6a-b0c1-7a7e1f626f74.jpeg)

Once this is complete we will get every result from 1/1/2010 from there we can further condense our search by entering a city name. Lets say we wanted to see all results from spring valley. We would then enter "spring valley" into the "Enter a city" search bar. With the information entered we can see that the only UFO sighting in spring valley on date 1/1/2010 was 10 minutes long. 
![7C1A75FC-6412-4D2A-B100-DD344FAD990F](https://user-images.githubusercontent.com/112785655/205192684-3bdc209c-f9f0-4b37-bd6a-5c1eeeb9b36a.jpeg)


## Summary:
A drawback of the webpage is that you can't search the duration of the UFO sighting. If the dataset was larger we would likely need this option to further condense our searches. This will likely increase the amount of time it takes the user to find the information they are looking for. Our goal with this
website is to make searches as easy as possible so they user saves time.
My first reccomendation would be to add "Enter a duration" to the menu so users can further identify which results they are looking for. 
