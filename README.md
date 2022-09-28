# Este es mi primer proyecto en GitHub

## Estamos modificando el archivo ReadMe

### Haciendo algunas pruebas ingeniosas

Este es un repositorio creado a modo de ejemplo para el manual de GitHub desktop, es un gran día para aprender a usar esta herramienta.

notas_alumnos<- c(7, 6.2, 5, 3.4, 5.6, 6.5, 7, 4.8, 2.5, 
                  1.7, 4,5, 3.2)
total_notas <- 0
for (nota_alumno in notas_alumnos) {
  total_notas <- total_notas + nota_alumno
}
promedio_final <- total_notas/length(notas_alumnos)
print(paste("El promedio final de las notas es", 
            promedio_final))