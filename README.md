# ESP32
int led = 13; int relay = 2; // กำหนดขาควบคุม Relay void setup() {   pinMode(relay, OUTPUT); // กำหนดขาทำหน้าที่ให้ขา 2 เป็น OUTPUT   pinMode(led, OUTPUT); } void loop() {   digitalWrite(led, 1);   digitalWrite(relay, 1); // สั่งให้ relay ทำงาน   delay(4000); // ดีเลย์ 1000ms   digitalWrite(led, 0);   digitalWrite(relay, 0); // ปิดไฟ relay   delay(4000); }
