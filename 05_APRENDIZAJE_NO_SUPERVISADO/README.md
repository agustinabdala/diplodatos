GRUPO N8

Comentarios adicionales:
- se utilizó K-means con 5 clusters porque luego de probar según lo recomendado por la regla del codo, este valor (un poco superior al sugerido) separaba de una manera más orgánica y clara el dataset.

- para dbscan se probaron con numerosas cantidades de clústers, y encontramos que era más significativa y balanceada la cantidad usada en cada prueba de concepto (5 en el primer caso, luego 2, y finalmente en el PCA de 4 componentes se alimentó un modelo de 3 clueters kmeans)

- Al usar PCA previamente, en el último Kmeans, se obtiene una perspectiva más abstracta y compacta que podría ser analizada con mayor detalle en posteriores (e hipotéticas) etapas.
