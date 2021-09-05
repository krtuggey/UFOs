# UFOs
Creating a webpage and dynamic table with JavaScript
 
#### Overview
After developing a working webpage to share information about UFO sightings, it's time to make the webpage more interactive using additional table filters. I've added four more filter options into the html code so the user has multiple criteria to choose from when visiting the webpage. Additionally, the original functions created for the webpage have been revamped to process multiple filters and "listen" to any changes made by the user.

#### Resources
- Data source: data.js
- Using: Visual Studio Code 1.58, JavaScript, HTML, CSS

#### Results
The first version of the webpage offered one filter option by date. Now, there are five criteria available to the user. Without any filters applied, the complete data table is presented.

![Unfiltered table](https://user-images.githubusercontent.com/84139177/132138557-d2c09fa8-16e3-4e5c-ac4e-636df934422e.png)

Let's say our user is looking for chevron shapes and Texas sightings. The user can enter "tx" into the state field and hit enter to find all of the sighting in Texas.

![Texas](https://user-images.githubusercontent.com/84139177/132138738-59db5201-ed59-4471-b21e-0e888ae0934f.png)

The user can also enter "chevron" into the shapes field and hit enter to find all of the sightings with a chevron shape.

![Chevron](https://user-images.githubusercontent.com/84139177/132138741-2d034271-3772-4c1f-84b9-a607b9163d45.png)

#### Summary
##### Drawbacks
At this point in development, the webpage is pretty limited in terms of filter options and visualizations. Without any modifications, the webpage will not be able to grow and gather traction online. Adding the opportunity to view data using more than one filter, more than one filter entry (like multiple state options), or an option for time frames could be a start for further updates.

##### Recommendations
1. If this webpage is intended to be a serious, reliable soure of information, then references need to be added. For example, every row in the data table provided should have a link to the source of the claim, whether it be a news article, image, or interview. Without reference sources, the information provided on the webpage has no credibility.
2. If the webpage is inteded to stay current, web scraping should be considered as a tool for content. By web scraping news sources, current events involving UFOs can be found and referenced on the webpage.
