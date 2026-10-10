<p align="center"><img src="insigna.png" width="120" alt="Kuziini Photos"></p>

# Kuziini Photos

Toate pozele și clipurile de pe calculator, aranjate după **dată**, **loc** și **folder**, cu **căutare după conținut** („mare”, „zăpadă”, „tort”) și **recunoașterea persoanelor**. Le poți vedea și de pe **telefon**, prin Wi-Fi.

Pozele nu pleacă nicăieri: aplicația doar le citește de unde sunt, iar analiza se face pe calculatorul tău.

## Descărcare

**Pagina de descărcare (pentru Windows și Mac): https://tinyurl.com/kuziini-photos**

### Windows 10 / 11

**[⬇ Descarcă KuziiniPhotos_Setup.exe](https://github.com/Kuziini-product/kuziini-photos/releases/latest/download/KuziiniPhotos_Setup.exe)**

1. Deschide fișierul descărcat.
2. Dacă apare **„Windows a protejat computerul”**, apasă **Mai multe informații** → **Rulează oricum**. Mesajul apare pentru că aplicația nu e semnată de o firmă mare, nu pentru că ar fi o problemă.
3. Alege **folderul sau discul cu poze** (de exemplu `Imagini` sau `D:\`). Poți adăuga mai multe locuri.
4. Notează-ți **PIN-ul** propus. Îl ceri doar pe telefon, o singură dată.
5. Așteaptă instalarea: **5–15 minute**, într-o fereastră albastră. Se descarcă 1–3 GB (Python și componentele AI).
6. Când Windows întreabă de **firewall**, apasă **Da**. Altfel telefonul nu se poate conecta.

La final aplicația se deschide în browser. Prima dată caută și analizează pozele în fundal (de la câteva minute la o oră, după câte poze ai), dar le poți răsfoi încă din timpul indexării.

**Ai nevoie de:** Windows 10 sau 11 pe 64 de biți, internet la instalare și aproximativ 5 GB liberi. Merge mai repede cu o placă video NVIDIA, dar merge și fără.

### macOS (Mac cu procesor Apple sau Intel, macOS 11 sau mai nou)

1. Deschide aplicația **Terminal** (apasă ⌘ + Space, scrie „Terminal”, apoi Enter).
2. Copiază comanda de mai jos, lipește-o în Terminal și apasă **Enter**:

   ```
   curl -fsSL https://github.com/Kuziini-product/kuziini-photos/releases/latest/download/install-mac.sh | bash
   ```

3. În ferestrele care apar, alege **folderul cu poze** și notează-ți **PIN-ul**. Dacă ai fotografii în aplicația **Poze** (Apple Photos), te întreabă dacă le adaugi și pe ele.
4. Așteaptă instalarea: **5–15 minute**. Se descarcă aproximativ 1 GB. La final aplicația se deschide în browser.

Aplicația apare apoi în **Launchpad** și în **Spotlight** ca „Kuziini Photos”. Nu cere parola Mac-ului și nu instalează nimic în afara dosarului tău.

- Dacă macOS întreabă dacă „Kuziini Photos” poate accesa fișiere (Desktop, Documente, un disc extern) sau dacă poate primi conexiuni din rețea, apasă **Permite**. Fără a doua permisiune, telefonul nu se poate conecta.
- Dacă pozele din aplicația **Poze** sau de pe un disc extern nu apar: **Setări sistem → Confidențialitate și securitate → Acces complet la disc → +** și alege **Kuziini Photos** din folderul **Aplicații** din dosarul tău.
- Din aplicația **Poze** apar doar fotografiile aflate pe Mac. Dacă iCloud are activat „Optimizează spațiul de stocare”, originalele stau în iCloud și nu apar.
- Pe un Mac cu procesor Intel merge tot, doar că prima analiză a pozelor durează mai mult.

## Pe telefon

1. Telefonul trebuie să fie în **același Wi-Fi** cu calculatorul.
2. În aplicația de pe calculator apasă **butonul cu telefonul** (sus, în dreapta) și scanează codul QR.
3. Introdu PIN-ul.
4. Din meniul browserului alege **„Adaugă pe ecranul de pornire”**. Așa o ai ca pe o aplicație.

Calculatorul trebuie să fie pornit. Aplicația pornește singură odată cu Windows sau cu Mac-ul, dacă ai ales asta la instalare.

## Dezinstalare

Pozele tale nu sunt atinse.

- **Windows:** Setări → Aplicații → Kuziini Photos → Dezinstalează.
- **Mac:** în Terminal:

  ```
  bash ~/Library/Application\ Support/Kuziini\ Photos/mac/dezinstaleaza.sh
  ```
