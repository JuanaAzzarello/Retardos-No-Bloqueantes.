# Retardos-No-Bloqueantes.
Tarea Arquitectura 
Punto 1: 

int i = 0;
void setup()
{
  Serial.begin(9600);
}

void loop()
{
  Serial.println("Tiempo Activo:");
  Serial.println(i);
   Serial.println("------------");
  delay(1000);
  i=i+1;
}
