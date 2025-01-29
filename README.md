# GeneralTasks
General Tasks for Project 2025
## Versioiden tarkistus 29.01 2025

Python
python --version
Toni Python 3.12.6

Django:
python -m django --version
Toni 5.1

Django REST Framework (DRF)
python -c "import rest_framework; print(rest_framework.__version__)"
Toni 3.15.2

Node.js
node -v
Toni v20.17.0

Vite (Projektikohtainen Tonilla. Asennettu 30.9 2024. Ei asennettuna globaalisti)
npm list -g vite

Toni
nwreactvite@0.0.0 C:\React\nwReactVite
├─┬ @vitejs/plugin-react@4.3.2
│ └── vite@5.4.8 deduped
├── vite@5.4.8
└─┬ vitest@2.1.8
  ├─┬ @vitest/mocker@2.1.8
  │ └── vite@5.4.8 deduped
  ├─┬ vite-node@2.1.8
  │ └── vite@5.4.8 deduped
  └── vite@5.4.8 deduped

## Kloonausohjeet Back-end
git clone https://github.com/Jaspak1778/DevPal_RFM(tms).git 
cd DevPal  # SIIRRYTÄÄN PROJEKTIKANSIOON, JONKA GIT LUO
python -m venv venv 
.\venv\Scripts\activate  # AKTIVOI VIRTUAALIYMPÄRISTÖN WINDOWSISSA
pip install -r requirements.txt

## Kloonausohjeet Front-end
git clone https://github.com/Jaspak1778/DevPal_React(tms).git 
cd DevPal  # SIIRRYTÄÄN PROJEKTIKANSIOON, JONKA GIT LUO
npm install # Asennetaan riippuvuudet package.json-tiedoston mukaisesti.
npm run dev # Kehitysympäristön käynnistys
avaa:  Local: http://localhost:5173/





  


