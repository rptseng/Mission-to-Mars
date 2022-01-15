# Mission-to-Mars
## Summary
The goal is to create a web app using Flask to scrape and present data and images about Mars. After the html index template is created, we will use Bootstrap to add additional presentation features to the page.

## Hemisphere Image Scraping
Using Splinter and BeautifulSoup, a code was created to navigate a browser through 'https://marshemispheres.com/' and retrieve the URLs and titles of the four full-resolution images of Mars hemispheres. A for loop was created to iterate through each of those links by searching for the respective html tags, located by using Google Chrome DevTools. Below are the four correctly retrieved images:

![hemi_titles_images.png](https://github.com/rptseng/Mission-to-Mars/blob/main/assets/hemi_titles_images.png)

## Updating Web App
The code block to retrieve the Mars hemisphere images was inserted as the function mars_hemispheres in scraping.py so the data can be added to MongoDB. A new html template was also created to display the hemisphere images at the bottom of the web app.

![hemi_scrape_function.png](https://github.com/rptseng/Mission-to-Mars/blob/main/assets/hemi_scrape_function.png)

## Bootstrap 3 Components
Using the DevTools, the website is mobile responsive.

The following two Bootstrap3 elements were added to the page:
- Changing the background colour of the jumbotron title to purple
- Modifying the "Scrape New Data" button with the "danger" style to turn it to a red colour

![page_screenshot.png](https://github.com/rptseng/Mission-to-Mars/blob/main/assets/page_screenshot.png)

