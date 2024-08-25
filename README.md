
# All University, School, and College Database

This repository contains a JSON file with a unique list of names of universities, schools, and colleges. The data is compiled from various sources and is intended for educational or research purposes.

## Overview

The JSON file contains a list of unique institution names, including:
- Public Universities
- Private Universities
- Colleges
- Schools (English Medium, Bangla Medium, Madrasha)
- International Universities

The data can be used for different applications, such as:
- Educational research
- Data analysis
- Project integration

## File Structure

- `unique_institute_names.json`: Contains the unique names of all institutions (universities, schools, and colleges) after merging data from different sources.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mahmudtopu3/all-university-school-college-database.git
   ```

2. **Access the data**:
   After cloning, you can use the `unique_institute_names.json` file for any project or data analysis.

   Example in Python:
   ```python
   import json

   # Load the JSON data
   with open('unique_institute_names.json', 'r', encoding='utf-8') as file:
       data = json.load(file)

   # Print the list of unique names
   print(data)
   ```

## Data Sources

The data is compiled from the following sources:
- Public University data
- Private University data
- English Medium Schools
- Bangla Medium Schools
- Madrasha Schools
- International Universities

## Contributions

Feel free to fork this repository and contribute by submitting a pull request if you have additional data or suggestions for improving the dataset.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
