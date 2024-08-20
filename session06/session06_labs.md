## Session 06 labs

### Checklist before you start:

1. Make sure you installed Visual Studio Code, git, and Python 3.11. <br><br>

2. Create a folder on your disk for all your coding projects. You may want to avoid spaces in the folder path for easier navigation. Make sure you remember where it is.<br><br>

3. Download the Module 2: Introduction to Data Science repository to that folder and make sure it's connected to GitHub. You can do it using the "Clone" function in VSCode. Please do not edit or add any files to this folder.<br>
https://github.com/peckham-daz/24-intro-to-data-science<br><br>

4. Create your own GitHub repository for this module on GitHub and set it up in your coding projects folder using the "Clone" function in VSCode.<br><br>

5. Make a virtual Python environment in your learning repository folder and add it to .gitignore. .gitignore is a file containing list of files and directories which should not be tracked by git.<br><br>

6. Create a text file on your desktop and paste the commands that you need to run the virtual environment.<br><br>


### Task 1
#### creating a .txt file - in the console
Using Python from the console, create and save a .txt file with your name, city, and a list of hobbies. You can use the code snippet below as a starter.

https://www.w3schools.com/python/ref_string_join.asp
https://www.pythonmorsels.com/slicing/
https://www.w3schools.com/python/python_string_formatting.asp

```
my_name = 'Name'
city = 'CityName'
hobbies = ['hobby_1', 'hobby_2', 'hobby_3']

# transform the text to match the pattern below. Note the 'and' added before the last hobby. You may have a look at list slicing to achieve that. Make sure it works with any number of hobbies.

my_text = 'My name is Marysia. I live in London. My hobbies are crocheting, hiking, music and computational art.'
```

Now, save the created text to a new .txt file:
https://www.w3schools.com/python/python_file_handling.asp

### Task 2
#### Write a piece of code which checks if a number even or odd.
you may want to have a look at the modulus operator:<br>
https://www.geeksforgeeks.org/what-is-a-modulo-operator-in-python/<br>
and conditional statements:<br>
https://www.w3schools.com/python/python_conditions.asp<br>

Can you make it into a function?
Here's Python function syntax:
https://www.w3schools.com/python/python_functions.asp

Can you write the code within the function as a single line?
TIP: think of casting Boolean values to integers adn using them for list indexing.


### Task 3
#### basic string operations - create a .py file you can run from the console
Create a Python script which lists of 10 most popular words in "The Story of the Fierce Bad Rabbit". Link to the text file:<br>
https://github.com/peckham-daz/24-intro-to-data-science/blob/main/session06/beatrix_potter_the_story_of_a_fierce_bad_rabbit.txt<br><br>

You may want to remove punctuation before counting the words. Save the information in a readable format to a new .txt file and publish on your GitHub.


how to read a file: https://www.w3schools.com/python/ref_file_read.asp<br>
how to split text: https://www.w3schools.com/python/ref_string_split.asp<br>
how to remove punctuation: https://www.geeksforgeeks.org/python-remove-punctuation-from-string/<br>
how to change words t
word counting: https://www.w3schools.com/python/ref_string_count.asp


### Task 4
#### editing text - create a .py file you can run from the console
Try to edit the story by replacing some of the most popular words. Save it to a new file and publish on your GitHub. Share the story in your groups.


### Task 5
#### the Python challenge - in a Jupyter notebook
Complete at least the first 5 steps of the Python challenge. Save the solutions in a Jupyter notebook and publish it to your GitHub.<br>
http://www.pythonchallenge.com/


### Task 6 - advanced
#### the MoMA dataset - work on it in a Jupyter notebook
**Note:** there are libraries that do parts fo these tasks for you, which we will learn next week. Today, please try to analyse this dataset using the built-in libraries and functions (for loops, csv library, json library).

how to import libraries:
```
# typically, imports would be listed in alphabetical order
import csv
import json
```
**Tip:** Start by figuring out how to read a .csv file and extract a column from it using a for loop and indexing.

for loops in Python: https://www.w3schools.com/python/python_for_loops.asp
reading csv files: https://www.geeksforgeeks.org/reading-csv-files-in-python/

#### Here is the file for this exercise:<br>
https://github.com/peckham-daz/24-intro-to-data-science/blob/main/session06/moma_artworks_1000.csv

It is a fragment of this MoMa dataset: https://github.com/MuseumofModernArt/collection

I suggest you do this exercise in a Jupyter notebook.

a. Find 5 artists with the most artworks in the dataset.

b. Find the artworks with the largest and smallest volumes (height * depth * length). Express the final number in meters.

c. What is the most popular word in the title?

d. What materials only appear in the dataset once?

e. Write all the information in a dictionary and save it to a .json file.

https://www.w3schools.in/python/json

```
# create a dictionary to match the pattern below and save it to a .json file

dict_to_save = {
    'most_pupular_artists': [
        'Artist 1',
        'Artist 2',
        'Artist 3',
        'Artist 4',
        'Artist 5',
    ],
    'largest_volume_artwork: {
        'title': 'Artwork title',
        'artist': 'Artist Name',
        'volume_m3': volume_largest,
    },
    'smallest_volume_artwork': {
        'title': 'Artwork title',
        'artist': 'Artist Name',
        'volume_m3': volume_smallest,
    },
    'most_popular_title_word': 'word',
    'materials_only_used_once': [
        'Material 1',
        'Material 2',
        'Material 3'...
    ],
}
```

### Task 7 - homework
For the next class, find a dataset with a table in .csv, .json or .tsv format to explore. Try to select something you find interesting. You can look on Kaggle, museum and library websites, statistics office websites, etc. Be prepared to describe your dataset in a few sentences to your group.

**Example data sources:**

https://www.kaggle.com/datasets

https://www.ons.gov.uk/

https://www.nga.gov/open-access-images/open-data.html

https://www.data.gov.uk/search?filters%5Bpublisher%5D=Tate

