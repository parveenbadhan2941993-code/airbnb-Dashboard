**Overview**

This Power BI dashboard analyzes Airbnb listings across 10 cities, focusing on growth trends, pricing patterns, ratings, user engagement, and host verification.

**Key Metrics**

*   Listings: 279,712
*   Hosts: 182,024
*   Cities: 10
*   Listing Types: 144
*   Reviews: 5.37K

**Insights**

**Growth Trends**

*   Slow growth between 2008–2010
*   Rapid expansion during 2015–2016
*   Decline after 2017
*   Significant drop in 2020

**Market Distribution**

*   Listings are concentrated in a few major cities
*   Paris and New York dominate total supply
*   Top cities contribute ~58.3% of listings

**Pricing**

*   Hotel rooms have the highest average price
*   Entire homes follow
*   Private and shared rooms are lower-priced segments

**Ratings**

*   Ratings are consistent across cities (9.2–9.7)
*   Strong performance in cleanliness, communication, and location

**User Behavior**

*   86.5% of users leave only one review
*   Repeat engagement is limited
*   A small group of users contributes a large share of reviews

**Host Verification**

*   Verified identity + profile picture → high trust
*   No verification + no profile picture → low trust
*   Mixed combinations indicate partial credibility

**DAX Logic (Generalized)**

**Aggregations**

*   Total count = count of rows
*   Distinct count = count of unique IDs

**Averages**

*   Average rating = mean of score columns

**Segmentation**

*   Conditional count = count with filters applied (e.g., by category or type)

**Ranking**

*   Rank = assign order based on a measure (descending) across all categories

**Cumulative Analysis**

*   Running total = cumulative sum based on ordered dimension
*   Cumulative percentage = cumulative value ÷ total value

**Reviewer Analysis**

*   Reviews per user = total reviews grouped by user
*   Cumulative reviewers = running distinct count based on review frequency

**Filtering / Flags**

*   Conditional flag = return 1 or 0 based on defined thresholds

**Ratio Calculations**

*   Percentage = segment value ÷ total value

**Tools**

*   Power BI
*   DAX

**Usage**

Open the .pbix file in Power BI Desktop and navigate through Overview, Ratings, and Reviews pages to explore the dashboard.