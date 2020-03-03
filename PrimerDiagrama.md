```mermaid

classDiagram

      Persona <|-- Estudiante
      Persona <|-- Profesor

      class Persona{
          <!--Propiedades-->
         -nombre : String
         -edad : Integer
         <!--constructor-->
         +Persona()
         <!--mostrar Nombre-->
         +getNombre()
         <!--modificar Nombre-->
         +setNombre()
         <!--mostrar Edad-->
         +getEdad()
         <!--modificar Edad-->
         +setEdad()
      }

      class Estudiante{
          <!--Propiedades-->
          -carrera : String
          -expediente : Integer
          <!--constructor-->
          +Estudiante()
          <!--mostrar Carrera-->
          +getCarrera()
          <!--modificar Carrera-->
          +setCarrera()
          <!--mostrar Expediente-->
          +getExpediente()
          <!--modificar Expediente-->
          +setExpediente()
      }

      class Profesor{
          <!--Propiedades-->
          -materia : String
          -cargo : String
          <!--constructor-->
          +Profesor()
          <!--mostrar Materia-->
          +getMateria()
          <!--modificar Materia-->
          +setMateria()
          <!--mostrar Cargo-->
          +getCargo()
          <!--modificar Cargo-->
          +setCargo()
        }
