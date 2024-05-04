# ops201challengeclass04.md

#!/bin/bash

# Script Name:                  Ops Challenge Arrays
# Author:                       Adrien Peterson
# Date of latest revision:      04/27/2024
# Purpose:                      Create 4 Directories

# Declaration of variables
directories=(“dir1” “dir2” “dir3” “dir4”)




# Declaration of functions



# Main
# Create four directories
for dir in “${directories[@]}”; do
    mkdir “$dir”
    touch “$dir”/”$dir”.text
done



# End
