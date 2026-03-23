# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1920" height="1200" alt="Screenshot (442)" src="https://github.com/user-attachments/assets/d18336bd-6cc8-4997-b4cb-4132dbd6d30e" />
<img width="1920" height="1200" alt="Screenshot (443)" src="https://github.com/user-attachments/assets/1786cba0-7087-45ef-868f-d08871cbfd67" />
<img width="1920" height="1200" alt="Screenshot (444)" src="https://github.com/user-attachments/assets/38951be3-ca69-4df0-ba88-cb6bf4c579df" />
<img width="1920" height="1200" alt="Screenshot (445)" src="https://github.com/user-attachments/assets/df3befbb-0338-47d8-a34a-a7fe9e06b18b" />
<img width="1920" height="1200" alt="Screenshot (446)" src="https://github.com/user-attachments/assets/8cd00059-6394-451b-b518-0672fe426623" />



### 2. Network Server – Recent Events
<img width="1920" height="1200" alt="Screenshot 2026-03-23 173713" src="https://github.com/user-attachments/assets/abc9b15e-24ab-4582-9f03-08ecf2a7a833" />
<img width="1892" height="1002" alt="Screenshot 2026-03-23 174216" src="https://github.com/user-attachments/assets/b64d30a9-b4a9-49fb-a2b4-c7a4854433ca" />



### 3. Dashboard Command Sending

-

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1884" height="1020" alt="Screenshot 2026-03-23 174448" src="https://github.com/user-attachments/assets/bf89270c-875f-4e01-9a46-834e9bd737a0" />
### Bulb OFF → Relay OFF
<img width="1900" height="1026" alt="Screenshot 2026-03-23 174350" src="https://github.com/user-attachments/assets/415b8867-5f06-45d5-9265-e2c06caed3fc" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
