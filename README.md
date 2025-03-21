# Solar System Data Scraper

This project is a web scraper that extracts planetary data from the [Royal Museums Greenwich website](https://www.rmg.co.uk/stories/topics/solar-system-data) and saves it as a CSV file using Python, BeautifulSoup, and Pandas.

## Features
- Scrapes planetary data including name, sidereal period, perihelion, aphelion, and inclination.
- Stores the extracted data in a structured Pandas DataFrame.
- Saves the data to a CSV file (`solar_system_data.csv`).

## Technologies Used
- **Python**
- **BeautifulSoup** (for web scraping)
- **Requests** (for HTTP requests)
- **Pandas** (for data processing and CSV export)

## Installation
### Prerequisites
Make sure you have Python installed. You can install the required dependencies using:

```bash
pip install beautifulsoup4 requests pandas
```

## Usage
Run the script to scrape the latest solar system data and save it to a CSV file:

```bash
python scraper.py
```

After execution, the `solar_system_data.csv` file will be created in the project directory.

## File Structure
```
📂 Solar-System-Scraper
 ├── 📄 scraper.py        # Main script
 ├── 📄 solar_system_data.csv  # Output CSV file
 ├── 📄 README.md         # Project documentation
```

## Contributing
Feel free to contribute! To do so:
1. Fork the repository.
2. Create a new branch (`feature-new`).
3. Commit your changes.
4. Push to your branch and submit a Pull Request.

## License
This project is licensed under the MIT License.

---
### Author
Developed by **Yasith Rashan** 🚀

