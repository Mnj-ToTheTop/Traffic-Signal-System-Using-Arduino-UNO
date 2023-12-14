//Assigning different Pins to our LEDs.
int Rled = 7;
int Gled = 2;
int Yled = 4;

//Assigning the output mode to the pins and assigning them in the OFF state for the beggining.
void setup() 
{
  pinMode(Rled,OUTPUT);
  pinMode(Gled,OUTPUT);
  pinMode(Yled,OUTPUT);
  Serial.begin(9600);
  digitalWrite(Rled,LOW);
  digitalWrite(Gled,LOW);
  digitalWrite(Yled,LOW);
}

void loop() 
{
  //Red light will be on for 3sec.
  digitalWrite(Rled,HIGH);
  digitalWrite(Gled,LOW);
  digitalWrite(Yled,LOW);
  delay(3000);

  //Green Light will be on for 3sec
  digitalWrite(Rled,LOW);
  digitalWrite(Gled,LOW);
  digitalWrite(Yled,HIGH);
  delay(3000);

  //Yellow Light will be on for 3sec
  digitalWrite(Rled,LOW);
  digitalWrite(Gled,HIGH);
  digitalWrite(Yled,LOW);
  delay(3000);
}
