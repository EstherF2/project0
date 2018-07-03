# Project 0

Web Programming with Python and JavaScript
Xinning (Esther) Fang
07/03/2018

My website is based on my trip to Japan not long ago. I had five .html pages: homepage.html, which is clearly the homepage of the website; schedule.html, which is a page where I made a table that shows the schedule of my Japan trip; Onsen.html, which basically introduces onsen in Japan and pics of some onsens we went; food.html, which introduces food I had in Japan with pictures as well, and lastly, scenic_spots.html, which mainly has photos I took in Japan. Please start with homepage.html.

In each page except homepage.html, I used Bootstrp to make a navigation bar at the top of the page, so that each page an be linked to each other. In the homepage.html, I used Bootstrap's grid model to create a basic navigation grid of the four pages.

As of @media, I used this in the layout of images in homepage.html and scenic_spots.html. When the screen is larger than 800px, there will be three images in a row; if it is smaller than 800px but larger than 600px, there will be two images in one row, and if the screen is smaller than 600px, there will be only one image in one row. These are included in grid.scss.

Except for grid.scss, I also created variable.scss for general style that might be often used and navigation.scss for the navigation bar. For nesting, I created another nesting.scss so that colors of texts under <ul> and <ol> are different. This was shown in scenic_spots.html.

I also imported some Google fonts found on https://www.w3schools.com/howto/howto_google_fonts.asp. For images on food.html and onsen.html, I included captions under each image, while I referenced this from https://www.w3schools.com/howto/howto_css_image_transparent.asp. Also, in terms of
rowspan of the table of my schedule, I read https://www.w3schools.com/html/html_tables.asp to get the information I want.
