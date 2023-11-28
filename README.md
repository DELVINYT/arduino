# arduino
const int pinBuzzer = 9;

void setup (){
  pinMode(pinBuzzer, OUTPUT);
}

void loop(){
  digitalWrite(pinBuzzer, HIGH);
  delay(1000);

  digitalWrite(pinBuzzer,LOW);
  delay(3000);
}
