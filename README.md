dla długiego życia tantali: soft start/ wolno narastające napięcie by krystalizacja popychana napięciem nie przebijała dielektryka


http://www.ee.co.za/article/thermal-stress-capacitors-failure-prevention.html

https://archiwum.uke.gov.pl/pozwolenia-amatorskie-4266
https://archiwum.uke.gov.pl/swiadectwa-amatorskie-4390

https://github.com/espressif/arduino-esp32/pull/678
https://www.esp32.com/viewtopic.php?f=2&t=1386
https://github.com/espressif/esp-idf/issues/1064

>Zyper
Dużo fajniejsze się wydaje to ESP-IDF niż natywne na ESP8266, bo podłączasz, kompilujesz i działa

można zawsze zapisywać, a potem odczytywać na komputerze (albo przez WiFi bezpośrednio z urządzenia)
no ale takie ublox na ali to 30 zł
tak patrzę po allegro to trackery GPS są od 100 do 300zł
możnaby wszystko zrobić, ale czy jest sens?

soft mógłby być jeden i wykrywałby które czujniki są dostępne i się konfigurował w zależności od tego co będzie w środku

chyba lepiej by było zrobić kilka wersji do wyboru niż upakować wszystko w jedno

Co do wznawiania połączenia to można nawet co kilka sekund (łączy się, wysyła, i usypia)
wtedy możnaby zrobić na baterii

możnaby dołożyć jeszcze sensor cząsteczek PM2,5 i PM10 zeby pokazywać zanieczyszczenie powietrza

czyli chcesz gotowe urządzenia bez możliwości modyfikacji?
>>gotowe, ale konfigurowalne. Tak samo, jak kupujesz samochód z klimą, albo bez czujników parkowania



@purk
baloniarze, entuzjaści pogody, droniarze i rakietowcy. mamy jeszcze jakieś potencjalne grupy docelowe?

kogoś mógłby interesować poziom hałasu otoczenia

nawet nie trzeba programować tego UARTem, bo działają apdejty OTA

ESP32 ma kilka kanałów ADC i mozemy je też wyprowadzić do generalnego użytku - odczyt i interwały  pomiaru byłyby do ustawienia z poziomy programu

kolejna rzecz, która mnie kiedyś jarała - detektor burz, który składał się ze zwoju kabla podłączonego do karty dźwiękowej xD

kolejna rzecz, która mnie kiedyś jarała - detektor burz, który składał się ze zwoju kabla podłączonego do karty dźwiękowej xD
i takie coś też nadawałoby się do podpięcia do sieci np. blitzortung

Oprócz tego jest fajny w miarę tani odbiornik GPS - ublox NEO-7, ja mam w szufladzie NEO-6, ale jeszcze nie testowany - dałem 26z








