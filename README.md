## Installation

Start by creating a virtual environment
`mkvirtualenv speech_formatter -p /usr/local/bin/python3`

Jump into the virtual environment
`workon speech_formatter`

Install all required packages
`pip install -r requirements.txt`

## Format speeches
Download your spreadsheet as csv to the folder named docs.

Run `jupyter lab`.
Go into `format.ipynb` and change `name` to the name of your downloaded file.

Run all the cells. Now there should be a bunch of csv files in the folder `formatted`. Upload these to Google Drive.

