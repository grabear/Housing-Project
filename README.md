# Housing Project
Use the pdf file for instructions on how to complete the project.

# Step 1: Clean the Data
Some of the data has bad values.

## For zip-city-county-state file
### GUID
Some of the guid's are not correct.  Normally they have a string that looks like:
"00D8ABF2-5101-28E6-68F0-D2A572869349"
The bad strings generally look like:  "YMDE"

To solve the problem parse each GUID and if they don't have any dashes,
then delete the record.

### Zip code
Some of the zip codes look like: "YMDE"
Replace these values with a random number of **5** digits.

## For income-info file
## Zip Code
Some of the zip codes look like: "YMDE"
Replace these values with a random number of **5** digits.

## Median income
Some of the median incomes look like: "YMDE"
Replace these values with a random number of **6** digit


