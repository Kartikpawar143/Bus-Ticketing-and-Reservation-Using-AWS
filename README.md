# Bus Ticketing, Reservation and Payment System Using AWS Window Instance. <br>

<h2>Passengers can buy bus or railway tickets on our platform. We are using AWS EC2 service for that.</h2> <br>

<h3>Process Given Below: </h3><br><br>

Open AWS Console and search EC2. <br>

![Screenshot 2025-01-26 235055](https://github.com/user-attachments/assets/7cbd659b-4473-451c-a324-8d3b6c4e3894)

Click on Launch Instance. <br>

![Screenshot 2025-01-26 235109](https://github.com/user-attachments/assets/beb8a70e-d8c7-4bd3-97a8-8e7c8c95a90f)

Give name to the instance "Instance-A" and select the Amazon Image Machine "Windows". <br>

![Screenshot 2025-01-26 235349](https://github.com/user-attachments/assets/ac85a354-4f94-4620-a234-f154934ad73b)

Select instance type "t3 micro" and key pair. <br>

![Screenshot 2025-01-26 235405](https://github.com/user-attachments/assets/6bf058e9-447e-436b-8324-9b628db8d3d6)

Configure network setting. <br>
Allow RDP,HTTP or HTTPS trafic. <br>

![Screenshot 2025-01-26 235414](https://github.com/user-attachments/assets/8b3e7d7d-7b8a-47a8-8e93-d8e0f84fa88c)

Configure Storage. <br>

![Screenshot 2025-01-26 235428](https://github.com/user-attachments/assets/29761e36-aa7d-4723-8f1a-7d80a9799eab)

Launch Instance. <br>

![Screenshot 2025-01-26 235455](https://github.com/user-attachments/assets/3d46f565-31de-4497-a0a5-95703ca0d472)

Connect to instance using RDP client. <br>

![Screenshot 2025-01-27 001245](https://github.com/user-attachments/assets/c15fe667-c5f2-45f3-a298-abaadbce7944)

Download remote desktop file. <br> 

![Screenshot 2025-01-27 001301](https://github.com/user-attachments/assets/4ad5fcf8-8fe6-4ec3-9ea4-e22cea555cea)

Upload the key pair to get the password. <br>

![Screenshot 2025-01-27 001519](https://github.com/user-attachments/assets/93f23f94-aeb7-47d8-a009-4ac26b34b06b)

Select the key pair. <br>

![Screenshot 2025-01-27 001529](https://github.com/user-attachments/assets/256f3721-5326-4f3c-a0a9-4775fc000233)

Click on Decrypt password. <br>

![Screenshot 2025-01-27 001539](https://github.com/user-attachments/assets/d46c34fb-48fa-4649-a884-b0ef9406891c)

Copy password. <br>

![Screenshot 2025-01-27 001605](https://github.com/user-attachments/assets/f23d5aa6-3d70-42f8-ab23-517b8cb343db)

Open the download remote desktop. <br>

![Screenshot 2025-01-27 001341](https://github.com/user-attachments/assets/3ecfcc61-1663-45e2-a65c-2662df08f7c5)

Enter the password. <br>

![Screenshot 2025-01-27 001635](https://github.com/user-attachments/assets/2e9386cf-228c-4f72-9bd6-6fb3196a6881)

Click yes. <br>

![Screenshot 2025-01-27 001648](https://github.com/user-attachments/assets/64737d42-519d-4992-9ca1-8d5edbeefa82)

Window AMI will open. <br>

![1](https://github.com/user-attachments/assets/96dc8820-52d7-4c12-ab55-a701c9872a2e)

Search xampp download. <br>

![2](https://github.com/user-attachments/assets/745becdb-54a5-4dc4-9f50-c268bf4e8da7)
![3](https://github.com/user-attachments/assets/f0780cbc-c577-4983-804d-8812e9d6c5f2)
![27 01 2025_00 18 53_REC](https://github.com/user-attachments/assets/a49199dc-9194-487c-abc3-5bd7276e3271)

By following the below path of file, copy the source code in that folder. <br>

![27 01 2025_00 20 43_REC](https://github.com/user-attachments/assets/0ccb1279-7abc-4c8a-97e7-eb2bea50b426)
![27 01 2025_00 21 06_REC](https://github.com/user-attachments/assets/9171401e-3249-433e-995d-feb06c0234b9)
![27 01 2025_00 21 31_REC](https://github.com/user-attachments/assets/1d06251b-4c78-4db7-a9a9-4e3b20da1020)
![27 01 2025_00 22 21_REC](https://github.com/user-attachments/assets/793f89ff-ad98-481a-a646-07e26ffa518b)

After that, open XAMPP and start Apache and MySql module. <br>

![27 01 2025_00 26 10_REC](https://github.com/user-attachments/assets/8e3efa5d-fed3-4e91-aadc-cd77fc6fc655)

Go to the admin of the xampp and then the xampp dashboard wil open. <br>

![27 01 2025_00 26 30_REC](https://github.com/user-attachments/assets/be6278b1-6de4-42e0-8456-f9c8f80109cb)
![27 01 2025_00 26 48_REC](https://github.com/user-attachments/assets/a7515853-7554-461b-bd61-598cee95551a)

Click on the phpMyAdmin of that dashboard and create new database named by train. <br>

![27 01 2025_00 27 42_REC](https://github.com/user-attachments/assets/25a990ee-5872-4bfe-96ec-5fe9034346de)
![27 01 2025_00 28 17_REC](https://github.com/user-attachments/assets/83314f47-de0c-4e90-8be7-6e18b53add06)

Then import the train.sql file which is in the source code. <br>

![27 01 2025_00 28 45_REC](https://github.com/user-attachments/assets/5f17b839-4d1e-454f-bf1c-f4efb6032a8e)
![27 01 2025_00 31 13_REC](https://github.com/user-attachments/assets/020c6853-357d-44d5-a1b5-982f8f4e10fd)

After this, <br>
open new web page and type localhost/Mumbai-Local-Train-Ticket-Booking-main at there. <br>

![27 01 2025_00 33 27_REC](https://github.com/user-attachments/assets/07aa02ca-137b-4b7f-873f-d442de76880b)

Here we have created our Bus Ticket or Railway Ticket booking application with the payment system, Bus Schedules, Train Schedules, etc. <br>

![27 01 2025_00 34 07_REC](https://github.com/user-attachments/assets/2ac3db29-0946-4099-a8be-4cabc72516d3)
![27 01 2025_00 36 16_REC](https://github.com/user-attachments/assets/93da21fb-77a9-48dc-b0a3-95e9e2989d7e)
![27 01 2025_00 37 24_REC](https://github.com/user-attachments/assets/8662fbee-e51a-487a-afd4-49cab57da0a5)
![27 01 2025_00 38 07_REC](https://github.com/user-attachments/assets/ae5ccfa4-a2eb-4072-bb46-ddc2484b2b48)
![27 01 2025_00 38 56_REC](https://github.com/user-attachments/assets/1f4bf830-e5fd-497f-b16c-c754b80944f5)
![27 01 2025_00 39 15_REC](https://github.com/user-attachments/assets/2d71020a-313a-48fa-86da-2e691f4ae3df)

