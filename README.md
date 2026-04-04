# MIB-Version-Table

| Train version | Generation | Tier | Production | Technische Bezeichnung | Markenbezeichnung | Modelle / Plattformen | Besonderheiten | Jahr |
|---|---|---|---|---|---|---|---|---|
| MSTD | MIB1 | Standard | Panasonic | MIB1 Standard | Discover Media / Amundsen / Media System | VW, Skoda, SEAT | Erste MIB1 Standard Plattform | ab ~2013 |
| MHIG | MIB1 | High | Harman | MIB1 High | Discover Pro / Columbus / Navigation Plus | Audi A3 (8V), VW | Erste High-End Variante | ab ~2013 |
| MEN2 | MIB2 | Entry | LG | MIB2 Entry | Composition Touch / Swing / Media System Touch / Color | VW, Skoda, SEAT Ibiza (2017) | Basis-System ohne Navigation | ab ~2015 |
| MST2 (D) | MIB2 | Standard | Delphi (Aptiv) | MIB2 Standard (D) | Composition Media | VW | Delphi Variante | ab ~2015 |
| MST2 (T) | MIB2 | Standard | Technisat / Preh | MIB2 Standard (T) | Composition Media / Amundsen / Media System | Skoda, SEAT | Technisat Variante | ab ~2015 |
| MS2p | MIB2 | Standard Plus | Delphi (Aptiv) | MIB2 Standard Plus | Audi Radio Plus | Audi A4 (8W), A5 (F5), Q5 (FY) | Audi-spezifisch | ab ~2016 |
| MHS2 | MIB2 | Scale | Delphi (Aptiv) | MIB2 Scale | MMI Navigation / Audi connect | Audi A4 (8W), A5 (F5) | Navigation vorbereitet | ab ~2016 |
| MHI2 | MIB2 | High | Harman / Aisin | MIB2 High | MMI Navigation Plus / Discover Pro / Columbus | Audi TT (FV), A4 (8W), A5 (F5), Q7 (4M) | Erste Einführung TT 2016 | 2016–2018 |
| MHI2Q | MIB2 | High | Harman + Qualcomm | MIB2 High (Q) | MMI Navigation Plus | Audi | Qualcomm SoC | ab ~2017 |
| MH2p | MIB2+ | High Plus | Aptiv / Alpine (Multi-Vendor) | MIB2 High Plus | MMI Navigation Plus (MIB2+) | Audi A6 (4A), A7 (4K), A8 (4N), Q7 (4M), Q8 (4M), e-tron (GE) | Neue Generation innerhalb MIB2 | ab ~2018 |
| PCM 4 / 4.1 | MIB2 | High | Harman | Porsche PCM 4 | Porsche Communication Management | Porsche 911 (992), Cayenne (E3), Macan (95B), Panamera (976) | MIB2-basiert | 2019–2022 |
| PCM 5 / 5.x | MIB2+ | High Plus | Harman / Aptiv | Porsche PCM 5 | Porsche Communication Management 5.x | Porsche Cayenne (E3), neuere Modelle | MIB2+ Architektur | ab ~2018 |
| MEN3 | MIB3 | Entry | Panasonic | MIB3 Entry | Composition Color / Swing | VW, Skoda | Entry-Level MIB3 | ab ~2020 |
| MOI3 (LG) | MIB3 | Standard | LG | MIB3 Standard | Discover Media / Pro / Media System | VW, SEAT | LG Variante | ab ~2020 |
| MOI3 (Preh/PCC) | MIB3 | Standard | Preh / PCC | MIB3 Standard | Discover Media / Amundsen / Columbus | Skoda | Multi-Vendor | ab ~2020 |
| MBA3 | MIB3 | Basic | Aptiv | MIB3 Basic | MMI Radio Plus | Audi A3 (8Y), Q3 (F3) | Einstieg Audi MIB3 | ab ~2021 |
| MHI3 | MIB3 | High | Aptiv | MIB3 High | MMI Navigation | Audi A4 (8W FL), A5 (F5 FL), Q5 (FY), Q7 (4M), Q8 (4M) | Weiterentwicklung | 2020–2021 |
| MPR3 | MIB3 | Premium | Aptiv | MIB3 Premium | MMI Navigation Plus | Audi A6 (4A), A7 (4K), A8 (4N), e-tron (GE) | High-End | ab ~2021 |
| MOI3GP (LG) | MIB4 | Standard | LG | MIB3GP / MIB4 | Discover Media / Pro | VW | Neue Plattform | ab ~2023 |
| MOI3GP (Preh/PCC) | MIB4 | Standard | Preh / PCC | MIB3GP / MIB4 | Discover Media / Amundsen / Columbus | VW, Skoda | Multi-Vendor | ab ~2023 |
| MOI3EI | MIB4 | Entry | unklar | MIB4 Entry | – | – | nicht eindeutig bestätigt | unklar |

