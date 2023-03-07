##Dokumentasjon:
-Prosjektrapport: [Overleaf](https://l.messenger.com/l.php?u=https%3A%2F%2Fwww.overleaf.com%2F8278797437vqsrgxgyvmnr&h=AT2yZSTJXKBVAB0i-o-Xrmv5aRXD2AApPnXD_CqH0uDPE-M9pc31HANUVfKONtGPmJuuE3ul9wE4Jbmv1_MuJFYK5xSBJsZxK8dEmsytti-fySrvxSrjIvj_RC3wifGX4TsSRLtdaSzQMg6K-nu9uw)
-Arbeidsavtale: ?????

##Vekeplan:
-Les dokumentasjon og prosjektkrav

##Midertidig inndeling:
- PWM/ADC Michal
- USART/Hardware Eryk
- I2C/Tempmåler Johnsen

##Prosjektkrav:
• MÅ: Lage en I2C slave, enten egenkodet eller via rammeverk.
• MÅ: Noden skal overvåke både egen og ekstern spenning
• MÅ: Noden skal overvåke temperatur via en termistor.
• MÅ: Noden skal bed hjelp av lys- og fotodiode bestemme hastigheten til ekstern vifte.
• MÅ: Via feilutganger vil noden varsle både høy temperatur, og gi feil dersom begge viftene
står stille i for lang tid, eller temperaturen er for høy.
• MÅ: Endringer i innstillinger må kunne gjøres over I2C og lagres på kontrolleren.
• BØR: Viften skal overvåkes over tid, slik at avvik i viftehastighet og evt varsler kan leses av
via I2C.
• Tilleggskretser kan brukes etter behov. EEPROM / ADC / OPAMP osv.
