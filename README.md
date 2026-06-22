# data

Zbiór danych do warsztatów programistycznych — zestawy tabelaryczne, teksty, dokumenty PDF, prompty AI oraz obrazy.

Każda nazwa pliku poniżej jest bezpośrednim linkiem do pobrania (raw). Instrukcja tworzenia własnych linków znajduje się na [końcu](#tworzenie-linku-do-pobrania-pliku).

## Dane tabelaryczne (CSV / XLSX)

- [`movies.csv`](https://raw.githubusercontent.com/workszop/data/main/movies.csv) — 7668 filmów z lat 1986–2016, 15 kolumn: `name, rating, genre, year, released, score, votes, director, writer, star, country, budget, gross, company, runtime`. Źródło: [Kaggle — danielgrijalvas/movies](https://www.kaggle.com/datasets/danielgrijalvas/movies)
- [`sales.csv`](https://raw.githubusercontent.com/workszop/data/main/sales.csv) — 44 zamówienia sprzedaży. Kolumny: `OrderDate, Region, Manager, SalesMan, Item, Units, Unit_price, Sale_amt`
- [`sales_data.xlsx`](https://raw.githubusercontent.com/workszop/data/main/sales_data.xlsx) — przykładowe dane finansowo-sprzedażowe (Segment, Country, Product, Units Sold, Gross Sales, Discounts, COGS, Profit, Date)
- [`world_population_2021.xlsx`](https://raw.githubusercontent.com/workszop/data/main/world_population_2021.xlsx) — populacja krajów świata. Kolumny: `Population 2020, Yearly Change, Net Change, Density (P/Km²), Land Area (Km²), Migrants (net), Fert Rate, Median Age, Urban Pop %, World Share`

## Teksty

- [`jane_austen.txt`](https://raw.githubusercontent.com/workszop/data/main/jane_austen.txt) — pełny tekst powieści *Pride and Prejudice* Jane Austen (~700 KB). Do ćwiczeń z przetwarzania tekstu / NLP
- [`studenci.txt`](https://raw.githubusercontent.com/workszop/data/main/studenci.txt) — lista 10 studentów: imię, nazwisko, grupa. Nazwy zapisane **różną wielkością liter** (do ćwiczeń z czyszczenia danych)

## Dokumenty (PDF)

Do ćwiczeń z ekstrakcji danych, parsowania i RAG.

- [`google_annual_report_for_2024.pdf`](https://raw.githubusercontent.com/workszop/data/main/google_annual_report_for_2024.pdf) — raport roczny Google / Alphabet za 2024 r.
- [`logistics_contract.pdf`](https://raw.githubusercontent.com/workszop/data/main/logistics_contract.pdf) — umowa o usługi logistyczne i zaopatrzeniowe (IFRC)
- [`organization_approval_matrix.pdf`](https://raw.githubusercontent.com/workszop/data/main/organization_approval_matrix.pdf) — matryca akceptacji (fikcyjna firma „Nexus Global Solutions”)
- [`organization_procurement_policy.pdf`](https://raw.githubusercontent.com/workszop/data/main/organization_procurement_policy.pdf) — polityka zakupowa („Nexus Global Solutions”)
- [`organization_travel_and_expenses_policy.pdf`](https://raw.githubusercontent.com/workszop/data/main/organization_travel_and_expenses_policy.pdf) — polityka podróży i wydatków („Nexus Global Solutions”)
- [`umowa_o_prace_Monika_Nowak.pdf`](https://raw.githubusercontent.com/workszop/data/main/umowa_o_prace_Monika_Nowak.pdf) — przykładowa umowa o pracę (dane fikcyjne)
- [`faktura_vat_marzec_2026.pdf`](https://raw.githubusercontent.com/workszop/data/main/faktura_vat_marzec_2026.pdf) — przykładowa faktura VAT (dane fikcyjne)
- [`markdown.pdf`](https://raw.githubusercontent.com/workszop/data/main/markdown.pdf) — *The Markdown Guide* autorstwa Matta Cone'a (materiał referencyjny)

## Prompty AI

- [`prompting_levels.txt`](https://raw.githubusercontent.com/workszop/data/main/prompting_levels.txt) — trzy poziomy jakości promptu na tym samym przykładzie (PL)
- [`prompts_funny_personal_images_chatgpt.txt`](https://raw.githubusercontent.com/workszop/data/main/prompts_funny_personal_images_chatgpt.txt) — prompty do generowania zabawnych obrazów osobistych
- [`prompts_personal_photo.txt`](https://raw.githubusercontent.com/workszop/data/main/prompts_personal_photo.txt) — prompty do profesjonalnych zdjęć portretowych
- [`prompts_infographics_nano_banana.pdf`](https://raw.githubusercontent.com/workszop/data/main/prompts_infographics_nano_banana.pdf) — biblioteka promptów do infografik

## Obrazy

- [`pic.zip`](https://raw.githubusercontent.com/workszop/data/main/pic.zip) — 16 zdjęć kotów (`pic/*.jpg`)

## Tworzenie linku do pobrania pliku

Aby uzyskać bezpośredni link do pliku, zmień ręcznie URL w pasku adresu przeglądarki:

1. Zacznij od standardowego adresu pliku na GitHubie:
   `https://github.com/username/repo/blob/main/file.txt`
2. Zmień `github.com` na `raw.githubusercontent.com`.
3. Usuń fragment `/blob/`.
4. Otrzymany adres to Twój bezpośredni link:
   `https://raw.githubusercontent.com/username/repo/main/file.txt`
