# SOP-ServiceDiscovery_LAB

#### Service Dashboard


![Alt text](https://github.com/TheMhee/SOP-ServiceDiscovery_LAB/blob/main/image.PNG?raw=true "Title")

## การรันApplication
1. รันApplication Server
2. รันClient ที่ต้องการให้อยู่กับตัวServer
3. เข้าDashboard ผ่าน path "http://localhost:8761/instances" (port 8761 คือ default port)

## สถานะของ Instance
* เมื่อมีClient service ทำงานอยู่จะแสดงผลเป็นสีเขียว และบอกสถานะเป็น UP
* เมื่อTerminate หรือservice หยุดทำงานจะแสดงผลเป็นสีแดง และบอกสถานะเป็น DOWN
