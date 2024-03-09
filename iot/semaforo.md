// C++ code
//

const int verdePin = 8;
const int amareloPin = 9;
const int vermelhoPin = 10;

void setup()
{
  pinMode(verdePin, OUTPUT);
  pinMode(amareloPin, OUTPUT);
  pinMode(vermelhoPin, OUTPUT);
}


void loop() {
  // Sinal verde
  digitalWrite(verdePin, HIGH);
  digitalWrite(amareloPin, LOW);
  digitalWrite(vermelhoPin, LOW);
  delay(5000); // Espera 5 segundos

  // Sinal amarelo
  digitalWrite(verdePin, LOW);
  digitalWrite(amareloPin, HIGH);
  digitalWrite(vermelhoPin, LOW);
  delay(2000); // Espera 2 segundos

  // Sinal vermelho
  digitalWrite(verdePin, LOW);
  digitalWrite(amareloPin, LOW);
  digitalWrite(vermelhoPin, HIGH);
  delay(5000); // Espera 5 segundos
}