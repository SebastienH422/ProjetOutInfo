# ProjetOutInfo

# Source de données:

Quantité: (3, 5, 8)

|                                 | xlsx      | tsv      | json     | xml (2 et 3) | csv (1 et 2) | librairie | Autres   |  | Format choisi | Téléchargé par |
|---------------------------------|-----------|----------|----------|--------------|--------------|-----------|----------|--|---------------|----------------|
| PIB                             | X         |          |          | X            | X            |           |          |  | csv1          | Julie          |
| Taux de chômage                 | X         | X        | X        | X            | X            |           |          |  | xml2          | Seb            |
| Taux d'intérêts des dépôts      | X         |          |          | X            | X            |           |          |  | xml3          | Julie          |
| IPCH                            | X         | X        | X        | X            | X            |           |          |  | json          | Seb            |
| Historique des actions          |           |          |          |              |              | X         |          |  | librairie     | Seb            |
| Devise                          | X         | X        |          |              | X            |           | sdmx-scv |  | csv2          | Julie          |
| Matières premières              | X         | X        |          |              | X            |           |          |  | tsv           | Julie          |
| Dette extérieure nette          | X         | X        |          |              | X            |           | sdmx-scv |  | xlsx          | Seb            |

##### Commentaires
- **PIB** - Le PIB est également essentiel pour une analyse de l'économie d'un pays. Un PIB croissant est souvent synonyme d'une économie forte, ce qui peut avoir un impact direct sur les actions.
- **Taux de chômage** - Le taux de chômage est un indicateur important de la santé économique d'un pays. Un faible taux de chômage peut indiquer une économie robuste, ce qui est favorable pour le marché boursier.
- **Taux d'intérêts des dépôts** - Les taux d'intérêt influencent les investissements dans les actions. Des taux d'intérêt bas peuvent rendre les actions plus attrayantes par rapport aux investissements à faible rendement, comme les dépôts bancaires.
- **IPCH** (Indice des Prix à la Consommation Harmonisé) - L'inflation est un facteur important à considérer, car elle influence les taux d'intérêt et peut affecter les décisions d'investissement. L'IPCH est un bon indicateur pour analyser l'inflation en Europe.
- **Historique des actions** - L'historique des actions est essentiel pour analyser les tendances passées et prévoir les évolutions futures des actions. Bien que cela ne soit pas directement un indicateur économique global, il fournit des données clés pour les prévisions.
- **Devise** - La fluctuation des devises peut avoir un impact significatif sur les actions, surtout pour les sociétés internationales. L'analyse des taux de change est importante pour les prévisions à court et moyen terme.
- **Matières premières** - Les matières premières, bien qu'elles n'affectent pas directement le marché des actions dans tous les secteurs, sont cruciales pour certaines industries (énergie, métallurgie, etc.), ce qui peut influencer l'économie et, par conséquent, les actions des entreprises concernées.
- **Dette extérieure nette** - La dette extérieure nette peut signaler la stabilité économique d'un pays. Un niveau élevé de dette extérieure peut poser des risques pour l'économie, influençant ainsi les marchés boursiers.


## Seb

### Taux de chômage 
**Période**: 2012 - 2023\
**Répartition géographique**: Europe\
**Source**: https://ec.europa.eu/eurostat/databrowser/view/tps00203/default/table?lang=fr&category=t_labour.t_employ.t_lfsi.t_une

##### Formats disponibles
- xlsx
- tsv
- json
- xml (2 et 3)
- csv (1 et 2)

##### Personalisation
- % pop active
- % pop tot
- millier de personnes
- séparateurs, format, ...

### IPCH
**Période**: 2012-2023\
**Répartition géographique**: Europe\
**Source**: https://ec.europa.eu/eurostat/databrowser/view/tec00118/default/table?lang=fr&category=t_prc.t_prc_hicp

##### Formats disponibles
- xlsx
- tsv
- json
- xml (2 et 3)
- csv (1 et 2)

### Historique des actions
**Periode**: 2010-2024
**Répartition géographique**: Mondiale
**Source**: yahoo finance (librairie)


## Julie

