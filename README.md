# Price-Scraper-Currency-Converter

This project is a python based price scraper curency converter which scraps book data from a book website then converts the scraped currency GBP to KES.It then stores the scraped data information and diplayethe book information including the title,price in GBP and KES and conversion status and time.The data information is  saved as a csv and /or json file and the book price is visulaed against book title.

## Features
 
 * ** Scrape data:** book data is extracted from the book website 

 * ** Currency conversion:**the prices of the boook is converted from the scraped price in pounds to kenyan shillings

 * ** Data frame:**stores book data you scraped

 * ** Results display:**displays scraped and convered prices of the book

 * ** Saving output files:**saves the scraped book data information in csv and json files

 * ** Plot:**visualise the book price against the book title 

## Technical Stack
* ** Language : ** Python 3
* ** Modules:** requests (Standard Library)
* ** Storage :** file system

### Prerequisites
* **  Install python on your machine.Check your version by running ''bash python --version


### Installation and setup
**Clone the Repository:**

    ```bash
git clone https://github.com/graceobonyo/Price-Scraper-Currency-Converter.git
cd guess-the-number
    ```

2.  **Run the program:**
    In the terminal pip install requests, bs4, pandas, matplotlib
    Then execute the script:

    ```bash
    python main.py
    ```


## Contributing

Contributions are what make the open-source community an excellent place to learn, inspire, and create. Any contributions you make are welcomed.

### How to Contribute

**Fork the Project**

**Create your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature
    ```

**Commit your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```

**Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
    ```

**Open a Pull Request**


### Areas for Improvement

  * Adding a API key to automatically convert the exchange rate since the exchange rate is bound to change anytime.
  * Adding an input feature to enable key in of the type of book and price one want to purchase within a specifc price range and genre of books 
  
  
## Project Structure

text
main.ipynb            # Main project information
book_price_converted.csv  # Local database for storing book information including title,price and conversion satus and time(auto-generated)
book_price_converter.json  # Local database for storing book information including title,price and conversion satus and time(auto-generated)
README.md          # Project information


## License

This project is open-source and available under the [MIT License] (https://github.com/graceobonyo/Price-Scraper-Currency-Converter/blob/main/LICENSE)


Grace Obonyo :https://github.com/graceobonyo
