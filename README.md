Cuerdo, Marjorie Ann  
Fielder, Sabrina  
Lietz, Rebecca  

# Wave Function Collapse for Poetry

This is adapted code from https://github.com/mewo2/oisin for performing the [WaveFunctionCollapse][wfc] algorithm on poems. 
It mashes up sentence fragments from a given text file to produce poems with fixed metric forms. 

# Example output
![Section of Harry Potter Output](https://raw.githubusercontent.com/marjcuerdo/wfc_poetry/main/output/hp.png)

[insert screenshot of example text]
[Full Output Text File](https://raw.githubusercontent.com/marjcuerdo/wfc_poetry/main/output/output_harrypotter1_1.txt)

It can also animate the process:
![GIF of Harry Potter Output](https://raw.githubusercontent.com/marjcuerdo/wfc_poetry/main/output/hp.gif)

# Instructions 

1. Clone this repository 

or 

Download the zipped folder and unzip it to your desired location.

## If you do not have pip installed

1. Open your command prompt/terminal.

2. Navigate to the folder that has Python.

3. Copy and paste the following commands and run them one at a time:

`curl https://bootstrap.pypa.io/ez_setup.py -o - | sudo python`

`sudo python get-pip.py`

4. Install required packages to run the algorithm

`pip install -r requirements.txt`

## Generate poetry text file

1. Navigate `cd` to where you unzipped the `wfc_poetry` folder.
2. Enter the following code:

`python ballad.py [input/yourTextFileName.txt] [output/yourNewPoemTextFile.txt]`

## Generate animated GIF

1. Enter the following code:

`python makegif.py [input/yourTextFileName.txt] [numberOfLines] [output/yourGifFileName.gif]`

# Rules and constraints


# Process for good output


