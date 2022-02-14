This repo is a companion to the [awesome-streaming-data-sources](https://github.com/apgiorgi/awesome-streaming-data-sources) repo, where we employ 'git scraping' on some selected data feeds, using the [Flat Data](https://next.github.com/projects/flat-data) project.

Each data feed has it's own directory and GitHub Actions workflow.

- [NOAA National Data Buoy Center - Latest Observations](http://www.ndbc.noaa.gov/data/latest_obs/latest_obs.txt)

  _"This file has the most recent observation(provided that the observation is less than two hours old)from all stations hosted on the NDBC website. Since this file has multiple stations, it also contains each station's position information (latitude and longitude). The file is relatively small, less than 100KB, and is updated approximately every 5 minutes, so it would be a good data source if you are interested in meteorological observations from multiple stations."_ [More Information](https://www.ndbc.noaa.gov/docs/ndbc_web_data_guide.pdf)

  [💾 Scraped data](./NOAA-NDBC/)

  [🎛 Workflow](.github/workflows/flat-noaa-ndbc.yml)
