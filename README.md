# UFOs

![nasa](https://user-images.githubusercontent.com/90135381/150019283-f1500cd9-ed65-481a-96ca-598a19851725.jpg)


                          Figutre 1: NASA image obtained from website


***RESOURCES*** JavaScript, Bootstrap, HTML, CSS, D3.js, VSC, NASA website and images.




***OVERVIEW***
The purpose of this challenge was to help Dana build an HTML page,  access information from a JS data.js file, stored as an array, and to create an interactive website to search UFO sightings. In order to create the HTML webpage, the following had to be completed: 
1. remove list element creating the button
2. replace the handleclick() function to save element, value and ID of the altered filter 
3. create a new function that loops through the dataset and only keeps data per the search criteria
4. create empty filters variable, replace handleclick() with updateFilters()
5. add filterTable() to filter the table value with entered values
6. listen for events so that it detects a change and calls the updateFilters() function, which saves the      element, value and ID of the filter
7. use D3.select() to save the element changed
8. write if-else statements to check if value was changed
9. clear element from filters variable
10. create and code for a filterTable() function
11. loop through and store the data matching the filters value
12. incorporate both for interactive table


***RESULTS***

In the figures below, it can be ascertained that information regarding various elements could be obtained via the webpage interactive filters for date, city, state, country and shape in order for Dana to search through UFO sightings instances. In Figure 3, Dana merely typed in the state code for texas and the table data was listed for sightings in that state. In order for Dana to research Texas sightings specificaly on 1/10/2010, she just had to add the date in conjunction with the state of Texas (Figure: 4). In Figure 5, in order to obtain circular UFO sightings, Dana entered circle in the shape tab. In order to continue searching additional variables, the previous text had to be deleted and a new element was then typed.



<img width="1440" alt="challenge pic" src="https://user-images.githubusercontent.com/90135381/150019106-d65f5d56-5ace-451c-819c-d81c2958d00e.png">


          
                           Figure 2: Webpage Introduction    
          
 
          
          
<img width="1440" alt="filterTable tx" src="https://user-images.githubusercontent.com/90135381/150208775-8a43d0ea-6c48-42cb-a6db-406a46100bfe.png">



                           Figure 3: filterTable "Texas" (tx) with code ref




<img width="1440" alt="filterTable tx, 1:10:2010" src="https://user-images.githubusercontent.com/90135381/150208796-8e2eab9b-2e56-46cc-9b40-4913b0553329.png">



                          Figure 4: filterTable "Texas", "1/10/2020" with code ref




<img width="1440" alt="filterTable circle" src="https://user-images.githubusercontent.com/90135381/150208816-e5073601-8699-4c94-b989-f66e5ce71816.png">



                          Figure 5: filterTable "circle" with code ref






***SUMMARY***

In conclusion, a table was successfully created via HTML and JavaScript, with graphics and an interactive table. One of the primary downfalls of this webpage is that the text requirement is case sensitive, as seen in Figure 6. Both "EL CAJON" and "CA" were entered in UPPERCASE and a subsequent blank table resulted.

<img width="1440" alt="filterTable-case sensitivity limitation" src="https://user-images.githubusercontent.com/90135381/150211932-a5683849-10c8-42dd-9b41-e8a90b0e8825.png">



    Figure 6: filterTable with case sensitivity limitations "EL CAJON", "CA" with code ref




The two recommendations for improving the website are as follows:

1. Perhaps the code could be altered to accomodate for the case sensitive requirements regarding the text search boxes, as this could portray mis-information due to resultant blank table space.

2. 

***REFERENCES***.  BCS, Google, StackOverflow, GitHub
