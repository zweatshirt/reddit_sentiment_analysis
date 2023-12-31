# Reddit Comments Sentiment Analysis 

## Authors: Alex Wernex and Zachery Linscott

This is a program to download the HTML pages of multiple URLs pointing to Reddit posts.
Each URL is read from a file that the user of the program provides a path to.

The raw HTML of each URL is then put into separate files.

From there the HTML to extract the comments from the subreddit.  

Once each all the html is cleaned,   the comments from each url are scrubbed from the html  
then stored cleanly into yet more files which are unique to each Reddit post.

Next, the comments files are scanned and sentiment analysis is performed on each comment.  
Once the sentiments are gathered, they are also put into their own files,  again unique for each Reddit post.

Finally, each sentiment file is then put into its own bar graph  
where the user can visually see
the number of positive, negative, and neutral comments.  
These graphs appear and are stored in the plots folder as well,  
located in Data.

## How to Use

1. Ensure you are in the correct directory.

2. Make sure to download the environment from requirements.yaml to make sure you have the appropriate libraries.

3. Run in the terminal using python passing the file of urls you wish to gather comments from as an argument, e.g.: `python run.py yourfilepath/yourfilename`
   
5. Finally when you are finished viewing the graphs, exit out of all of the windows to end the program.
Don't worry, all of the graphs will still be in the plots folder as pictures. 

Also, make sure you ran the run.py with the old.reddit link for each one. Otherwise the comments will not be in the file and it won't work.

## Sample Output

The attached Data/raw/HTMLOutput files, Data/processed/comments files, Data/sentiments/sentiments, and Data/Plots/graphs files 
are all sample outputs.
