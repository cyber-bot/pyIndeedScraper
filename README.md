# pyIndeedScraper

pyIndeedScraper is a Python Program to scrape Indeed to get Data regarding a Job regarding a Job Title and Location on any page of Indeed.

## Installation

Use pip install requirements.txt to Install all requirements.
```bash
pip install requirements.txt
```

## Usage

For Example, lets scrape Data for Data Scientist Jobs in New York from the Second Page on Indeed that are Full Time Positions. For Spaces, use the + Sign as shown below. Page is optional, by default it will be 1.
```bash
python main.py -jobTitle Data+Scientist -location New+York -page 2 -jobtype fulltime
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)