## MIB Train-Version Naming Convention
```
<TrainPrefix><Gen><Suffix>_<Region>_<Brand/Variant>_<Platform>_<Version>
```
### 1. Region Codes:

| Code | Country |
|---|---|
| AS | Asia |
| CN | China |
| EU | Europe |
| ER | Europe + Rest of World |
| JP | Japan |
| KR / XB | South Korea |
| NAR | North America Region |
| US | United States |
| RoW | Rest of the World |
| RoA | Rest of Asia |
| TW | Taiwan |

### 4. Brand/Variant Codes:

| Code | Brand / Explanation |
|---|---|
| AU | Audi (10.1” Screen) |
| AUG | Audi |
| AUASUV | Audi e-tron (MHI3) |
| AUG33 | Audi 9.2” MH2p |
| AUG35 | Audi 10.1” MH2p |
| AUG45S | Audi 15” MHI3 |
| BYG24 | Bentley |
| BYG46S | Bentley (MHI3) |
| BYSUV | Bentley SUV |
| LB | Lamborghini |
| LB636 | Lamborghini (MH2p) |
| LB46S | Lamborghini (MPR3) |
| POG | Porsche |
| PO416 | Porsche 10.9” (MH2p) |
| POG11 / POG24 | Porsche Varianten |
| POG35 | Porsche 12.3” (MH2p) |
| POG46 | Porsche (MPR3) |
| SE | Seat |
| SEG11 | Seat 8” |
| SEGPx | Seat MEN3 (6.5”) |
| SEMQB | Seat MOI3 |
| SK | Skoda |
| SKG11 | Skoda 8” |
| SKG13 | Skoda 9.2” (MIB2.5) |
| SKGPx | Skoda MEN3 |
| SKMQB | Skoda MOI3 |
| VW | Volkswagen |
| VW37W | VW (MHI3) |
| VWG11 | VW 8” |
| VWG13 | VW 9.2” (MIB2.5) |
| VWG33 | VW 9.2” MH2p |
| VWG36 | VW 15” MH2p |
| VWGPx | VW MEN3 |
| VWMQB | VW MOI3 |

### 3. Platform Codes:

| Code | Explanation |
|---|---|
| PQ | All-in-one Unit (Display + Main Unit kombiniert) |
| ZR | Zentralrechner (separate Headunit + Display) |

### 4. Version Codes:

| Code | Explanation |
|---|---|
| E | Engineering / Beta |
| K | Customer Update |
| P | Production |
| R | Release / Serienstand |
| S | Security Fix |

### 5. Example:
MH2pQ_EU_AUG35_ZR_P

MH2pQ  =    MIB2+ High Plus with Qualcomm
EU     =    Europe
AUG35	 =    Audi 10.1” Display
ZR	   =    Separate Headunit
P	     =    Productionversion

Audi MIB2+ High-End System (A6/A7/A8), Europe, Production
