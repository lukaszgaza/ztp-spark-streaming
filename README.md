# Spark Streaming

Spark Streaming to rozszerzenie Spark pozwalające na przetwarzanie danych strumieniowych. Zapoznać z nim można się [tutaj](https://spark.apache.org/docs/latest/streaming-programming-guide.html).

### Zadanie
Zaimplementuj program wyświetlający średni czas spędzany przez użytkowników na danej stronie (średnią z ostatnich 30 sekund).

* Stwórz program w Pythonie generujący dane mówiące ile czasu użytkownik o danym id spędził na danej stronie internetowej.
* Powyższy program generowane dane powinien wysyłać na topic kafki.
* Powyższy program powinien generować dane w sposób strumieniowy.
* Stwórz program, korzystając ze Spark Streaming, wypisujący na ekran średni czas spędzany przez użytkowników na danej stronie (średnią z ostatnich 30 sekund).
* Dane powinny być wyświetlane w postaci tabeli.
* Całość powinna działać jako kontenery Dockera (jeden lub kilka kontenerów).