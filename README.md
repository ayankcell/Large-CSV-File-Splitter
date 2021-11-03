# Large-CSV-File-Splitter

This is just simple Bash script to deal with large CSV Files.  It uses the advantage of built in Linux CLI command "split".  By default it creates multiple files from one large .csv file with each of files containing maximum of 5000 ( five thousand ) records.  You could modify it as you like.

## How To Use

- Simply download the __csv-split__ file.
- Make the file executable by typing __chmod +x csv-split__ in your terminal
- Then do the split by executing it __./csv-split large_file.csv __
- Done!

## Disclaimer

This file was created initially to help __my personal need__ in processing big .csv file.  I don't guarantee it fits your need.
