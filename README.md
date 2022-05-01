# Mission-To-Mars
Automate a web browser to visit different websites to extract data about the Mission to Mars (Web Scraping), utilizing `BeautifulSoup`, `Splinter`, and `MongoDB`.

## Overview 
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

##Deliverable 1 

**Directions:**
1. Use your browser to visit the Mars Hemispheres website to view the hemisphere images.
2. Create a list to hold the .jpg image URL string and title for each hemisphere image.
3. Write code to retrieve the full-resolution image URL and title for each hemisphere image. The full-resolution image will have the .jpg extension.
4. Loop through the full-resolution image URL, click the link, find the Sample image anchor tag, and get the href.
5. Save the full-resolution image URL string as the value for the img_url key that will be stored in the dictionary 
6. Save the hemisphere image title as the value for the title key that will be stored in the dictionary 
7. Before getting the next image URL and title, add the dictionary with the image URL string and the hemisphere image title to the list you created in Step 2
8. Print the list of dictionary items

**Results:**

<img width="1163" alt="D1-1" src="https://user-images.githubusercontent.com/95068439/166168027-b7085677-2858-46a1-b8fb-e1d7e97e3e34.png">

<img width="1170" alt="D1-2" src="https://user-images.githubusercontent.com/95068439/166168033-6a87e11e-3de0-4ed7-a820-85f7ea708319.png">

<img width="664" alt="D1-3" src="https://user-images.githubusercontent.com/95068439/166168035-f3975a6d-c087-41e7-979e-bc4d9577164a.png">

<img width="1190" alt="D1-4" src="https://user-images.githubusercontent.com/95068439/166168038-e65b3452-8c95-4083-9504-cc3729799516.png">

<img width="1168" alt="D1-5" src="https://user-images.githubusercontent.com/95068439/166168040-09afccfe-d379-4f98-8708-5e93591f8327.png">


## Deliverable 2

**Directions:**

1. In the def scrape_all() function in your scraping.py file, create a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image.
2. Below the def mars_facts() function in the scraping.pyfile, create a function that will scrape the hemisphere data by using your code from the Mission_to_Mars_Challenge.py file. At the end of the function, return the scraped data as a list of dictionaries with the URL string and title of each hemisphere image.
3. Run the app.py file, then check your Mongo database to make sure that you are retrieving all of the data.
4. Modify the index.html file to access your database, and retrieve the img_url and title as you loop through the dictionary in the database using {% for hemisphere in mars.hemispheres %}. The dictionary in the mars hemispheres database is the dictionary that was created from the Hint after Step 3 in Deliverable 1.
5. Run the app.py file, open the index.html file, and click the "Scrape New Data" button.

**Results:**

<img width="512" alt="D2-1" src="https://user-images.githubusercontent.com/95068439/166168276-cd7e63a0-f0a1-4757-9615-c8d8032d4e29.png">

<img width="1212" alt="D2-2" src="https://user-images.githubusercontent.com/95068439/166168281-f0c65ac9-7922-46dd-9260-a4b1ca56f3e9.png">

<img width="1060" alt="D2-3" src="https://user-images.githubusercontent.com/95068439/166168286-149d5bd7-811d-45f9-afcb-52de2c3d58ac.png">

**Pictures**

![Screen Shot 2022-02-21 at 22 41 17 (2)](https://user-images.githubusercontent.com/95068439/166168186-62e240b3-2eb6-4596-924a-fdc6ce8fe215.jpeg)

![1 4 2](https://user-images.githubusercontent.com/95068439/166168084-b826bf6e-be72-4e0c-81ea-6fa65a531881.jpeg)

![1 4 3](https://user-images.githubusercontent.com/95068439/166168088-eaf933be-df47-4e68-8ef5-5b5f6da13c7d.jpeg)

![1 4 4](https://user-images.githubusercontent.com/95068439/166168089-82121c60-d9c6-4136-afc7-2009391f4a7c.jpeg)

![2 4](https://user-images.githubusercontent.com/95068439/166168367-e92f03e9-8467-4e45-ba79-a33917ec8289.jpeg)

## Deliverable 3

**Directions:**
1. Adding a Bootstrap components
2. Customizing facts table
3. Adding the hemisphere images as thumbnails

**Pictures**

![3 1 1](https://user-images.githubusercontent.com/95068439/166168416-3f1d429e-83d2-44e8-b405-ae0c18c02861.jpeg)

![3 1 2](https://user-images.githubusercontent.com/95068439/166168420-0b55dbc9-2cbf-4361-8a74-2ae6575672c8.jpeg)

![3 1 3](https://user-images.githubusercontent.com/95068439/166168421-1ae00a25-860d-496b-87c7-14ceb26e76c4.jpeg)

![3 1](https://user-images.githubusercontent.com/95068439/166168423-432c2722-5971-425b-b2b4-fc0eb9062fc5.jpeg)


> LinkedIn: https://www.linkedin.com/in/wilson-alexei/

> Email: wils.alexei@gmail.com




