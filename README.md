# ESP32-IOT
Prototipo para la medición de variables físico químicas en cultivos de arroz mediante la plataforma Arduino.
@Autores:
  Diego Andres Florez
  Medardo Vergara Tovar
@Programa de ingenieria de sistemas.
@Corporacion univercitaria remington.
------------------------------------------------------------------------------------------------------------------

GUIA DE CONFIGURACION ARDUINO IDE Y ESP32 

#Instalar placa esp32 IDE Arduino:
  -Archivo
    -Preferencia
      -gestor de url adiciones de targetas  pegar el siguiente link: https://dl.espressif.com/dl/package_esp32_index.json
      -ir a herramientas 
        -gestionar librerias
          -escribir en el la barra de busqueda ESP32
            -instalar y esperar la descarga
  
#seleccionar placa:
  -ir a herramientas-palca-ESP32 ARDUINO
    -Seleccionar "ESP32 DEV MODULE"
  
#Solución error (Leaving...Hard resetting via RTS pin...)
  -Ir a herramientas y seleccionar flash frequency 40mhz.

