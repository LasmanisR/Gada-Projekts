# Weather Station
* [Projekta apraksts](#Projekta-apraksts)
* [Shēmas](#Shēmas)
* [Kods](#Kods)
* [Komponentes](#Komponentes)

# Projekta apraksts/ideja
Projekta ideja ir izveidot laika apstākļu staciju mājai ar displeju un sensoriem BME280(Temperatūra, mitrums, spiediens), MH-Z19(CO2), ar iespēju vērot šos datus gan uz displeja, gan arī izmantojot cloud. Būs iespēja arī noteikt aptuvenos laikapstākļus pateicoties spiedienam.
* LCD Displejs uz kura tiks attēloti šādi dati:
  * Pulkstenis/Laiks
  * Datums
  * Gaisa temperatūra
  * Gaisa mitrums
  * Spiediens
  * CO2
* Diode kas attēlos CO2 līmeni.
  * Zaļš - Viss labi(400-800ppm)
  * Dzeltens - Uzmanību(800-1200ppm)
  * Sarkans - Viss slikti(1200 - ∞ppm)
* Sensora poga kas ļaus pārslēgt režīmus.
* Grafiki, kuros tiks attēloti sensoru mērijumi gan 1h, gan 24h laikā.

# Shēmas
<img src="https://github.com/LasmanisR/Weather-Station/blob/master/Sh%C4%93mas/Sh%C4%93ma1.PNG">

# Kods
-Šobrīd Nav

# Komponentes(ar linkiem kur tās var pasūtīt)
* Feather Huzzah:http://eby.onl/DQ
* TTP223(sensora poga):http://ali.onl/1yP0
* BME280(5V):http://ali.onl/1yP2
* MH-Z19:http://ali.onl/1yP1
* LCD i2c - Displejs:http://ali.onl/1yP3
* RGB Diode:http://ali.onl/1yOY
