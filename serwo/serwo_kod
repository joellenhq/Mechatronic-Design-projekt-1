#include <Servo.h> //dołączenie biblioteki
Servo serwo;          //utworzenie obiektu serwo
void setup() {
serwo.attach(5);    //dołączenie obiektu do pinu 5
}

void loop() {
int pot=analogRead(A0);              //odczyt z wejścia analogowego
int kat=map(pot,0,1024,0,180);  //przeskalowanie wartosci
serwo.write(kat);                        //przesłanie polecenia o ruchu
delay(50);                                   //opóźnienie ;)
}
