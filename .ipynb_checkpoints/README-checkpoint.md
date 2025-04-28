# Dataset Information

The data in the 'Dataset' folder comes from the [Hyacinth Bean Image Dataset](https://www.kaggle.com/datasets/pratikgorde/hyacinth-bean-image-dataset) on Kaggle.

---

## Recommended Execution Order:

1) `Augmentation.ipynb`
2) `projekt_ML_eda_ostateczna.ipynb`
3) `sieci_neuronowe.ipynb`
4) `Clasification.ipynb`
## Projekt gotowy znajduje sie w folderze ostateczny projekt, a w nim:
1) 4 pliki wymienione powyżej
2) 2 pliki z ramkami danych - testowa i treningowa
3) Eda chyba dobrze zrobiona, by uzyskać obie ramki danych ze zdjęć to trzeba wykonać ją na części treningowej, a następnie na testowej(na początku i na końcu pliku jedna z tych 2 części jest zakomentowana)
4) Sieci neuronowe jednak nie były takie super, zwykłą MLP po różnych poprawkach udało się maksymalnie doprowadzić do 95%, natomiast CNN pomimo wielu prób nie osiągneła nawe 90% accuracy, więc nie były nawet liczone inne metryki
5) Najskuteczniejszy okazał się modele SoftVote z wagami, a po optymalizacji hiperparametrów udało się osiągnąć ponad 98% we wszystkich metrykach, gdzie próbka testowana wynosiła prawie 700 nasion
6) Stacking również był niezły, ale inne modele były już znacznie gorsze


