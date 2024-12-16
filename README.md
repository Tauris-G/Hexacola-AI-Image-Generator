# Hexacola AI Image Generator

![Hexacola AI Image Generator](https://github.com/jusu-vardas/hexacola-ai-image-generator/blob/main/screenshot.png?raw=true)

## Aprašymas

**Hexacola AI Image Generator** yra internetinė aplikacija, leidžianti vartotojams generuoti aukštos kokybės vaizdus naudojant dirbtinį intelektą. Projekto tikslas – suteikti vartotojams paprastą ir intuityvią sąsają, kurioje jie gali detaliai aprašyti fono elementus ir personažus, pasirinkti norimą stilių bei gauti nuostabius, vienodą stilių turinčius vaizdus.

## Funkcijos

- **Atskirai aprašyti foną ir personažus**: Leidžia detaliai aprašyti tiek fono elementus, tiek personažus, siekiant tiksliau valdyti generuojamų vaizdų turinį.
- **Automatinė promptų optimizacija**: Naudojant AI, optimizuojami vartotojo įvedami aprašymai, siekiant geresnių generavimo rezultatų.
- **Pasirinkti modelį ir stilių**: Galimybė pasirinkti iš įvairių modelių ir stilių, tokių kaip Cinematic, Pixel Art, Anime, Realistic ar Mix.
- **Dark Mode**: Patogus tamsusis režimas, leidžiantis naudoti aplikaciją net ir esant mažai apšvietimo.
- **Vaizdų atsisiuntimas**: Galimybė atsisiųsti atskirus vaizdus arba visus sugeneruotus vaizdus vienu metu.
- **Pilno ekrano vaizdo peržiūra**: Spustelėjus ant vaizdo, jis atsidaro pilno ekrano režimu patogiai peržiūrai.

## Kaip naudoti

1. **Klonuoti repozitoriją**:
    ```bash
    git clone https://github.com/jusu-vardas/hexacola-ai-image-generator.git
    ```

2. **Atidaryti `index.html`**:
    Tiesiog atidarykite `index.html` failą savo naršyklėje.

3. **Įvesti aprašymus**:
    - **Background Description**: Įveskite fono aprašymą (pvz., "Saulėlydis kalnuose, ramus ežeras").
    - **Character Description**: Įveskite personažo aprašymą (pvz., "Jaunas riteris su sidabru kruopelė").
    - **Negative Prompt**: (Neprivaloma) Įveskite elementus, kurių nenorite matyti vaizde (pvz., "nenoriu logotipo, iškraipyto stiliaus").

4. **Pasirinkti nustatymus**:
    - **Modelis**: Pasirinkite norimą modelį iš išvardytų galimybių.
    - **Plotis ir aukštis**: Nustatykite norimą vaizdo dydį pikseliais.
    - **Seed**: (Neprivaloma) Nustatykite sėklą, kad generavimas būtų pakartojamas.
    - **Kiek paveikslėlių**: Nustatykite norimą generuojamų vaizdų skaičių.
    - **Stilius**: Pasirinkite norimą stilių arba "Mix", jei norite sujungti kelis stilius.

5. **Generuoti vaizdus**:
    Spustelėkite **"GENERUOTI"** mygtuką, kad pradėtumėte vaizdų generavimą.

6. **Peržiūrėti ir atsisiųsti**:
    - Generuoti vaizdai bus rodomi apačioje. Spustelėkite ant vaizdo, kad jį peržiūrėtumėte pilno ekrano režimu.
    - Jei sugeneravote kelis vaizdus, galite atsisiųsti visus juos vienu metu paspaudę **"ATSISIŲSTI VISKĄ"** mygtuką.

## Pagrindinės Technologijos

- **HTML5**: Struktūrai sukurti.
- **CSS3**: Stiliui ir dizainui.
- **JavaScript**: Funkcionalumui ir sąveikai.
- **Font Awesome**: Ikonų naudojimui.
- **Pollinations.AI API**: Teksto optimizavimui ir vaizdų generavimui.

## API Endpoints

- **Teksto optimizavimas**: `https://text.pollinations.ai/openai`
- **Vaizdų generavimas**: `https://image.pollinations.ai/prompt/`

**Pastaba**: Įsitikinkite, kad turite reikiamas prieigos teises prie Pollinations.AI API. Jei reikia, peržiūrėkite [Pollinations.AI dokumentaciją](https://github.com/pollinations/pollinations/blob/master/APIDOCS.md).

## Prisidėti prie projekto

Norėdami prisidėti prie šio projekto, sekite šiuos žingsnius:

1. **Fork** šį repozitoriją.
2. **Sukurti naują šaką** (`git checkout -b feature/puikus-pakeitimas`).
3. **Atlikti pakeitimus** ir **commit**.
4. **Paskirti šaką** (`git push origin feature/puikus-pakeitimas`).
5. **Atidaryti Pull Request**.

## Licencija

Šis projektas yra licencijuotas pagal [MIT Licenciją](LICENSE).

## Kontaktai

Jei turite klausimų ar pasiūlymų, susisiekite su manimi per [GitHub](https://github.com/Tauris-G).

---

Sukurta su ❤️ naudojant [Pollinations.AI](https://pollinations.ai/).

