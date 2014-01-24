PhysicalComputing
=================

Code for my Physical Computing class

int button = 3; // DIY SWITCH
int ledpin = 2;

void setup() {
  pinMode(button, INPUT);
  pinMode(ledpin, OUTPUT);
}

void loop() {
  int value = digitalRead(button);
  if (value == HIGH) {
    digitalWrite(ledpin, HIGH);
  } else{
    digitalWrite(ledpin, LOW);
  }
}
