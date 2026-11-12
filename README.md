# 🌿 PCMAT — La Sèrie de Fibonacci

![Estat](https://img.shields.io/badge/Estat-Actiu-2E6E36?style=flat-square)
![Tecnologia](https://img.shields.io/badge/HTML5%20%7C%20CSS3%20%7C%20JS-Vanilla-F59E0B?style=flat-square)
![Àmbit](https://img.shields.io/badge/Educació-Matemàtiques%20i%20PC-3B82F6?style=flat-square)
![Llicència](https://img.shields.io/badge/Llicència-MIT-lightgrey?style=flat-square)

Aplicació web educativa, interactiva i gamificada per treballar la **Sèrie de Fibonacci** i les seqüències numèriques additives a l'aula. El disseny visual i la progressió didàctica s'inspiren en el model manipulatiu **PCMAT** (Pensament Computacional i Matemàtiques).

---

## ✨ Característiques principals

* **🎨 Estètica i didàctica PCMAT:** Interfície clara i accessible amb capçalera verda institucional, icones de flor de 6 pètals i la dinàmica d'aprenentatge en dos passos:
  * **Observa:** Exemple resolt pas a pas (`1, 3, 4, 7, 11, 18`) per deduir la regla de formació.
  * **Completa:** Caselles interactives amb validació immediata i retroacció visual.
* **🎮 Sistema de Gamificació i Perfil d'Alumne:**
  * Registre ràpid de l'alumne/a (**nom, cognoms, curs/grup i avatar matemàtic**) amb desament automàtic al navegador (`localStorage`).
  * Barra d'experiència (**XP**) amb **5 rangs evolutius** (des d'*Aprenent de Patrons* fins a *Gran Mestre/a de Fibonacci*).
  * Comptador de **ratxes d'encerts**, botó de **pistes visuals** (ressalta els dos termes previs que se sumen) i **6 medalles desbloquejables**.
* **📈 5 Nivells amb Dificultat Creixent:**
  1. **El Model PCMAT:** Introducció a la sèrie clàssica (`1, 1, 2, 3...`) i seqüències base (`2, 5, 7, 12...`).
  2. **Seqüències Germanes:** Exploració dels nombres de Lucas i noves parelles inicials.
  3. **Caselles Ocultes:** Pensament invers i càlcul mental mitjançant restes per trobar termes inicials o intermedis.
  4. **L'Espiral Daurada i l'Intrús:** Detecció i correcció d'errors en seqüències donades, acompanyat de la construcció SVG animada de l'**Espiral de Fibonacci**.
  5. **Mestre/a de Patrons:** Reptes avançats amb nombres enters negatius, decimals i l'aproximació al **Nombre d'Or ($\phi \approx 1,618$)**.
* **📄 Informe de Seguiment en PDF per al Docent:** Generació instantània d'un informe descarregable amb les dades de l'alumne/a, nivell assolit, punts XP, medalles obtingudes, detall d'encerts per exercici i espai per a observacions i signatures.

---

## 🗂️ Estructura del repositori

El projecte està desenvolupat com una **Single-Page Application (SPA) autònoma** en un únic fitxer per facilitar-ne l'ús a qualsevol aula sense dependències ni configuracions complexes:

```text
pcmat-fibonacci/
├── index.html      # Aplicació completa (HTML5, CSS3, lògica JS, SVG i generador PDF)
└── README.md       # Documentació del projecte
```

---

## 🚀 Instal·lació i ús

### Opció 1: Execució en local
1. Clona aquest repositori o descarrega el fitxer `index.html`:
   ```bash
   git clone [https://github.com/el-teu-usuari/pcmat-fibonacci.git](https://github.com/el-teu-usuari/pcmat-fibonacci.git)
   ```
2. Obre el fitxer `index.html` fent doble clic amb qualsevol navegador web modern (Chrome, Firefox, Edge, Safari). No requereix connexió a internet ni servidor local.

### Opció 2: Publicació gratuïta amb GitHub Pages (recomanat per a l'aula)
1. Puja el fitxer `index.html` a un repositori públic de GitHub.
2. Ves a **Settings** (Configuració) > **Pages**.
3. A l'apartat *Build and deployment*, selecciona la branca `main` i la carpeta `/ (root)`, i fes clic a **Save**.
4. En menys d'un minut tindràs un enllaç web (`https://el-teu-usuari.github.io/pcmat-fibonacci/`) llest per compartir amb l'alumnat des d'ordinadors, Chromebook o tauletes.

---

## 🛠️ Tecnologies utilitzades

* **HTML5 & CSS3:** Disseny responsiu adaptat a pantalles d'ordinador, tauletes i pissarres digitals interactives (PDI).
* **JavaScript (ES6+):** Motor d'exercicis, validació dinàmica, persistència de progrés amb `localStorage` i gestió de nivells.
* **SVG dinàmic:** Representació geomètrica interactiva dels quadrats i l'espiral de Fibonacci.
* **Exportació PDF integrada:** Generació d'informes d'avaluació directament des del navegador.

---

## 📄 Llicència

Aquest projecte es distribueix sota la llicència **MIT**. Pots utilitzar-lo, modificar-lo i adaptar-lo lliurement per a fins educatius i docents.