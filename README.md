Лабораторная работа №5.

Задача классификации изображений.

Цели:
Знакомство с принципами использования нейросетей.

Задача:

Keras — открытая нейросетевая библиотека, написанная на языке Python. Она представляет собой мощную высокоуровневую надстройку (frontend) для TensorFlow. Библиотека нацелена на оперативную работу с сетями глубокого обучения, при этом спроектирована так, чтобы быть компактной, модульной и расширяемой. Keras предоставляет высокоуровневый, более интуитивный набор абстракций, который делает простым формирование нейронных сетей.

В качестве ознакомления с нейронными сетями и наглядного примера использования Keras, решим задачу классификации. Попробуем распознать предметы одежды, используя набор данных Fashion MNIST (сокращение от «Modified National Institute of Standards and Technology»). Этот набор представляет из себя 60000 изображений для обучения и 10000 изображений для тестирования качества работы сети. Сами изображения представлены в оттенках серого с разрешением 28 на 28 пикселов. Набор данных Fashion MNIST содержит 10 различных классов изображений. В английском языке под словом «fashion» подразумевается стиль, мода, образ. Поэтому набор данных, помимо видов одежды, содержит так же сумки и обувь.

Необходимо улучшить точность, используя следующие методы:

- Сделать сеть глубокой
- Выбрать наилучший оптимизатор
- Изменить количество эпох
- Изменить объем мини-выборки
- Увеличить число нейронов первом слое