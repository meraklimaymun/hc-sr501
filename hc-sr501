int hareket;

void setup() {
  // put your setup code here, to run once:
pinMode(2, INPUT);
pinMode(3, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
hareket=digitalRead(2);
if (hareket == HIGH){
  analogWrite(3, 1);
}
else{
  analogWrite(3, 0);
}
}
