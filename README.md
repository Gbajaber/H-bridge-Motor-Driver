# H-bridge-Motor-Driver
electronics section - second task

This project is considered as required by smart methods company in cooperative training for the year 2021 
Tinkercad is the website that used to create this circuit
The objective to move the motors at clockwise
componets Arduino Uno R3 = 1 / DC Motor = 2 / 9V Battery = 1 / H bridge L293D

the code

#define m1 2 
#define m2 3 
#define m3 4 
#define m4 5 
void setup()
{
   pinMode(m1,OUTPUT);
   pinMode(m2,OUTPUT);
   pinMode(m3,OUTPUT);
   pinMode(m4,OUTPUT);
}

void loop()
{
  digitalWrite(m1, HIGH);
  digitalWrite(m2, LOW);
  digitalWrite(m3, HIGH);
  digitalWrite(m4, LOW);
  delay (10000);
}

tinkercad link
https://www.tinkercad.com/things/hfdPIIKpVxz-h-bridge-motor-driver/editel
