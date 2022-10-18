#Part 1

```
import csv
#https://drive.google.com/file/d/13gclMmH86q8pwj0qUfTbAjl595B2rov6/view?usp=sharing
from google.colab import drive
drive.mount('/content/gdrive')
from google.colab import files
#uploaded = files.upload()
#import io
#reader = pd.read_csv(io.BytesIO(uploaded['Filename.csv']))

#fn = 'trip_data_6.csv'

f = open('gdrive/My Drive/trip_data_12.csv', 'r')
reader = csv.reader(f)
n = 0
for row in reader:
    print(row)
    print(len(row))
    n+=1
    if n ==2:
        break

```

Output: ['medallion', ' hack_license', ' vendor_id', ' rate_code', ' store_and_fwd_flag', ' pickup_datetime', ' dropoff_datetime', ' passenger_count', ' trip_time_in_secs', ' trip_distance', ' pickup_longitude', ' pickup_latitude', ' dropoff_longitude', ' dropoff_latitude']
14
['D7D598CD99978BD012A87A76A7C891B7', '82F90D5EFE52FDFD2FDEC3EAD6D5771D', 'VTS', '1', '', '2013-12-01 00:13:00', '2013-12-01 00:31:00', '1', '1080', '3.90', '-73.97934', '40.776653', '-73.981865', '40.73428']
14
