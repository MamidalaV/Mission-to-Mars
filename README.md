# Mission-to-Mars

# PURPOSE: The purpose of this project is to create a web application using webscraping logics by extracting various bits of information on planet Mars from different websites.

### Using Splinter and BeautifulSoup libraries in Python:
- The html code "https://redplanetscience.com/" is accessed and the title and headline of the latest article is scraped.
  
![news](https://user-images.githubusercontent.com/74985818/117238448-eb893880-adfa-11eb-8859-c8e8355fb861.png)

- Using the same libraries, the html code of "https://spaceimages-mars.com" website is accessed to get the URLs for high resolution images of all 4 hemispheres of Mars.

![forloop](https://user-images.githubusercontent.com/74985818/117238471-f2b04680-adfa-11eb-8d4e-78687223bbe7.png)


### This scraped information is stored in MongoDB:

![mongodb](https://user-images.githubusercontent.com/74985818/117238648-4c187580-adfb-11eb-8801-126fe16cba80.png)


### The data scraped from these websites is stored in MongoDB and using HTML, a webpage is designed to display this information.

This is acheived using the below code designed within the 'flask' application (app.py)

![flask](https://user-images.githubusercontent.com/74985818/117238793-87b33f80-adfb-11eb-8110-526aa882269f.png)

### Website code using HTML can be found ![] <<here>> where with a button click, all the lastest information needed for this project can be scraped when needed.
  
![webpage](https://user-images.githubusercontent.com/74985818/117239195-4e2f0400-adfc-11eb-9e2b-cd3490864bb9.png)
  
### Below are the images of hemispheres scraped from "https://spaceimages-mars.com" website.

![hemispheres](https://user-images.githubusercontent.com/74985818/117239320-8e8e8200-adfc-11eb-8f47-5bfc691b5540.png)

### Within the HTML code, 2 additional bootstrap components are used to change the color of the 'Scrape New Data' button and background image (Ingenuity helicopter's first flight on Mars) added inside the Jumbotron class of first < div/ > tag.
  
![bootstraps](https://user-images.githubusercontent.com/74985818/117239596-15dbf580-adfd-11eb-908e-2ac2b484e280.png)


