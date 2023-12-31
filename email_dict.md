# Data Description

- The email data set contains user level data from a transportation company.
- The company ran a marketing campaign to encourage users to upgrade their tickets.

## User Level Data

| Variable Name          | Variable Description                                                                          |
|------------------|------------------------------------------------------|
| ID                     | User ID                                                                                       |
| age                    | User's age in years.                                                                          |
| avg_distance           | Average distance (miles) covered during the user's past trips.                                |
| n_purchase             | Total count of transactions made by the user.                                                 |
| discount_purchase      | Count of purchases made by the user using discount codes or promotions.                       |
| n_reward               | Count of purchases where the user redeemed loyalty or reward points.                          |
| n_first_class          | Number of first-class tickets or services purchased by the user.                              |
| n_second_class         | Number of second-class tickets or services purchased by the user.                             |
| n_third_class          | Number of third-class tickets or services purchased by the user.                              |
| n_fourth_class         | Number of fourth-class tickets or services purchased by the user.                             |
| avg_npassengers        | Mean number of passengers included in the user's bookings.                                    |
| avg_price              | Mean transaction value for the user's purchases.                                              |
| sdt_dev_price          | Standard deviation of the prices for all the user's purchases, indicating price variability.  |
| sdt_dev_distance       | Standard deviation of distances for the user's trips, indicating travel distance variability. |
| since_last_purchase    | Days elapsed since the user's latest purchase.                                                |
| n_sent_reminder        | Total count of reminder emails sent to the user.                                              |
| n_open_reminder        | Count of reminder emails opened by the user.                                                  |
| n_click_reminder       | Count of times links within the reminder emails were clicked by the user.                     |
| n_sent_upgrade         | Total count of upgrade offer emails sent to the user.                                         |
| n_open_upgrade         | Count of upgrade offer emails opened by the user.                                             |
| n_click_upgrade        | Count of times links within the upgrade offer emails were clicked by the user.                |
| n_sent_discount        | Total count of discount offer emails sent to the user.                                        |
| n_open_discount        | Count of discount offer emails opened by the user.                                            |
| n_click_discount       | Count of times links within the discount offer emails were clicked by the user.               |
| n_sessions             | Count of web sessions initiated by the user on the platform.                                  |
| n_bounces              | Count of sessions where the user left the website without any interactions.                   |
| n_hits                 | Total interactions or events triggered by the user during web sessions.                       |
| total_session_duration | Cumulative duration (in seconds) of all user's web sessions.                                  |
| total_revenue          | Total monetary value (in dollars) generated from the user's transactions.                     |
| conversions            | Count of successful conversions or target actions achieved by the user.                       |
| n_search               | Total search operations initiated by the user on the website.                                 |
| n_path                 | Count of unique routes or navigation patterns taken by the user on the platform.              |

------------------------------------------------------------------------

## Data on current upgrade promotion

| Variable Name          | Variable Description                                                                          |
|------------------|------------------------------------------------------|
|price | Current price of the ticket in consideration.|
|days_2_trip| Gap in days between the current date and the scheduled trip date.|
|is_second_class| Binary indicator signifying if the user's current booking is of the second class (1 for Yes, 0 for No).|
|distance| Linear distance (in miles) between the starting point and destination of a given trip.|
|upgrade_price| Cost associated with upgrading the current ticket.|
|success| Binary indicator reflecting if whether the customer chose to upgrade by paying upgrade_price.|
