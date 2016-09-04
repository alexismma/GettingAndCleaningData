# Description

Downloading Data

The first thing I did in my solution is check to see if the zip file is downloaded and if not then I download it. 

File Preparation

The second was to load all the pertinent files. I put the column names on each of the test and training set files. I then used cbind() to append the subject and activity identifiers.

Finally, I´ve merged the two files together using cbind().

Extract Mean & Standard Deviation Measurements

I´ve decided to keep those variables that had the word mean or std in them and were the main function. 

Tidy Data Output

I used rbind() to train the data with the test data, and then summarize. And finally print the results.


