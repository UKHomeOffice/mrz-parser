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

## Fields mentioned in document

| Field                          | Mandatory | Description  |  Allowed Characters   | Min Length  | Max Length  | Format | 
| ------------------------------ | -------   |------------- |  -------------------  | ----------- | ----------- | ------ | 
| Document Type                  | Y         |              |  A-Z                  | 1           | 2           |        |
| Identifiers                    | Y         | Names        |  A-Z                  | ?           | L**         |        |
| Issuing State or Organization  | Y         |              |  A-Z                  | 3           | 3           |        |
| Dates                          | Y         |              |  0-9                  | 6           | 6           | YYMMDD |

L** - type length - (doc type length + dates + org length )


## Check Digits

A-Z mapped to 10-35

## Nationality

### Country Codes
1. Alpha 3 Codes

## Transliteration
