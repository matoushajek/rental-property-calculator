# Investiční byt – interaktivní kalkulačka proveditelnosti (SQL + Power BI)

Tento projekt představuje interaktivní finanční kalkulačku simulující ekonomickou proveditelnost nákupu investičního bytu financovaného hypotékou. Cílem je převést komplexní finanční rozhodnutí domácnosti do srozumitelných metrik a umožnit uživateli vyhodnotit, zda je investice dlouhodobě udržitelná.

Dashboard umožňuje měnit klíčové vstupní parametry, například:

* vlastní kapitál domácnosti,
* cenu nemovitosti,
* délku hypotéky,
* úrokovou sazbu,
* očekávaný výnos z nájmu,
* míru neobsazenosti bytu,
* čistý příjem domácnosti,
* maximální podíl splátky na příjmu.

Na základě těchto vstupů model počítá:

* výši úvěru a měsíční splátku hypotéky,
* očekávaný čistý nájem a měsíční cashflow,
* nutný měsíční doplatek domácnosti,
* minimální požadovaný příjem dle bankovních limitů,
* proveditelnost investice z hlediska rozpočtu,
* potřebnou likvidní rezervu,
* celkové přeplacení hypotéky,
* podíl hypotéky, který v průběhu času splatí nájemník.

Projekt kombinuje SQL pro datový model a Power BI pro interaktivní simulaci a interpretaci výsledků. Výsledkem je praktický nástroj podporující finanční rozhodování, který propojuje hypotéční financování, nájemní výnos a rizikové faktory do jednoho přehledného modelu.

---

## Jak dashboard používat

1. Nastav vstupní parametry pomocí sliderů.
2. Sleduj změny ve splátce, nájmu a cashflow.
3. Vyhodnoť proveditelnost investice a její dopad na rozpočet domácnosti.

Dashboard slouží jako realistická simulace, nikoliv jako finanční doporučení. Nezohledňuje individuální scoring bank, další závazky domácnosti ani daňové aspekty investice.

---

## Technologie

* SQL – datový model a výpočty
* Power BI – vizualizace a interaktivní simulace


# Rental Property Feasibility Calculator (SQL + Power BI)

This project presents an interactive financial calculator that simulates the feasibility of purchasing a rental property financed by a mortgage. Its goal is to translate a complex household investment decision into clear, understandable metrics that help users evaluate whether the investment is sustainable in the long term.

The dashboard allows users to adjust key input parameters, including:

* available household capital,
* property price,
* mortgage term length,
* interest rate,
* expected rental yield,
* vacancy rate,
* household net income,
* maximum payment-to-income ratio.

Based on these inputs, the model calculates:

* loan amount and monthly mortgage payment,
* effective rental income and monthly cashflow,
* required monthly subsidy,
* minimum income needed under lending constraints,
* investment feasibility within the household budget,
* required liquidity buffer,
* total mortgage interest paid,
* share of the mortgage effectively covered by the tenant over time.

The project combines SQL for the data model and Power BI for interactive simulation and business interpretation. The result is a practical decision-support tool that integrates mortgage financing, rental income, and risk factors into a single transparent model.

---

## How to use the dashboard

1. Adjust the input sliders to reflect your scenario.
2. Observe how payments, rent, and cashflow change.
3. Evaluate affordability and financial impact on the household.

The dashboard is intended as a realistic simulation rather than financial advice. It does not account for individual bank scoring models, additional liabilities, or taxation aspects.

---

## Technologies used

* SQL – data modeling and calculations
* Power BI – interactive visualization and simulation
