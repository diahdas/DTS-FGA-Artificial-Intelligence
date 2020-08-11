# Demand Prediction
The given dataset contains normalized historical demand of a city, aggregated spatiotemporally within geohashes and over 15 minute intervals. The dataset spans over a two month period. A brief description of the dataset fields are found below:
| Features | Descriptions |
|-|-|
|Geohash6|Geohash level 6. Geohash is a public domain geocoding system which encodes a geographic location into a short string of letters and digits with arbitary precision.|
|Day| Day, where the value indicates the sequential order and not a particular day of the month|
|Timestamp|Start time of 15-minute intervals, in the following format: <hour>:<minute>, where hour ranges from 0 to 23 and minute is either one of (0, 15, 30, 45)|
|Demand|Aggregated demand normalized to be in the range [0,1]|


Source dataset: aiforsea.com/traffic-management
