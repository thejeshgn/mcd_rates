# MCD Rates
The MCD (Municipal Corporation of Delhi) Rate Finder helps user to find out the current prices, per square meter, of MCD land available for sale in the Delhi region.

- Data in [CSV - mcd_rates.csv](https://github.com/thejeshgn/mcd_rates/blob/master/mcd_rates.csv) and in [sqlite - mcd.sqlite](https://github.com/thejeshgn/mcd_rates/blob/master/mcd.sqlite)
- [How did I scrape this?](https://github.com/thejeshgn/mcd_rates/blob/master/how-to-scrape.md)
- [Meta Data](https://github.com/thejeshgn/mcd_rates/blob/master/metadata.md)

##Just give me the data
All the data is in mcd_rates.csv if you like sqlite then check mcd.sqlite

## License
This scraping code and scraped data are availabe under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Which means 
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.The licensor cannot revoke these freedoms as long as you follow the license terms.

As long as
- Attribution — You must give appropriate credit, Generally attribute data work to Thejesh GN linking to http://thejeshgn.com


## How to rerun?
### Download 

Download  or clone the git project.


### Install Dependencies
`
pip install -r requirements
`

### To run 
`
python scrape.py
`

### Export data as csv
`
datafreeze export.yaml
`


