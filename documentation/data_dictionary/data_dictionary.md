Data Dictionary – Ad Campaign Performance Dataset
Raw Data Fields

    ad_id - Unique identifier assigned to each individual advertisement.

    campaign_name - Name of the advertising campaign under which the ad was run.

    campaign_category - Classification of the campaign objective (e.g., Awareness, Traffic, Conversions).

    ad_type - Format of the advertisement such as Image, Video, or Carousel.

    platform - Digital platform where the advertisement was displayed (e.g., Facebook, Google, Instagram).

    reporting_date - Date on which the ad performance metrics were recorded.

    age_group - Age range of the targeted audience segment.

    gender - Gender category of the targeted audience.

    impressions - Number of times the advertisement was displayed to users.

    clicks - Number of times users clicked on the advertisement.

    conversions - Number of completed desired actions resulting from the advertisement.

    spend - Total cost incurred in running the advertisement.

    conversion_value - Revenue generated from the recorded conversions.

Derived Metrics (Calculated Measures)

    Click-Through Rate (CTR) - Measures the proportion of impressions that resulted in clicks.
    Formula:
        CTR = clicks / impressions


    Cost Per Click (CPC) - Represents the average cost incurred for each click.
    Formula:
        CPC = spend / clicks


    Conversion Rate - Measures the proportion of clicks that resulted in conversions.
    Formula:
        Conversion Rate = conversions / clicks


    Return on Investment (ROI) - Measures the profitability of advertising spend.
    Formula:
        ROI = (conversion_value - spend) / spend


    Total Revenue - Total monetary value generated from conversions.
    Formula:
        Total Revenue = SUM(conversion_value)
