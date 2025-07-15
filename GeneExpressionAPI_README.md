# Gene Expression API

This project is a beginner-friendly RESTful API built using Python and Flask. It simulates gene expression data and helps understand how APIs can be used to access and share biological datasets programmatically.

## Features

- Retrieve a list of gene names
- Query expression levels and tissue-specific information for individual genes
- Learn basic API routing and data handling with Flask

## Example Dataset

```json
{
  "BRCA1": {"expression_level": 5.4, "tissue": "breast"},
  "TP53": {"expression_level": 7.1, "tissue": "lung"},
  "EGFR": {"expression_level": 4.2, "tissue": "brain"},
  "MYC": {"expression_level": 6.8, "tissue": "liver"}
}
```

## API Endpoints

- `/` - Welcome route
- `/genes` - Returns a list of all available genes
- `/expression?gene=GENENAME` - Returns expression details for the specified gene

## Technologies Used

- Python
- Flask
- REST API principles
- Postman (for testing)

## How to Run This Project

1. Download or clone the repository
2. Install Flask with:
   ```
   pip install Flask
   ```
3. Run the application:
   ```
   python app.py
   ```
4. Access the endpoints via browser or Postman

## Sample Usage

```
GET /expression?gene=BRCA1
```

## Author

Rabia Waseem Baig  
Bioinformatics student at COMSATS University Islamabad  
LinkedIn: https://www.linkedin.com/in/rabia-waseem-baig-2a8597283

## Future Improvements

- Add ability to upload or update gene data
- Integrate with real biological datasets
- Include basic user authentication
