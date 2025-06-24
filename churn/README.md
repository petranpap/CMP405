# Customer Churn Dataset

**Σκοπός:** Πρόβλεψη αν ένας πελάτης παύει υπηρεσίες (Classification)

## Περιγραφή
- `Churn`: Target (Yes/No)
- Χαρακτηριστικά: `Tenure`, `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`, κ.ά.

## Τι μαθαίνουμε
- Πώς χειριζόμαστε string to numeric μετατροπές
- Πώς αναλύουμε συσχετίσεις
- Χρήση `DecisionTree` ή `SVM`

## Οδηγίες (Google Colab)
1. Φόρτωσε το CSV
2. Εξέτασε `df.columns`, `df.dtypes`
3. Καθάρισε `TotalCharges`
4. Encode κατηγορικά
5. `train_test_split`, εκπαίδευσε μοντέλο
6. Αξιολόγησε με `precision`, `recall`
