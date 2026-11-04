<div align="center">

# Cześć, jestem Adam 👋
### Informatyka Stosowana @ Politechnika Krakowska 🎓
### Embedded Systems & Python Developer | Cyberpunk & Tech Maker 🤖

[![Politechnika Krakowska](https://img.shields.io/badge/Politechnika%20Krakowska-Informatyka%20Stosowana-002D62?style=for-the-badge&logo=academic-tree&logoColor=white)](https://pk.edu.pl)
[![Cyberpunk Enthusiast](https://img.shields.io/badge/Vibe-Cyberpunk%20%2F%20High%20Tech%20Low%20Level-FCEE09?style=for-the-badge&logoColor=black&labelColor=000000)](https://github.com/AdamAdamnomnom)
[![Status](https://img.shields.io/badge/Status-Open%20to%20Opportunities-00F0FF?style=for-the-badge&labelColor=000000)]()

<br/>

> *„High tech, low level. Fascynuje mnie połączenie surowej elektroniki, mikrokontrolerów i Linuksa z klimatem tech-noir — tworzę urządzenia i oprogramowanie, które żyją poza monitorem.”*

</div>

---

### 🚀 O mnie (Story & Bio)

Studiuję **Informatykę Stosowaną na Politechnice Krakowskiej** i na co dzień balansuję między światem software'u a sprzętu. Nie znoszę nudnego kodu i „programowania do szuflady” — najbardziej jara mnie budowanie namacalnych projektów, gdzie kod bezpośrednio kontroluje napięcia, przekaźniki, silniki, dźwięk i ekrany dotykowe.

* 🎓 **Informatyka Stosowana (Politechnika Krakowska):** Solidne zaplecze algorytmiczne, inżynieria systemowa, sieci komputerowe i architektura komputerów przeniesione w praktykę.
* 🤖 **Cyberpunk & Tech-Noir Geek:** Wielki fan uniwersum Cyberpunka (gry, książki, anime, stylistyka). Fascynują mnie interfejsy człowiek-maszyna, wbudowane terminale, sensoryka, neony i klimat urządzeń działających niezawodnie w trybie 24/7.
* ⚡ **Hardware & Mikrokontrolery:** Gdy nie siedzę w kodzie, trzymam w ręku lutownicę lub oscyloskop. Projektuję sterowniki przemysłowe na mikrokontrolerach **AVR (ATmega328P)** oraz układach **ESP8266**, tworząc autorskie biblioteki C++ odwzorowujące logikę PLC (nieblokujące timery, pamięć EEPROM, obsługa przerwań E-STOP).
* 🐧 **Hacking Linuksa & Dedykowane Urządzenia (Appliances):** Przerabiam terminale cienkie (**Thin Clients**) na autonomiczne urządzenia kioskowe oparte o minimalistycznego Debiana, sesję X11, okna PyQt6, manipulację oknami w `python-xlib`, protokół CDP (Chrome DevTools Protocol) oraz cyfrową obróbkę dźwięku (ALSA/LADSPA DSP).
* 💡 **Eksperymenty i nowe projekty:** Ciągle coś dłubię — od prototypów automatyki domowej i warsztatowej, przez customowe peryferia, po optymalizację środowisk linuksowych pod specyficzny sprzęt.

---

### 🛠️ Technologie i Skrzynka z Narzędziami

<div align="center">

| Kategoria | Technologie & Narzędzia |
|---|---|
| **Języki** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) |
| **Embedded & Sprzęt** | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white) ![ATmega328P](https://img.shields.io/badge/ATmega328P-Microchip-blue?style=flat-square) ![PLC](https://img.shields.io/badge/PLC-Ladder%20Logic-darkgreen?style=flat-square) ![UART/EEPROM](https://img.shields.io/badge/Hardware-UART%20%7C%20EEPROM%20%7C%20GPIO-grey?style=flat-square) |
| **Systemy & Linux** | ![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![X11 / Openbox](https://img.shields.io/badge/X11%20%2F%20Openbox-555555?style=flat-square) ![PulseAudio / ALSA](https://img.shields.io/badge/Audio-PulseAudio%20%2B%20ALSA%20%2B%20LADSPA-orange?style=flat-square) |
| **Frameworki & Narzędzia** | ![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white) ![CDP](https://img.shields.io/badge/CDP-Chrome%20DevTools%20Protocol-4285F4?style=flat-square&logo=google-chrome&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

</div>

---

### 🌟 Wyróżnione Projekty (Featured Projects)

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">⚡ <a href="https://github.com/AdamAdamnomnom/vena3-plc">vena3-plc</a></h3>
      <p align="center"><b>Przemysłowy Sterownik PLC (C++ / ATmega328 + ESP8266)</b></p>
      <ul>
        <li>Zbudowany od zera fizyczny sterownik PLC do automatyzacji procesów przemysłowych i maszyn.</li>
        <li>Własna biblioteka obiektowa w C++ odwzorowująca przemysłową logikę sterowników PLC (markery pamięci, liczniki cykli, timery oparte o <code>millis()</code>).</li>
        <li>Sprzętowy przycisk zatrzymania awaryjnego (E-STOP) na dedykowanych przerwaniach mikroprocesora.</li>
        <li>Dwukierunkowa komunikacja szeregowa UART oraz pamięć nieulotna EEPROM.</li>
      </ul>
      <p align="center">
        <code>C++</code> • <code>Arduino</code> • <code>ESP8266</code> • <code>ATmega328P</code> • <code>Industrial Automation</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎵 <a href="https://github.com/AdamAdamnomnom/VenaV-speaker">VenaV-speaker</a></h3>
      <p align="center"><b>Embedded Audio/Video Kiosk System (Python / PyQt6 / Linux)</b></p>
      <ul>
        <li>Autonomiczny system kioskowy na dotykowy terminal cienki Fujitsu Futro S930 (Debian, sesja X11, Openbox bez środowiska desktopowego).</li>
        <li>Interfejs AlwaysOnTop w PyQt6 integrujący odtwarzacze w dedykowanych procesach Chromium.</li>
        <li>Sterowanie przez protokół CDP (Chrome DevTools Protocol) oraz bezkolizyjne przesuwanie okien poza ekran (<code>stow</code>) w <code>python-xlib</code>.</li>
        <li>Wirtualna klawiatura wstrzykująca kody klawiszy przez X11 XTest, mikser ALSA i cyfrowy procesor efektów LADSPA (PulseAudio).</li>
      </ul>
      <p align="center">
        <code>Python 3</code> • <code>PyQt6</code> • <code>Linux Appliance</code> • <code>X11</code> • <code>Audio DSP</code>
      </p>
    </td>
  </tr>
</table>

---

### 📊 Statystyki GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AdamAdamnomnom&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Statystyki GitHub Adama" height="175" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdamAdamnomnom&layout=compact&theme=tokyonight&hide_border=true" alt="Najczęściej używane języki" height="175" />
</div>

---

### 📬 Kontakt

Jestem otwarty na ciekawe wyzwania inżynieryjne, praktyki, staże oraz propozycje współpracy przy projektach **Embedded / IoT**, **aplikacjach w Pythonie/C++** i **automatyce przemysłowej**.

* 🎓 **Uczelnia:** Politechnika Krakowska (Wydział Informatyki i Telekomunikacji)
* 💻 **GitHub:** [@AdamAdamnomnom](https://github.com/AdamAdamnomnom)
* 💼 **LinkedIn:** *(dostępny na życzenie / w CV)*
* ✉️ **E-mail:** *(dostępny w CV)*

<div align="center">
  <sub>⚡ <i>"Wake up, Samurai. We have code to write."</i> ⚡</sub>
</div>
