# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## NAME : NIRUDHI A
## REG NO : 212224223003
## DEPT : INFORMATION TECHNOLOGY
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
11. Send control commands from the dashboard to control the relay.
<img width="1919" height="1128" alt="Screenshot 2026-03-17 123722" src="https://github.com/user-attachments/assets/c8381a08-4d74-4043-ae1e-48d7c05e3d8e" />
<img width="1918" height="1126" alt="Screenshot 2026-03-17 123741" src="https://github.com/user-attachments/assets/2ee3184b-41df-4c10-b053-433f2ace1974" />
<img width="1919" height="1139" alt="Screenshot 2026-03-17 123820" src="https://github.com/user-attachments/assets/6a15c774-d70b-48a3-a734-43ff81b4f92c" />
<img width="1915" height="1139" alt="Screenshot 2026-03-17 123905" src="https://github.com/user-attachments/assets/93ca8471-2504-403e-8ba8-7a774979dcf4" />
<img width="1919" height="1140" alt="Screenshot 2026-03-17 123929" src="https://github.com/user-attachments/assets/435025ed-d1e8-4c14-a52c-0c2208719aca" />
<img width="1919" height="1140" alt="Screenshot 2026-03-17 124116" src="https://github.com/user-attachments/assets/664935a7-b4f8-4aa4-a51a-3a2d49c4bc9d" />
<img width="1919" height="1141" alt="Screenshot 2026-03-17 124140" src="https://github.com/user-attachments/assets/c879eb56-f95a-4f27-86c0-4f450e2514bf" />
<img width="1919" height="1138" alt="Screenshot 2026-03-17 124402" src="https://github.com/user-attachments/assets/be94744c-39f3-4535-9e13-bf350a2336a9" />

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171508" src="https://github.com/user-attachments/assets/56faf8ee-f0f6-4b3f-a65d-58d6cd79809d" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171532" src="https://github.com/user-attachments/assets/aa6781c2-118d-40af-87f1-a4998aea3e95" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171550" src="https://github.com/user-attachments/assets/0f9e5552-2693-4ec8-b613-7e470b56dd71" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171616" src="https://github.com/user-attachments/assets/68470057-8ad9-40c7-b553-bc7863ab293b" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171635" src="https://github.com/user-attachments/assets/cae55c70-6b73-496f-b672-efcd02f8bac7" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171711" src="https://github.com/user-attachments/assets/9b14ef3b-42dd-41ae-a0ae-a2346f9b5e1c" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171752" src="https://github.com/user-attachments/assets/8f54f901-9d10-4ed0-a6f1-61e0e4977550" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171822" src="https://github.com/user-attachments/assets/c46c0e83-f35d-4e0a-b760-02aeac4e274d" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 171843" src="https://github.com/user-attachments/assets/45def0b8-6996-49c6-b7e3-3bbbc8fa7d8b" />

### 2. Network Server – Recent Events
<img width="1919" height="1138" alt="IOT 6 ON RE" src="https://github.com/user-attachments/assets/e1c6e5f9-6ec8-4f73-a6d6-f82c6280faad" />
<img width="1919" height="1140" alt="IOT 6 RE OFF" src="https://github.com/user-attachments/assets/eaf97d8d-5ecb-41fe-ae89-1db8ef4e4581" />

### 3. Dashboard Command Sending
<img width="1920" height="1200" alt="Screenshot 2026-03-20 100504" src="https://github.com/user-attachments/assets/76af7ee9-281e-4208-9fe6-f0f438f19363" />

### 4. Relay Status Dashboard Output

<img width="1919" height="1139" alt="IOT 6 ON" src="https://github.com/user-attachments/assets/96d9c5d2-fd60-4ed4-95ea-346b9352d2a9" />
<img width="1919" height="1141" alt="IOT 6 OFF L" src="https://github.com/user-attachments/assets/e4cd4520-df59-4b2d-8cae-7d5a54162b9d" />
### Bulb ON → Relay ON 
![WhatsApp Image 2026-03-20 at 10 15 33 AM (1)](https://github.com/user-attachments/assets/03e4981b-26d9-45fd-a8f0-f254652a4d2c)


### Bulb OFF → Relay OFF

![WhatsApp Image 2026-03-20 at 10 15 33 AM](https://github.com/user-attachments/assets/08a4e14e-1427-4ed9-b771-fe4beae031f1)

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
