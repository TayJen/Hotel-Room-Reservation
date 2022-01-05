# Hotel-room-reservation
## Project Description
To attract customers, the hotel chain has added to its website the ability to book a room without prepayment. However, if the customer cancelled the booking, the company suffered losses. The hotel staff could, for example, buy groceries for the arrival of a guest or simply not have time to find another client.

To solve this problem, we need to develop a system that predicts the rejection of armor. If the model shows that the reservation will be canceled, the client is invited to make a deposit. The deposit amount is 80% of the room rate for one day and the cost of a one-time cleaning. The money will be debited from the client's account if he still cancels the reservation.

The hotel_train and hotel_test tables contain the same columns:
- id - record number;
- adults - number of adult guests;
- arrival_date_year - year of arrival;
- arrival_date_month - month of arrival;
- arrival_date_week_number - arrival week;
- arrival_date_day_of_month - day of arrival;
- babies - number of babies;
- booking_changes:
  - the number of changes to the order parameters;
- children:
  - number of children from 3 to 14 years old;
- country - citizenship of the guest;
- customer_type - type of the customer:
- Contract - contract with a legal entity;
- Group - group check-in:
- Transient - not related to a contract or a group check-in;
- Transient-party - is not related to a contract or a group check-in, but is related to a booking of the Transient type.
- days_in_waiting_list - how many days the order was waiting for confirmation;
- distribution_channel - order distribution channel;
- is_canceled - order cancellation;
- is_repeated_guest - indicates that the guest is booking a room for the second time;
- lead_time - the number of days between the booking date and
- the arrival date;
- meal - order options:
  - sc - no additional options;
  - bb - breakfast included;
  - Hb - breakfast and lunch included;
  - breakfast, lunch and dinner are included.
- previous_bookings_not_canceled -
  - the number of confirmed orders from the client;
  - previous_cancellations - the number of cancelled orders from the client;
- required_car_parking_spaces - the need for a place for the car;
- reserved_room_type - type of the reserved room;
- stays_in_weekend_nights - number of nights on weekends;
- stays_in_week_nights - number of nights on weekdays;
- total_nights - total number of nights;
- total_of_special_requests - the number of special marks.
