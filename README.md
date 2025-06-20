![VALVULAS](https://github.com/user-attachments/assets/70f42e3e-575c-4d06-8047-ba353e285fab)

# istema-de-control-de-presi-n
El sistema está compuesto por un recipiente de proceso al que se le controla la presión interna mediante un esquema automático de control. El flujo de material hacia y desde el recipiente está regulado por dos componentes principales:
Válvula de entrada (Reactivos): Permite la introducción de los materiales al interior del recipiente. Su apertura es controlada automáticamente en función de la presión interna.

Válvula de salida (Productos): Permite la liberación del contenido del recipiente, ayudando a mantener el equilibrio del sistema de presión.

En el corazón del sistema se encuentra un controlador PID, el cual actúa sobre las válvulas para mantener la presión deseada dentro del recipiente. Este controlador recibe señales constantes de un transmisor de presión (PT) que monitorea el valor de presión en tiempo real. Al comparar la presión medida con el punto de ajuste predefinido, el PID ajusta las válvulas de entrada y salida con precisión para corregir cualquier desviación.
