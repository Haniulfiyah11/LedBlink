# LedBlink
int led = 12;//Output pada Digital Pin adalah sebuah LED yang terkoneksi/terhubug dengan digital pin 11. 
void setup()
{
 pinMode(led, OUTPUT);//Mengatur Digital Pin sebagai Output
}
void loop()
{
 digitalWrite(led, HIGH);   //Mengatur led agar menyala.
 delay(2500);               //Tunggu sampai 4 detik.
 digitalWrite(led, LOW);   //Mengatur led agar mati.
 delay(2500);               //Tunggu sampai 4 detik.
 }
