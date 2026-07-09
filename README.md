# Porfolio---DataBaseSQL
**A database for managing hotel bookings**

**Database structure**:

1) **__Tables__**

**Rooms** 
- ID
- Number
- Category
- Capacity
- Price per night
- Status

**Guests** 
- ID
- FULL NAME
- Phone number
- City

**Bookings** 
- ID
- Guest_ID 
- Number_ID 
- Check-in date
- Departure date
- Status

**Payments** 
- ID
- Booking_ID 
- Amount
- Way of Payment
- Payment date

 **Communications**
- Bookings.Guest_ID -> Guests.ID
- Bookings.Number_ID -> Rooms.ID
- Payments.Booking_ID -> Bookings.ID

**SQL queries**

The project has written queries:

1. All bookings with guest number and room number
2. The number of armor each guest has
3. Available rooms
4. Bookings with the "Confirmed" status

 **Tools**
- Microsoft Access, SQL

**How to use**
1. Open the `Hotel.accdb` file
2. Run the required query in SQL or Constructor mode
