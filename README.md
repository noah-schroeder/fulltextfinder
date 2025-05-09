# Full Text Finder

A simple web tool that helps researchers and students efficiently download academic articles by processing CSV files containing article references.

## Features

- Upload CSV files with article metadata (DOI, title, etc.)
- Retrieve direct links to full-text PDFs via Unpaywall API
- Process data entirely client-side (your data never leaves your browser)
- No installation required - works directly in your web browser

## How to Use

### Option 1: Github Page
1. Visit the [Full Text Finder](https://noah-schroeder.github.io/fulltextfinder/)
2. Enter your email address (required for Unpaywall API)
3. Upload your CSV file containing article references
4. Review the generated filenames and download links
5. Download articles directly or export the results as a new CSV

### Option 2: Local page
1. Download the html file in the github repo
2. Open the html file on your local computer using the web browser of your choice. 

## CSV Format

Your input CSV should contain at least the title, but I recommend using as many of the columns below as you can for best results:
- `doi` - Digital Object Identifier
- `title` - Article title
- `authors` - Article authors
- `year` - Publication year

## Privacy & Security

- Your email is only used for Unpaywall API requests
- No data is collected or stored by this tool

## Technologies

- Built with HTML, CSS, and JavaScript
- Uses [PapaParse](https://www.papaparse.com/) for CSV parsing
- Styled with [TailwindCSS](https://tailwindcss.com/)
- Integrates with [Unpaywall API](https://unpaywall.org/products/api)

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0) - see the LICENSE file for details.

This is a copyleft license that requires anyone who distributes or modifies this code to make the source available under the same terms.

## Acknowledgements

- [PapaParse](https://www.papaparse.com/) - MIT License
- [TailwindCSS](https://tailwindcss.com/) - MIT License

## Contributing

Contributions are welcome!
