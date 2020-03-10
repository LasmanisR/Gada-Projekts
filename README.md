# Weather Station
* [Projekta apraksts](#Projekta-apraksts)
* [Shēmas](#Shēmas)
* [Kods](#Kods)
* [Komponentes](#Komponentes)

# Projekta apraksts
Laika apstākļu stacija mājai ar displeju un sensoriem BME280(Temperatūra, mitrums, spiediens), MH-Z19(CO2).
* LCD Displejs uz kura tiks attēloti šādi dati:
  * Pulkstenis/Laiks
  * Datums
  * Gaisa temperatūra
  * Gaisa mitrums
  * Spiediens
  * CO2
* Diode kas attēlos CO2 līmeni.
  * Zaļš - Viss labi
  * Dzeltens - Uzmanību
  * Sarkans - Viss slikti
* Sensora poga kas ļaus pārslēgt režīmus.
* Grafiki, kuros tiks attēloti sensoru mērijumi gan 1h, gan 24h laikā.

# Shēmas
<img src="https://github.com/LasmanisR/Weather-Station/blob/master/Sh%C4%93mas/Sh%C4%93ma1.PNG">

# Kods
# Komponentes
* Feather Huzzah
* TTP223(sensora poga)
* BME280(5V)
* MH-Z19
* LCD i2c - Displejs
* RGB Diode
* 
