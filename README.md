With this script, you can upload large CSV log files to your laptop, about 50 GB in total.

When I was working with several large csv files I had a problem uploading them to my laptop. When I uploaded multiple files over 10GB each, I got memory errors.

To optimize memory usage, I used chunks, changed some column types, and loaded all the files into a temporary list before concatenating them into a common data frame.
