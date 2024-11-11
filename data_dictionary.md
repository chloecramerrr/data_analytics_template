# Data Dictionary for AB_NYC_2019 Dataset

| Column Name                       | Data Type  | Description                                                                                       |
|-----------------------------------|------------|---------------------------------------------------------------------------------------------------|
| `id`                              | Integer    | Unique identifier for each listing.                                                               |
| `name`                            | String     | Name of the Airbnb listing.                                                                       |
| `host_id`                         | Integer    | Unique identifier for each host.                                                                  |
| `host_name`                       | String     | Name of the host.                                                                                 |
| `neighbourhood_group`             | String     | The borough group of the listing (e.g., Brooklyn, Manhattan).                                     |
| `neighbourhood`                   | String     | Specific neighborhood within the borough.                                                         |
| `latitude`                        | Float      | Latitude coordinate of the listing's location.                                                    |
| `longitude`                       | Float      | Longitude coordinate of the listing's location.                                                   |
| `room_type`                       | String     | Type of room offered (e.g., Entire home/apt, Private room, Shared room).                          |
| `price`                           | Integer    | Price per night for the listing in USD.                                                           |
| `minimum_nights`                  | Integer    | Minimum number of nights required for a booking.                                                  |
| `number_of_reviews`               | Integer    | Total number of reviews the listing has received.                                                 |
| `last_review`                     | Date       | Date of the most recent review.                                                                   |
| `reviews_per_month`               | Float      | Average number of reviews per month.                                                              |
| `calculated_host_listings_count`  | Integer    | Number of listings by the host.                                                                   |
| `availability_365`                | Integer    | Number of days within a year that the listing is available for booking.                           |


