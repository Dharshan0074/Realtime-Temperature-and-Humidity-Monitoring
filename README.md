🌡️ IoT Temperature & Humidity Monitoring with NodeMCU, DHT22 & Firebase
🔧 Project Overview
This project uses a NodeMCU (ESP8266) microcontroller and a DHT22 temperature and humidity sensor to collect environmental data and send it to a Firebase Realtime Database for live monitoring from anywhere in the world.

🧰 Components Used
NodeMCU (ESP8266)

DHT22 Temperature & Humidity Sensor

Jumper wires

Internet connection (Wi-Fi)

Firebase Realtime Database

⚙️ How It Works
The DHT22 sensor is connected to the NodeMCU via jumper cables.

The NodeMCU is programmed using the code available in this repository.

Before uploading the code:

Replace the SSID and Password with your Wi-Fi credentials.

Update the Firebase project details (database URL and credentials).

Once powered and connected to Wi-Fi, the NodeMCU:

Reads temperature and humidity values from the DHT22.

Sends the data to Firebase over the internet.

You can view the live data from anywhere via Firebase’s Realtime Database console.
