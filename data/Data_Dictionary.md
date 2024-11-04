# Data Dictionary
- [Data Dictionary](#data-dictionary)
  - [Columns and data types](#columns-and-data-types)

Both files contain similar data. The ```example_networks.csv``` file is missing the product columns.
## Columns and data types
|Column     |Type          |Description                  |
|-----------|--------------|-----------------------------|
acct_id	| string	| A unique account ID given to an individual customer
extenders |	bigint	| The number of wireless extenders currently in the home
wireless_clients_count |	bigint	| The number of WIFI-connected devices on the custoemr network.
wired_clients_count	| bigint | The number of devices using wired connections (vs. WIFI). These can sometimes be gaming systems or servers but frequently are cabled in order to recieve the best network quality and highest speeds.
rx_avg_bps |	double| The average Bits Per Second received (from the device, to the Internet) of all devices in the network
tx_avg_bps |	double | The average Bits Per Second transmitted (to the device, from the Internet) of all devices in the network
rx_p95_bps |	double| The 95th percentile Bits Per Second received (from the device, to the Internet) of all devices in the network
tx_p95_bps |	double | The 95th percentile Bits Per Second transmitted (to the device, from the Internet) of all devices in the network
rx_max_bps |	double | The maximum Bits Per Second received (from the device, to the Internet) of all devices in the network
tx_max_bps |	double | The average Bits Per Second transmitted (to the device, from the Internet) of all devices in the network
rssi_mean |	double | The average RSSI (Received Signal Strength Indicator) which is a measure of how well a device receives a signal, shown as a negative dBm value.
rssi_median |	bigint | The median RSSI (Received Signal Strength Indicator) which is a measure of how well a device receives a signal, shown as a negative dBm value.
rssi_max |	bigint | The maximum RSSI (Received Signal Strength Indicator) which is a measure of how well a device receives a signal, shown as a negative dBm value.
rssi_min |	bigint | The minimum RSSI (Received Signal Strength Indicator) which is a measure of how well a device receives a signal, shown as a negative dBm value.
network_speed |	string | The speed of the customers **current** Internet connection in Megabits Per Second. E.g., 1000M = 1 Gig.
city |	varchar(32) | The customer's City
state |	varchar(2) | The customer's State
whole_home_wifi |	boolean | The customer has the "Whole Home WIFI" product
wifi_security |	boolean	| The customer has the "WIFI Security" product
wifi_security_plus |	boolean	| The customer has the "WIFI Security+" product
premium_tech_pro |	boolean	| The customer has the "Premium Tech Pro" product
identity_protection |	boolean	| The customer has the "Identity Protection" product
family_identity_protection | boolean	| The customer has the "Family Identity Protection" add-on product
total_shield |	boolean	| The customer has the "Total Shield" product
youtube_tv |	boolean	| The customer has the "YouTube TV" product
