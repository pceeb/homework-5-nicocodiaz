#!/bin/bash/sh

#Action 1:

sed 's/;/\t/g' README_Week7_Data.txt | sed 's/../\t/g'

#This command will separate the taxonomy categories (Kingdom, Phylum, Class, Order, Family, Genus, Species) listed for each species. These are listed at the very end of the data.

#This command will take out the semicolons and replace them with tabs, to create the space in between each column.

#Action 2:

#Went to first line of the text file, which provides the titles for each column of data. Added the terms Kingdom, Phylum, Class, Order, Family, Genus, Species, all of which were separated by tabs.

#This was done manually instead of using a command. We did this to ensure the titles were were correctly placed over the corresponding data and to save time.

#Action 3:

#To delete the species without a full taxonomy breakdown, we uploaded the README_Week7_Data.txt file to GitHub to view the data. 

#We used Ctrl F to find ';;' which indicates that one category within the phylogeny was non identified. This was to confirm how may species would have to be deleted in the text file.

#We returned to README_Week7_Data.txt file and deleted the lines with the ';;' character present using the command...

grep -n ";;"




#This completes the first part of our Final Project as the data is properly organized with incomplete data eliminated.

#The remainder of our project with focus on using RStudio and TR8 Package to analyze different variables of the remaining species data in README_Week7_Data.txt.
