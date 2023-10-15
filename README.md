# data-512-hw

## Project Goals:

The purpose of this project is to demonstrate the principles of Professionalism and Reproducibility through some data pulling and analysis. 

## Sources:

* Wikimedia Foundation REST API: https://www.mediawiki.org/wiki/API:REST_API#Terms_and_conditions
* Example Code: This code example was developed by Dr. David W. McDonald for use in DATA 512, a course in the UW MS Data Science degree program. This code is provided under the Creative Commons CC-BY license. Revision 1.2 - August 14, 2023
* Pandas Documentation: https://pandas.pydata.org/docs/
* MatPlotLib Documentation: https://matplotlib.org/2.0.2/api/pyplot_api.html


## Data Files

All of the data files in this project are created in the Data Acquisition Notebook. The Images of the Visuals are created in the Visualization Notebook.

1. academy_monthly_mobile_20150701-20230930.json
Description:

This file contains monthly pageviews of movies on English Wikipedia from both mobile-web and mobile-app access methods.
Fields:

    Movie Title (e.g., "Everything Everywhere All at Once"):
        items: List of monthly pageviews for the movie.
            project: The Wikimedia project (e.g., "en.wikipedia").
            article: Article title, URL encoded.
            granularity: Level of time granularity (e.g., "monthly").
            timestamp: YYYYMMDDHH formatted time when data was recorded.
            access: Access method (e.g., "mobile-web" or "mobile-app").
            agent: Type of user (e.g., "user").
            views: Number of pageviews for that month.

2. academy_monthly_desktop_202001-202303.json
Description:

This file contains monthly pageviews of movies on English Wikipedia from desktop access.
Fields:

    Movie Title (e.g., "Everything Everywhere All at Once"):
        items: List of monthly pageviews for the movie.
            project: The Wikimedia project (e.g., "en.wikipedia").
            article: Article title, URL encoded.
            granularity: Level of time granularity (e.g., "monthly").
            timestamp: YYYYMMDDHH formatted time when data was recorded.
            access: Access method (e.g., "desktop").
            agent: Type of user (e.g., "user").
            views: Number of pageviews for that month.


3. academy_monthly_cumulative_20150701-20230930.json
Description:

This file contains cumulative monthly pageviews of movies on English Wikipedia from all access methods combined.
Fields:

    Movie Title (e.g., "Everything Everywhere All at Once"): A list of dictionaries, each representing a month's pageview data.
        timestamp: YYYYMMDDHH formatted time indicating the start of the month when data was recorded.
        views: Cumulative number of pageviews for that month.







