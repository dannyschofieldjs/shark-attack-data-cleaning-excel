# Data Cleaning Log

| Step | Data issue | Action taken | Reason |
|---|---|---|---|
| 1 | Unnecessary columns | Retained 11 analysis fields | Reduced the dataset to the fields required for analysis |
| 2 | Blank and duplicate rows | Removed affected rows | Prevented duplicated observations |
| 3 | Duplicate case numbers | Added .1 and .2 suffixes | Preserved unique record identifiers |
| 4 | Missing year | Derived year from Case Number | Retained otherwise usable records |
| 5 | Missing type | Replaced with "unknown" | Preserved missingness without leaving blanks |
| 6 | Missing country | Removed the record | Country was required for location analysis |
| 7 | Missing descriptive values | Replaced with "unknown" | Standardised missing categorical data |
| 8 | Non-numeric age | Replaced with "unknown" | Prevented mixed or misleading values |
| 9 | Invalid fatal indicator | Standardised to Y, N or unknown | Created consistent categories |
| 10 | Hidden spaces and formatting | Standardised Year and Sex | Prevented duplicate chart categories |
