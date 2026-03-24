# Amazon Product Scraper

fast, multithreaded Amazon product scraper with a clean GUI interface.

## Features

- **Fast Performance**: Multithreaded scraping with configurable workers
- **Clean GUI**: Easy-to-use interface with real-time progress
- **Configurable**: Set product search, pages, workers, and output filename
- **Unique Results**: Automatic duplicate removal by product title
- **CSV Export**: Results saved to organized output folder

## Project Structure

```
transformers/
├── main.py              # Main entry point
├── requirements.txt     # Dependencies
├── README.md           # This file
├── core/               # Core scraping logic
│   └── scraper.py      # Scraping functions
├── gui/                # GUI components
│   └── main_window.py  # Main GUI window
└── output/             # Generated CSV files
```

## Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python main.py
```

## Usage

1. **Product Search**: Enter the product you want to search for (e.g., "headphones")
2. **Pages**: Set how many Amazon pages to scrape (1-20)
3. **Workers**: Set concurrent threads for faster scraping (1-10)
4. **Output**: Choose filename for CSV results
5. **Start**: Click "Start Scraping" and monitor 

## Performance

- **Original**: ~56s for 5 pages
- **Optimized**: ~19s for 5 pages (66% faster)
- **Rate**: ~3.5 products/second

## Output Format

CSV files contain:
- Product name
- Price
- Rating
- Review count
- Amazon URL
- Product code"# automation-test" 
"# automation-test" 
