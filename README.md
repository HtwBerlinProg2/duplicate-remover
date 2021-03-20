# Duplicate Remover

Gegeben ist das generische Interface `DuplicateRemover<T>`:

```java
public interface DuplicateRemover<T> {

  T removeDuplicates(T values);
}
```

Die Methode nimmt `values` vom Typ `T` (generischer Datentyp) über den Methodenparameter entgegen und soll alle vorhandenen Duplikate entfernen. `T` kann ein beliebiger Datentyp sein, also bspw. eine `List` oder eine `Map`. 

## Aufgaben

1. Implementieren Sie einen `ListDuplicateRemover`, der das Interface `DuplicateRemover` korrekt implementiert. Ihre Klasse soll aus einer Liste alle Duplikate entfernen und die bereinigte Liste am Ende zurückgeben. Stellen Sie die korrekte Funktionsweise über einen Unit-Test sicher.
2. Implementieren Sie einen `MapDuplicateRemover`, der das Interface `DuplicateRemover` korrekt implementiert. Ihre Klasse soll aus einer Map alle Duplikate in den Values entfernen und die bereinigte Map am Ende zurückgeben. Stellen Sie die korrekte Funktionsweise über einen Unit-Test sicher.
