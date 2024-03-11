# Symulacja Monte Carlo Modelu Isinga
Model Isinga to model matematyczny wykorzystywany w mechanice statystycznej do badan nad przejsciami
fazowymi.
Symulacje wykonałam implementujac algorytm Metropolisa dla modelu Isinga bez pola magnetycznego na
dwuwymiarowej sieci kwadratowej L × L.
Aby wykonac wykresy, skorzystałam z nastepujacych wzorów:

1. srednia wartosc spinu:

$$ m = \cfrac{1}{L ^2} \sum ^{L^2} _{i,j = 1} S _{ij} $$

2. magnetyzacja:

$$ \langle m \rangle = \cfrac{1}{L^2} \sum^{l_sym}_{m_j} |m_j| $$

3. podatność:

$$ \mathcal{X} = \cfrac{N}{k_BT} (\langle m^2 \rangle - \langle m \rangle ^2)$$

## WYKORZYSTANE NARZĘDZIA:
Python

Biblioteki: numpy, scipy, matplotlib.pyplot, matplotlib.animation, numba, IPython.display
