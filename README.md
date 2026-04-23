# PL-300

Bienvenue. Pour importer un fichier dans Power Query, cliquez sur `Nouvelle source` puis `Web`, copiez-collez le lien du fichier a importer ci-dessous, puis pensez a renommer votre requete dans Power Query.

## Calendrier

```dax
Calendrier =
ADDCOLUMNS (
	CALENDARAUTO (),
	"Annee", YEAR ( [Date] ),
	"Mois", FORMAT ( [Date], "MMMM" ),
	"NumMois", MONTH ( [Date] ),
	"Trimestre", "T" & FORMAT ( [Date], "Q" )
)
```

## DimProduct.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/DimProduct.xlsx
```

## DimProductCategory.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/DimProductCategory.xlsx
```

## DimProductSubcategory.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/DimProductSubcategory.xlsx
```

## Product.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/Product.xlsx
```

## Region.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/Region.xlsx
```

## Salesperson.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/Salesperson.xlsx
```

## SalespersonRegion.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/SalespersonRegion.xlsx
```

## Targets.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/Targets.xlsx
```

## Ventes.xlsx

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/Ventes.xlsx
```

## PL 300.zip

```text
https://github.com/votredatacoach/PL-300/raw/refs/heads/main/PL%20300.zip
```
