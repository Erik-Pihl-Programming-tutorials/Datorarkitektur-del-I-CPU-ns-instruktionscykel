# Datorarkitektur (del I) - CPU:ns instruktionscykel
Första delen i en serie som behandlar CPU-konstruktion i mjukvara. 
En simulerad processor som baseras på mikrodator ATmega328P implementeras i terminalmiljö,
där klockpulser, in- och utdata implementeras via inmatning samt utskrift från terminalen.

Denna del behandlar OP-koder, olika minnen, programräknare, instruktionsregister, CPU-register med mera. Framförallt implementeras CPU:ns instruktionscykel via en enkel tillståndsmaskin.

Filen "embedded_computer_system1_start_code.zip" innehåller diverse makron för OP-koder, I/O-adresser, utskriftsfunktioner med mera som används i programmet.

Resterande filer utgörs av den färdiga implementeringen av CPU:ns instruktionscykel.

I efterföljande delar ska ytterligare OP-koder läggas till, programminnet och dataminnet ska utvecklas, samtidigt som stacken, ALU:n samt interrupt-implementering ska läggas till.

Se video tutorial här:
https://youtu.be/gVzuMkYP_LY