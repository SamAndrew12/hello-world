# hello-world
My first repo!

#include <arduino.h>
#include <wire.h>

void setup()
{
  Serial.begin(9600);
}

void loop()
{
  Serial.println("Hello World!");
}
