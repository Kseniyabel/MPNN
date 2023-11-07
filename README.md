# MPNN
Пример использования MPNN для предсказания терапевтической активности молекул при помощи из SMILES.
Данные получены из базы данных Drug Bank https://go.drugbank.com/releases/latest
Разделение лекарственных молекул на классы произведено при помощи ATC (АТХ) классификации 4го уровня (на данном уровне учитываются как химические особенности молекулы, так и мишень, на которую она действует).
Реализация MPNN произведена при помощи https://keras.io/examples/graph/mpnn-molecular-graphs/
