# My Gaming Backlog

Klientská webová aplikace pro evidenci a správu osobní sbírky videoher. Využívá RAWG API a localStorage. Vytvořeno jako semestrální práce v rámci studia aplikované informatiky na VŠE FIS.

## Funkce

* **Vyhledávání a objevování:** Procházení rozsáhlé databáze her s využitím RAWG Video Games Database API.
* **Pokročilé filtrování a řazení:** Možnost filtrovat výsledky podle platforem (PC, konzole apod.) a žánrů. Výsledky lze řadit podle relevance, popularity, data vydání nebo hodnocení.
* **Správa osobní knihovny:** Přidávání her do vlastního seznamu, který je trvale uložen v prohlížeči pomocí `localStorage`.
* **Sledování progrese:** Přiřazení vlastních stavů k jednotlivým hrám (Chci hrát, Právě hraji, Dohráno, Odloženo).
* **Hodnocení a poznámky:** Možnost přidat vlastní číselné hodnocení (0–100), zaznamenat datum dohrání a psát si k hrám vlastní poznámky.
* **Detaily hry a galerie:** Zobrazení podrobného popisu hry, skóre z Metacritic, dostupných platforem, žánrů a prohlížení galerie obrázků v modálním okně.
* **Responzivní UI:** Plně responzivní design, který se dynamicky přizpůsobuje a funguje bez problémů na desktopu i mobilních zařízeních.

## Použité technologie

* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Knihovny:** jQuery, SweetAlert2
* **API:** [RAWG API](https://rawg.io/apidocs) pro získávání herních dat

## Security Note (API Key)

V repozitáři je záměrně ponechán bezplatný (free-tier) API klíč pro službu RAWG, aby byla aplikace po stažení (či na živé ukázce) okamžitě plně funkční pro účely ukázky. V případě jeho propadnutí je nutné klíč změnit ve skriptu `assets/js/app.js`, konkrétně u proměnné `App.API_KEY`.
