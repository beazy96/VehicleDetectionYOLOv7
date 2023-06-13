# VehicleDetectionYOLOv7

Program wykorzystuje algorytm YOLOv7 w celu wytrenowania modelu rozpoznającego pojazdy i pokazuje jak niezbilansowanie liczby obiektów reprezentujących poszczególne klasy wpływa na skuteczność detekcji.

Zbiór danych został przygotowany przy użyciu Roboflow. Posiada on gotowe oznaczenia obiektów zgoden z formatem YOLO.

Zbiór danych zawiera niezbalansowaną liczbę obiktów reprezentującą poszczególne klasy.

[![Class-Balance.jpg](https://i.postimg.cc/Mp21LdCP/Class-Balance.jpg)](https://postimg.cc/7f9CGMY0)

Zbiory danych:

[![Test-Val-Train.jpg](https://i.postimg.cc/wvHJBMqh/Test-Val-Train.jpg)](https://postimg.cc/8FKsK1r5)

Program radzi sobię dobrze z rozpoznawaniem obiektów takich jak samochody i autobusy, a posiada problem z rozróżnieniem rowerów i motocykli.

[![good.jpg](https://i.postimg.cc/23pT2mdT/good.jpg)](https://postimg.cc/WqnM1BHJ)

[![bad.jpg](https://i.postimg.cc/Gmjw8Sr6/bad.jpg)](https://postimg.cc/75bQj95N)
