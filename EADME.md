 Arduino LED Blink – Tinkercad Simulation

# Description
This is a basic Arduino simulation using [Tinkercad](https://www.tinkercad.com/).  
The LED turns ON for 2 seconds, then OFF for 2 seconds continuously.  
The project demonstrates the use of digital output and delay functions in Arduino.

# Components Used
- Arduino UNO R3  
- LED  
- 220 Ohm Resistor  
- Breadboard  
- Jumper wires  

 Arduino Code

#define led  7

void setup()
{
  pinMode(led, OUTPUT);
  digitalWrite(led, HIGH);
  delay(10000); 
}

void loop()
{
  digitalWrite(led, HIGH);
  delay(2000);
  digitalWrite(led, LOW);
  delay(2000); 
}
