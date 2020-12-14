# Property Search

## Requirements

- Python (v3.8 or above) and pip
  - `sudo apt update`
  - `sudo apt install software-properties-common`
  - `sudo add-apt-repository ppa:deadsnakes/ppa`
  - `sudo apt update`
  - `sudo apt install python3`

- Node and NPM (v12.18.4 or above)
  - `curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.35.3/install.sh -o install_nvm.sh`
  - `bash install_nvm.sh`
  - `source ~/.profile`
  - `nvm install 12.18.4`

## Steps to Run

- Go to the deliverables folder. Run the following commands in sequence:
  - `python3 pip  install -r requirements.txt`(To be run only first time)
  - `python3 server.py`

- Open new terminal and go to deliverables folder and run the following commands:
  - `npm install` (To be run only first time)
  - `npm start`

- Flask server will run on `http://localhost:5000/`
- Site will run on `http://localhost:3000/`

## Functionalities Included

- Searching for a locaiton and getting paginated data for properties on basis of following parameters
  - minimum price
  - maximum price
  - minimum #beds
  - maximum #beds
  - property type
  - date added
  - distance from entered location
  - and many other filters like modernisation, quick sale, cash only, etc
- Ability to sort the above output
- Ability to download the search results in an excel file
- Getting details of a particular property from previous output
  - Agent info (contact number, address, name)
  - property description, floor plan, bedrooms,bathrooms, floors count
  - crime rates, average values, school performance in area, council tax in area, population breakdown in area, values range distribution, value trend, home values
  - similar sold properties in the area
  - similar for sale properties in the area
  - similar for rent properties in the area

## Functionalities not included

- Some attributes information which could not be fetched from the available APIs
- Some of the othe pages which did not have available APIs for data or the APIs were paid
- The calculators, again the data was not available through a free API, or its logic was not public

## Demo

![demo](demo.gif)