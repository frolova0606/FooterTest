# **FooterTest**
 This script is designed for automated testing of websites to check if a footer is present on specified pages. It sends HTTP requests to specified URLs and analyzes the received responses to make sure that the footer is present and includes links to social networks.

**Description**

The script checks the following aspects:
Presence of a footer on each page.
The status code of the response (must be 200).
Presence of social media links in the footer.

**Getting Started**
Install Postman: If you don't have Postman yet, download and install it from the official website.
Create a collection : In Postman, create a new collection and add this script to the “Tests” section for each request.
Customize URLs: The URLs of the pages to be tested are set in the script. You can change them if necessary.

**How to use**

Run the script in Postman.
The script will automatically test the specified pages and output the results to the console:
If the footer is present, you will get a notification that the test was successful.
If the footer is missing, you will receive a notification about it.
Social media links will be tested and the results will also be displayed.

