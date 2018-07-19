# QR-Hotspots
A multi platform application for ( Hotspots / Bluetooth ) security using QR codes as credentials for connection.

The project aims to create a safe hotspot / bluetooth connection, using single use randomly generated QR codes that are created by the host and then scanned by the "Client", allowing them to connect for one session and locking permission for one client per QR code.

Use Scenario demonstrating how this will work.
- Two users wish to connect to each other in hotspot or bluetooth scenario.
- Both users open up the QR-Hotspots Application.
- The host prompts the Application to generate a random one time use QR Code.
- The client then scans this QR code.
- Both devices become connected.
- The QR code used in the process is deemed expired thereafter.
- Upon disconnect from either side, The process needs a new QR code to repeat a connection.
