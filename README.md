# Number of Rows

Output : 14


# DateTime Range


Output: 2013-07-01 01:14:24 2013-03-22 08:04:00



#Field Names

Output :

['medallion', ' hack_license', ' vendor_id', ' rate_code', ' store_and_fwd_flag', ' pickup_datetime', ' dropoff_datetime', ' passenger_count', ' trip_time_in_secs', ' trip_distance', ' pickup_longitude', ' pickup_latitude', ' dropoff_longitude', ' dropoff_latitude']

# Description of Fields

Output:

medallion: It is a transferable permit in the United States allowing a taxicab driver to operate.

hack_license: Taxi license number.

vendor_id: The unique sequence which is assigned to each vendor in order to establish a record keeping and tracking system.

rate_code: Rate code is taxi's meter setting.

store_and_fwd_flag: This flag indicates whether the trip record was held in vehicle's memory before sending to the vendor, aka "store and forward, because the vehicle did not have a connection to the server.

picup_datetime & dropoff_datetime: Date and time for a particular trip's pickup and dropoff respectively.

passenger_count: Number of customer for that trip.

trip_time_in_secs: Recorded total trip time in seconds.

trip_distance: Recorded total trip distance.

pickup_longitude & pickup_latitude: The exact location from where the passenger were picked.

dropoff_longitude & dropoff latitude: The exact location to where the
passenger were dropped.

# Sample Data
Output:  

| medallion| hack_license| vendor_id| rate_code| store_and_fwd_flag| pickup_datetime| dropoff_datetime| passenger_count| trip_time_in_secs| trip_distance| pickup_longitude| pickup_latitude| dropoff_longitude| dropoff_latitude|
| ---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|------------|
|D1C79CF706C80D3A1DC7FBCA6CD56E43|DAC7742E8F00034774098DBC6B4FF2B7|CMT|1|N|2013-06-03 00:02:12|2013-06-03 00:10:07|1|474|1.30|-73.981583|40.773529|-73.981827|40.782124 3567E8B49FEBFCBB587F1864D723D5C8|430B8022563CDE1D51D44786DFD8D6CB|CMT|1|N|2013-06-03 00:03:03|2013-06-03 00:19:27|1|982|4.90|-73.999565|40.728367|-73.952927|40.729546 4220E1995D36A40DF34664AD33ED13F6|48A1C9C9300AFC7BDBB718CE308EE45A|CMT|2|N|2013-06-03 00:01:30|2013-06-03 00:28:11|1|1745|17.70|-73.788445|40.641151|-73.985451|40.744194 440900089FF528A873424DED689C77A3|E6A63B40E565A8A03AF32E0B138F5EB1|CMT|1|N|2013-06-03 00:04:14|2013-06-03 00:27:50|1|1415|12.10|-73.862816|40.768875|-74.008797|40.738842 |

# Data Types

Output:

| medallion| hack_license| vendor_id| rate_code| store_and_fwd_flag| pickup_datetime| dropoff_datetime| passenger_count| trip_time_in_secs| trip_distance| pickup_longitude| pickup_latitude| dropoff_longitude| dropoff_latitude|
| ---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|------------|
| Varchar(40)|  Varchar(40)| Varchar(5)| Int(2)| Varchar(5)| DateTime(15)| DateTime(15)| Int(5)| Int(5)| float(5)| float(10)| float(10)| float(50)|

# Geographic Range

Output:

Maximum Longitude: 113 160.84689

Minimum Longitude: -736.16669

Maximum Latitude: 404.54999

Minimum Latitude: -180.0

![This is an image](https://github.com/Clarkson-Applied-Data-Science/bhojanha-taxi/blob/main/Part_5.png)

# Harvesine Distance

Output:
Average Haversine Distance = 19.03913105447283

![This is an image](https://github.com/Clarkson-Applied-Data-Science/bhojanha-taxi/blob/main/A1.png)

![This is an image](https://github.com/Clarkson-Applied-Data-Science/bhojanha-taxi/blob/main/Taxi%20Image%202.png)


# Distinct values for each Field

Output:

13461 33382 3 15 4 11 7280 4329 38909 64165 56642 89437


# Min Max Values For Other Numeric Data Types
In the below ouput

rc is rate_code

pc is passenger_count

tis is trip_time_in_secs


td is trip_distance




OutPut:


max_rc:210 , min_rc:1


max_pc:208 ,min_pc:1


max_tis:10800, min_tis:120


max_td:3.9 ,min_td:0.08

#  A chart which shows the average number of passengers each hour of the day

Output:
![This is an image](https://github.com/Clarkson-Applied-Data-Science/bhojanha-taxi/blob/main/Part%209%20.png)

# One out of every thousand Rows

Output:  13971

# Comparison with the 9th Step

Output:

![This is an image](https://github.com/Clarkson-Applied-Data-Science/bhojanha-taxi/blob/main/Taxi%20image%203.png)
