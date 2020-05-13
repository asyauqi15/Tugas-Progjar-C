## Tabel
### server_async_http.py
| Concurrency level | Time taken for test (seconds) | Complete request | Failed request | Total transferred (bytes) | Request per second | Time per request (ms) | Transfer rate (Kbytes/sec) |
|:-----------------:|:-----------------------------:|:----------------:|:--------------:|:-------------------------:|:------------------:|:---------------------:|:--------------------------:|
|1|4.035|1000|0|122000|247.80|4.035|29.52|
|10|71.940|1000|0|122000|13.90|719.396|1.66|
|50|71.978|1000|0|122000|13.89|3598.889|1.66|
|100|71.930|1000|0|122000|13.90|7193.010|1.66|
### server_thread_http.py
| Concurrency level | Time taken for test (seconds) | Complete request | Failed request | Total transferred (bytes) | Request per second | Time per request (ms) | Transfer rate (Kbytes/sec) |
|:-----------------:|:-----------------------------:|:----------------:|:--------------:|:-------------------------:|:------------------:|:---------------------:|:--------------------------:|
|1|197.899|1000|0|122000|5.05|197.899|0.60|
|10|251.300|1000|0|122000|3.98|2512.996|0.47|
|50|250.319|1000|0|122000|3.99|12515.956|0.48|
|100|301.136|1000|0|122000|3.32|30113.581|0.40|