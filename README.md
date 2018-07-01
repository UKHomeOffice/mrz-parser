Machine Readable Zone Parser

Based on ICAO Document 9303, Machine Readable Travel Documents, Seventh Edition 2015

Document Series
https://www.icao.int/publications/pages/publication.aspx?docnum=9303

Work in Progress ...

## Document Types
1. Type 1 Format
2. Type 2 Format
3. Type 3 Format

## Type Format Characteristics and constraints

| Format        | Line Span     | Line Length  | Characters   |
| ------------- | ------------- | -----------  | -----------  |
| Type1         | 3             | 30           | A-Z 0-9 <    | 
| Type2         | 2             | 36           | A-Z 0-9 <    | 
| Type3         | 2             | 44           | A-Z 0-9 <    | 

## Type 1 format

### Line 1

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  |  
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- |  
| Document Type                  | Y         |              |  A-Z                  | 1           | 2           |        
| Issuing State or Organization  | Y         |              |  A-Z                  | 3           | 3           |        
| Document Number                | Y         |              |  A-Z0-9               |             | 9           | 

### Line 2

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | 
| Birth Date                     | Y         |              |  0-9                  |  6          | 6           | 
| Expiry Date                    | Y         |              |  0-9                  |  6          | 6           | 
| Nationality                    | Y         |              |  A-Z                  |  3          | 3           | 

### Line 3

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | 
| Identifiers                    | Y         | Names        |  A-Z                  | 1           | 30          |        



## Type 2 format

### Line 1

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  |  
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- |  
| Document Type                  | Y         |              |  A-Z                  | 1           | 2           |        
| Issuing State or Organization  | Y         |              |  A-Z                  | 3           | 3           |        
| Identifiers                    | Y         | Names        |  A-Z                  | 1           | 31          |        

### Line 2

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | 
| Document Number                | Y         |              |  A-Z0-9               |             | 9           | 
| Nationality                    | Y         |              |  A-Z                  |  3          | 3           | 
| Birth Date                     | Y         |              |  0-9                  |  6          | 6           | 
| Expiry Date                    | Y         |              |  0-9                  |  6          | 6           | 

## Type 3 format

### Line 1

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | Format | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | ------ | 
| Document Type                  | Y         |              |  A-Z                  | 1           | 2           |        |
| Issuing State or Organization  | Y         |              |  A-Z                  | 3           | 3           |        |
| Identifiers                    | Y         | Names        |  A-Z                  | 1           | 39          |        |

### Line 2

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | 
| Document Number                | Y         |              |  A-Z0-9               |             | 9           | 
| Nationality                    | Y         |              |  A-Z                  |  3          | 3           | 
| Birth Date                     | Y         |              |  0-9                  |  6          | 6           | 
| Expiry Date                    | Y         |              |  0-9                  |  6          | 6           | 


## Check Digits
A-Z mapped to 10-35

### Dates
Format YYMMDD followed by check digit

### Document Number
A-Z0-9 followed by check digit

## Nationality

### Country Codes
1. Alpha 3 Codes

## Transliteration

Letter -> Unicode -> A-Z (1..n)
