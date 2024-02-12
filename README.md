# hotel room cancellation in ms excel

#Aim : TO FIND WHY CUSTOMERS CANCELLED THE HOTEL ROOM BOOKINGS AND HOW MANY CUSTOMERS CANCELLED THE BOOKINGS IN LAST 3 YRS

#About data
data is obtained from kaggle.com(https://www.kaggle.com/datasets/mojtaba142/hotel-booking)

#analysis :
1. analyze the data by using power query in excel(null values,duplicate values,delete unwanted rows and columns)

2. create 2 new columns as guest_type and room_status

3. room_status column shows that customer got their assigned room or not and find this by using if formula(=IF([@[reserved_room_type]]=[@[assigned_room_type]],"desired","un-desired")

4. guest_type column indicates that which type of customers booked hotel rooms like couple,family,single and find this by using if formula(=IF(AND(E10=2,F10=0,G10=0),"couples",IF(AND(E10=1,F10=0,G10=0),"single","family"))

5. crate pivot tables for making dashboard.
