# Amplificator de Tensiune cu Reacție Negativă

Acest repository conține proiectarea unui **amplificator de tensiune cu reacție negativă**, realizat în cadrul materiei "Circuite electronice fundamentale 2 - Proiect". 

Proiectul a avansat din faza de concept, incluzând acum atât **Partea 1** (proiectarea schemei și simulările circuitului), cât și elemente din **Partea 2** (layout-ul PCB și fișierele de fabricație).

## 📂 Structura Repository-ului

Fișierele sunt organizate după cum urmează:
* **`Fisiere Gerber si DRILL/`**: Conține fișierele necesare pentru trimiterea în producție a plăcii (Gerber și Excellon).
* **`Fisiere PCB/`** & **`allegro/`**: Conțin proiectul fizic al cablajului imprimat.
* **`proiect1_test3-PSpiceFiles/SCHEMATIC1/`**: Conține schema electrică și fișierele aferente simulărilor.
* **`signoise.run/`**: Fișiere de analiză și rulare generate de mediul OrCAD.

## 💡 Cum se deschid fișierele

* **Cablajul Imprimat (PCB):** Fișierele din folderele `Fisiere PCB` și `allegro` pot fi deschise și vizualizate folosind **OrCAD PCB Editor**.
* **Simulările:** Fișierele din `proiect1_test3-PSpiceFiles` pot fi deschise cu **OrCAD Capture / PSpice**.
* **Fișierele de fabricație:** Conținutul din `Fisiere Gerber si DRILL` poate fi deschis cu orice vizualizator Gerber standard (ex. GerbV, ViewMate sau vizualizatoare online).

## 🎯 Specificațiile Proiectului (conform temei)

Amplificatorul îndeplinește următoarele caracteristici:
* **Amplificarea de tensiune:** Av = 3 + N/2 (în acest caz, **Av = 4**)
* **Tensiune de intrare sinusoidală:** 100 mV V-V, f = 1 kHz
* **Impedanță minimă de intrare:** 100 kΩ
* **Rezistență de sarcină:** 10 Ω
* **Domeniul de temperatură:** 0–70°C
* **Amplificare în buclă deschisă:** > 200
* **Alimentare:** De la o singură sursă de tensiune
* **Componente:** Utilizarea exclusivă a componentelor discrete (fără circuite integrate)
* **Implementare:** Tehnologie SMT & PCB

## 🧩 Stadiul Proiectului

### ✔️ Etape Finalizate
* **Concept și schemă electrică:** Dimensionarea componentelor în funcție de cerințe (amplificare, impedanțe, sarcină).
* **Simulări:** Analiza răspunsului în frecvență, stabilirea punctelor de funcționare, verificarea amplificării și a stabilității (PSpice).
* **Proiectare PCB:** Realizarea layout-ului plăcii.
* **Export pentru fabricație:** Generarea fișierelor Gerber și Drill.
* Asamblarea componentelor și testarea practică în laborator
* <img width="3840" height="2160" alt="WhatsApp Image 2026-05-23 at 22 17 51" src="https://github.com/user-attachments/assets/ec54ec46-b7d4-42e2-96a8-8aa8a250a500" />
* Măsurători și comparații între rezultatele teoretice / simulare / practică
* <img width="1000" height="770" alt="image" src="https://github.com/user-attachments/assets/df7d536c-94d5-4905-ba22-a6ad652e22c4" />


## 🛠 Tehnologii și instrumente folosite

* **OrCAD Capture & PSpice:** Pentru desenarea schemei și simulări.
* **OrCAD PCB Editor:** Pentru realizarea layout-ului și generarea fișierelor de fabricație.
* <img width="749" height="717" alt="image" src="https://github.com/user-attachments/assets/6db56002-5c1e-428d-a982-b10f83bbfffe" />
* **Echipamente de laborator:** Osciloscop, generator de funcții, sursă de alimentare (urmează pentru etapa de testare).

## ✍️ Autor

Proiect realizat de **Dragotoniu Ionuț-Constantin** Facultatea de Electronică, Telecomunicații și Tehnologia Informației – UPB  
Grupa 431C • An universitar 2025–2026
