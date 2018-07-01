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

| Format     | Lines     | Line Length  | 
| ---------- | --------- | -----------  | 
| Type 1     | 3         | 30           | 
| Type 2     | 2         | 36           | 
| Type 3     | 2         | 44           | 

## Type 1 format

### Line 1

| Field                          | 
| ------------------------------ | 
| Document Type                  | 
| Issuing State or Organization  | 
| Document Number                | 

### Line 2

| Field                          | 
| ------------------------------ | 
| Birth Date                     | 
| Expiry Date                    | 
| Nationality                    | 

### Line 3

| Field                          | 
| ------------------------------ | 
| Identifiers                    | 



## Type 2 format

### Line 1

| Field                          | 
| ------------------------------ | 
| Document Type                  | 
| Issuing State or Organization  | 
| Identifiers                    | 

### Line 2

| Field                          | 
| ------------------------------ | 
| Document Number                | 
| Nationality                    | 
| Birth Date                     | 
| Expiry Date                    | 

## Type 3 format

### Line 1

| Field                          | 
| ------------------------------ | 
| Document Type                  | 
| Issuing State or Organization  | 
| Identifiers                    | 

### Line 2

| Field                          | 
| ------------------------------ | 
| Document Number                | 
| Nationality                    | 
| Birth Date                     | 
| Expiry Date                    | 


## Check Digits
A-Z mapped to 10-35

### Dates
Format YYMMDD followed by check digit

### Document Number
A-Z0-9 followed by check digit

## Nationality

### Country Codes
1. Alpha 3 Codes
