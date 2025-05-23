# Actividad-23-05


## Diagrama de clases Sistema de Reserva de Salas 


1. Dentro del diagrama no existe alguna relacion con include y extend que se pueda visualizar.
2. El apartado de Ver historial de otras personas con el actor Estudiante estimo que no es apropiado el poder ver el historia de otros estudiantes, siempre y cuando cumpla con algun parametro de provacidad, ahi puede estar bien.
3. El administrador puede notificar cambios por correo, pero no es lo mas optimo si ya tiene un actor de sistema de notificaciones, lo cual haria que el sistema podria duplicar las notificaciones
4. El estudiante puede agregar un motivo de cancelacion, pero este ultimo queda flotando en el diagrama sin llegar a ningun lado

---

## Diagrama de clases

1. La clase usuario puede realizar "reservarReserva" y "cancelarReserva" pero en el diagrama de caso de uso puee realizar mas: "ver historial de otras personas, ver estado de solicitud, ver y borrar historial"
2. no existe algun orden entre la relacion de las clases, por ejemplo la clase Reserva esta sin alguna conexion con alguna otra clase e incluso tiene una liena hacia la nada.
3. todo el sistema de notificacion no tiene alguna manera de recivir informacion

---

##
   