### Taux d'interêts des dépots
**peirode** 1960-2024
**Source**:=https://donnees.banquemondiale.org/indicateur/FR.INR.DPST?most_recent_value_desc=false&view=chart
**répartition geographique** : mondiale

### Formats disponibles :
-csv
-xlm
-excel


### Croissance du PIB
**periode** : 1961- 2024\
**Répartition géographique**: Mondiale\
**Source** : https://donnees.banquemondiale.org/indicateur/NY.GDP.MKTP.KD.ZG?view=chart

### Formats disponibles :
-csv
-xlm
-excel

### PIB
**periode** : 1961- 2024\
**Répartition géographique**: Mondiale\
**Source** : [https://donnees.banquemondiale.org/indicateur/NY.GDP.MKTP.KD.ZG?view=chart](https://donnees.banquemondiale.org/indicateur/NY.GDP.MKTP.CD?year=2022)

### Formats disponibles :
-csv
-xlm
-excel

### Population
**periode** :2013 - 2024 \
**Répartition géographique**:Europe\
**Source** :https://ec.europa.eu/eurostat/web/main/data/database 

### Format disponible :
-tsv
### Matières premières 
**periode** :1991 -2024
 ### formats disponibles 
 - xlsx
 - csv
**source generale** :https://www.insee.fr/fr/information/3128533?\
**petrol brut brent** : https://www.insee.fr/fr/statistiques/serie/010002091#Telechargement\
**argent** : https://www.insee.fr/fr/statistiques/serie/010002086#Telechargement\
**or** : https://www.insee.fr/fr/statistiques/serie/010002100#Telechargement\
**paladium** : https://www.insee.fr/fr/statistiques/serie/010767332#Telechargement

### ECU/EUR exchange rates versus national currencies

**periode** : 2012 - 2024\
**Source** : https://ec.europa.eu/eurostat/databrowser/view/tec00033/default/table?lang=en&category=t_ert

 ### formats dipsonibles
 - xlsx
 - tsv
 - sdmx-csv

### Dette exterieure nette 
**periode**  1995 -2023 \
**Répartition géographique** : europe\
**source** : https://ec.europa.eu/eurostat/databrowser/view/tipsii20/default/table?lang=en&category=tips.tipsed
**source actuelle** https://ec.europa.eu/eurostat/databrowser/view/sdg_17_40/default/table?lang=fr
### Formats disponibles :
-xlsx
-tsv
-sdmx-csv





# Essentiel
Indicateurs géopolitiques: Données sur les conflits, les sanctions économiques, les politiques fiscales et commerciales des grands pays (États-Unis, Chine, etc.).

Balance commerciale et déficit budgétaire
- Données sur les exportations, importations, et le solde commercial.
- Déficit ou excédent budgétaire d'un gouvernement.

Taux d'intérêt directeur des banques centrales
- Taux d'intérêt de la BCE (Banque centrale européenne), de la Fed (Réserve fédérale des États-Unis), etc.


Historique des prix des actifs financiers (, obligations, matières premières, crypto-monnaies, etc.)\
Exemple :
- Prix historiques des actions (ex. : Apple, Tesla, ou un indice sectoriel).
- Cours des matières premières (pétrole, or, argent, etc.).
- Cours des devises (par exemple, EUR/USD, USD/JPY, etc.).
- Indices boursiers (ex. : S&P 500, Dow Jones, Nasdaq).

Données sur la répartition sectorielle de l'économie
- Contribution de chaque secteur à l’économie (agriculture, industrie, services).

# Secondaire

Indicateurs de confiance: Confiance des consommateurs et des entreprises (ex. : indice de confiance des consommateurs, indice de confiance des directeurs d'achats).

Age moyen

Indices de développement humain (IDH): Indicateur composite qui mesure la qualité de vie dans un pays (éducation, santé, niveau de vie).

Analyse sectorielle
- Performances des secteurs (par exemple, technologie, santé, consommation, énergie).
- Comparaison des performances des secteurs à l’échelle mondiale ou régionale.

Données sur les fusions et acquisitions
- Historique des transactions de fusions et acquisitions dans certains secteurs.
