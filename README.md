# Feed-Reader-Testing
Project 6 for Udacity Frontend Nanodegree

Open the `index.html` file manually after extracting the project.

1.By checking whether allFeeds are declared and its length not equal t0 0 to make sure
  allFeeds variable has been defined and that it is not empty

2. Writing a for loop through the allFeeds array to to check whether the name is declared 
   and its length not equal to 0 to each feed in the allFeeds object and ensures it has a URL 
   defined and that the URL is not empty

3. Select the menu item and make sure it has "menu-hidden" item

4. Select menuIcon element and adds "click" to it to maker sure "menu-hidden" work well

5. Call function "loadfeed" before and using "done" to wait for the asynchronous completed
   Check whether "entries" length is not 0 to maker sure "loadfeed" function is called and completed.

6. a. Call function "loadfeed" and using "done" to wait for the asynchronous completed
   b. Get the first inner text
   c. Again, Call function "loadfeed" and using "done" to wait for the asynchronous completed
   d. Get second inner text
   e. check whether our first inner text and second inner text is different to maker sure a new feed 
      is loaded by the loadFeed function that the content actually changes
