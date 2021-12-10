# Concessionario

## (Table) cars:

- id | BIGINT -  PRIMARY KEY, AUTO INCREMENT, UNIQUE, NOTNULL
- targa | VARCHAR(7) - NOTNULL, UNIQUE
- marca | VARCHAR(20) - NOTNULL
- modello | VARCHAR(20) - NULL
- versione | VARCHAR(255) - NULL
- anno_immatricolazione | YEAR - NULL
- paese_immatricolazione | VARCHAR(255) - NULL
- carburante | VARCHAR(20) - NULL
- chilometraggio | MEDIUMINT - NULL
- cilindrata | SMALLINT - NULL
- potenza_cv | SMALLINT - NULL
- cambio | VARCHAR(20) - NULL
- numero_porte | TINYINT - NULL
- carrozzeria | VARCHAR(20) - NULL
- numero_posti | TINYINT - NULL
- condizione | VARCHAR(20) - NULL
- equipaggiamento | TEXT - NULL
- colore_carrozzeria | VARCHAR(20) - NULL
- tipo_vernice | VARCHAR(20) - NULL
- colore_interni | VARCHAR(20) - NULL
- materiale_interni | VARCHAR(20) - NULL
- proprietari_precedenti | TINYINT - NULL
- veicolo_danneggiato | DEFAULT(0) - NULL
- tagliandi_certificati | DEFAULT(0) - NULL
- veicolo_non_fumatori | DEFAULT(0) - NULL
- classe_emissioni | VARCHAR(13) - NULL
- note | TEXT - NULL