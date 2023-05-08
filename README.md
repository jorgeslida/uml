#Diagramas de classes
  ##Animales
El siguiente diagrama representa la estructura de classes de los tipos de animales de la aplicacion
```mermaid

classDiagram
class Perro extends Animal{
  String raza;
  String morder(String cosa) {
      return null;
      }
      
      @Override
      void sonar(){
      }
}

abstract class Animal {
  void alimentar(){
  }
  abstract void sonar();
  
  
  class Animal {
    void sonar()*
   }
   
   Animal <|--Perro


```
