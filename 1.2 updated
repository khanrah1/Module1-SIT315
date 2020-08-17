CODE:

void setup() {
  pinMode (8,OUTPUT);
  pinMode (2,INPUT);
Serial.begin(9600);

  attachInterrupt (0,SensorToOnLed,RISING);
 
}

void loop() {


}

void SensorToOnLed()
{
  digitalWrite(8,HIGH);
Serial.println("object Detected!");
  delay(10000);
  digitalWrite(8,LOW);
  
}
