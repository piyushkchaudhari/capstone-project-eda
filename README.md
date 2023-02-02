# HOTEL BOOKING ANALYSIS
### This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
### Explore and analyze the data to discover important factors that govern the bookings
# Dataset
- hotel: Name of hotel 
- is_canceled: Whether the booking is canceled or not 
- lead_time: time between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.
# Exploratory Data Analysis
- 1)  which type of hotel booking cancel a most
- 2)  what is an average of daily price per month
- 3)  hotel booking of each month
- 4)  which segment is costumer belong to most per year
- 5)  which type of meal seals a most
- 6)  how many guest stay in hotel per year
- 7)  From which country most guest come
- 8)  how many guest is repeated 
- 9)  which type of room guest most prefered
- 10) what is a most guest demands from hotel 
- 11) how many hotel booking canceled per month
- 12) which hotel prefered by which type of guest
### Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

- Bar Plot.
- Pie Chart.
- Line Plot.
- Heatmap.
- Box Plot 
![Screenshot 2023-02-02 122926](https://user-images.githubusercontent.com/123857050/216254704-2d2cf506-6b10-464b-bd53-bd93cbd60035.png)
# Conclusion
- Given that we do not have repeated guests, we should target our advertisement on guests to increase returning guests.
- Given that most of the guest are adults for both hotels then for improving return guest provide goods that adult guest like.
- Most of the hotel bookings come from online segment . We should spend a significant amount for online advertisement.
- Most of the hotel bookings come from Portugal and united Kingdom. We should spend a significant amount of our budget on those area.
- We can see most of the people prefered bb and hb meal but in city hotel most of the people prefered bb and sc meal. Then for satisfaction of guest sepend money on advertisement of bb ,hb and sc meal
- It seems city hotels got 42% cancel orders and resort hotels got 28% cancel orders
- It seems city hotels get more cancel orders than resort hotels.most of the cancel order come from may , july and august month
Most of the guest preferred room type A,D and E . we should develop this type of more rooms and improving service of this type of rooms.
