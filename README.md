# Large-CSV-File-Splitter

This is just simple Bash script to deal with large CSV Files.  It automatically splits large .csv file into smaller parts preserving the header ( first line data ).

It uses the advantage of built in Linux CLI command "split".

By default it creates multiple files from one large .csv file with each of files containing maximum of 5000 ( five thousand ) records.  You could modify this value as you like.

## How To Use

- Simply download the __csv-split__ file.
- Make the file executable by typing ```chmod +x csv-split``` in your terminal
- Then do the split by executing it ```./csv-split large_file.csv```
- Done!

## Disclaimer

This script was created initially to help __my personal need__ in processing big .csv file.  I don't guarantee it fits your need.
