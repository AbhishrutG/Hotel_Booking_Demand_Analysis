
# Data Dictionary

This document provides detailed descriptions of each column in the dataset used for the **Hotel Booking Demand and Cancellation Analysis** project.

| Column Name                | Data Type | Description                                                                 |
|----------------------------|-----------|-----------------------------------------------------------------------------|
| `hotel`                    | Categorical | Type of hotel (City Hotel or Resort Hotel).                                |
| `is_canceled`              | Integer    | Indicates whether the booking was canceled (1 = Canceled, 0 = Not Canceled).|
| `lead_time`                | Integer    | Number of days between the booking date and the arrival date.              |
| `arrival_date_year`        | Integer    | Year of arrival date.                                                      |
| `arrival_date_month`       | Categorical | Month of arrival date.                                                    |
| `arrival_date_week_number` | Integer    | Week number of the arrival date.                                           |
| `arrival_date_day_of_month`| Integer    | Day of the month of the arrival date.                                      |
| `stays_in_weekend_nights`  | Integer    | Number of weekend nights (Saturday or Sunday) booked.                      |
| `stays_in_week_nights`     | Integer    | Number of weeknights (Monday to Friday) booked.                            |
| `adults`                   | Integer    | Number of adults.                                                          |
| `children`                 | Integer    | Number of children.                                                        |
| `babies`                   | Integer    | Number of babies.                                                          |
| `meal`                     | Categorical | Type of meal booked (e.g., Breakfast, Full Board).                         |
| `country`                  | Categorical | Country of origin of the customer.                                         |
| `market_segment`           | Categorical | Market segment designation (e.g., Online TA, Offline TA).                 |
| `distribution_channel`     | Categorical | Booking distribution channel (e.g., Direct, Corporate).                   |
| `is_repeated_guest`        | Integer    | Indicates if the customer is a repeated guest (1 = Yes, 0 = No).           |
| `previous_cancellations`   | Integer    | Number of previous bookings canceled by the customer.                      |
| `previous_bookings_not_canceled` | Integer | Number of previous bookings not canceled by the customer.                |
| `reserved_room_type`       | Categorical | Code of the reserved room type.                                            |
| `assigned_room_type`       | Categorical | Code of the assigned room type.                                            |
| `booking_changes`          | Integer    | Number of changes made to the booking.                                     |
| `deposit_type`             | Categorical | Type of deposit made (e.g., No Deposit, Refundable, Non Refundable).       |
| `agent`                    | Integer    | ID of the travel agency that made the booking (0 if none).                 |
| `company`                  | Integer    | ID of the company that made the booking (0 if none).                       |
| `days_in_waiting_list`     | Integer    | Number of days the booking was on the waiting list.                        |
| `customer_type`            | Categorical | Type of customer (e.g., Transient, Contract, Group).                       |
| `adr`                      | Float      | Average Daily Rate per room (calculated as total revenue divided by total nights). |
| `required_car_parking_spaces` | Integer | Number of car parking spaces required.                                     |
| `total_of_special_requests` | Integer   | Total number of special requests made by the customer.                     |
| `reservation_status`       | Categorical | Status of the reservation (e.g., Canceled, Check-Out, No-Show).           |
| `reservation_status_date`  | Date       | Date of the reservation status.                                            |

---

### Notes
- **Categorical Columns**: Represent nominal or ordinal data (e.g., `hotel`, `meal`).
- **Numerical Columns**: Include integers or floats for quantities or rates (e.g., `adr`, `lead_time`).
- **Missing Values**: Some columns (e.g., `children`, `agent`, `company`) contain missing or default values.

---

