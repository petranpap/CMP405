# Titanic Dataset

**Σκοπός:** Πρόβλεψη της επιβίωσης των επιβατών (Classification)

## Περιγραφή
- `Survived`: Target (0 = όχι, 1 = ναι)
- Χαρακτηριστικά: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

## Τι μαθαίνουμε
- Πώς διαχειριζόμαστε missing values (`Age`)
- Encoding κατηγορικών (`Sex`, `Embarked`)
- Χρήση `LogisticRegression` / `RandomForest`

## Οδηγίες (Google Colab)
1. Φόρτωσε το CSV (`pd.read_csv(...)`)
2. Εξερεύνησε με `df.head()`, `df.info()`
3. Χειρίσου τα κενά
4. Κάνε encoding των κατηγορικών
5. Διαχώρισε `X`, `y`, μετά `train_test_split`
6. Εκπαίδευσε μοντέλο
7. Αξιολόγησε με `accuracy_score`, `confusion_matrix`
