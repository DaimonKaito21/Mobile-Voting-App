• MOBILE APPLICATION

- A mobile app that needs to scans a QR Code before it can access the Mobile Application.

- The scanned QR Code needs to be registered first before the polling hours.

-A maximum of 3 voters/users only can use one MAC Address. When the voter exceeds the maximum use, the mobile app will be disabled. 
(The system will automatically check each MAC Address).

- When the voter finished submitting their preferred candidates, the mobile app will show the summary of votes.

- Uses check boxes in choosing voters' preferred candidates.

- Once the polling hours is enabled, the Mobile app will be enabled also. A mobile app that can store their mac address on the main server.

- A mobile app that will be enabled only on the scheduled polling hours. 

• LOCAL SERVER (Raspberry Pi Model B+)

- The device that will be used on the voter's registration, which is connected to a QR Code scanner. Its function is for voter registration only. Every scanned QR Code will be sent to the main server and will be stored in a Database.

• MAIN SERVER  (Raspberry Pi 3 Model B+)

- The main server can be accessed by the authorized officials only

- Only the authorized official can access the main server, the authorized official needs to create an account. If they already have an account they can now input the bona fide candidates. 

- The main server can automatically count the number of votes during and after the polling day, and can export it through excel.

- The main server that can calculate the overall result per candidate that can be exported through excel 
(Ex. Candidate A got 500 votes, Candidate B got 250. It means to if Candidate A won, Candidate A's voters can be seen and in just one click. Votes can be exported through excel) 

- The admin can set the start and end of the polling hours.

- The main server can update the mobile application.

- Once the polling hours is enabled, the Mobile app will also be enabled. The main server will store the mac address on the database. The app will detect the MAC address of the users, as well as its history.

Note that the same MAC address cannot be used again after 3 votes.
