# Evaluacion_Modulo-01_Calculadora_IMC

DESARROLLO DEL PROGRAMA:
Evaluación de conocimientos adquiridos y técnica en el manejo de código de Python para generar una Calculadora de IMC funcional capaz de capturar, almacenar y entregar datos diversos en forma de texto y números.

Para crear este programa se tuvo en consideración la necesidad de conocer y representar variables de nombre, apellido paterno, apellido materno, peso, edad, estatura y valor de IMC.

En atención a ello, se configuró un input donde el usuario puede registrar nombre y apellidos en una misma linea de texto. Una vez recabada esta oración, se procede a dividir los nombres ingresados mediante split para luego generar lista de nombres individuales, los cuales son formateados a modo de título, utilizados para calificar el ingreso de solo letras en cada palabra y que se cuenta con al menos tres palabras distintas (nombre y apellidos) con extensión de tres o más caracteres dentro de bucle for. 

En caso de cumplirse todos los requisitos, se avanza al siguiente paso por medio de else. En caso contrario (uno o dos nombres solamente, ingreso de datos numericos, ingreso de nombres con ocho o menos caracteres en total), se cumple condición if y se repite proceso hasta quedar registrados los datos solicitados correctamente.

En cuanto al ingreso de cifras numericas con int(input) y float(input) para determinar valor peso, estatura y edad, se usaron bloques try para verificar el registro de solo números y ofrecer una amplia de cobertura para posibles datos erroneos o falsos entrados por el usuario en la forma de bloques except asignados con clase ValueError. Se asigna rango valido de edad, peso y estatura por medio de condición if con valores diversos aplicables para la generalidad de personas. Se crean dos condiciones if dentro del apartado edad para determinar si se trata de un menor de edad o de una persona adulta, cambiando en consecuencia factores para determinar el IMC correctamente dentro de su respectivo rango de edad. 

De igual forma se convierte valor de tres digitos ingresado por el usuario en en estatura, ej. 194. a numero entero con dos decimales para aplicación de calculo de IMC, ej. 1.94.

Se hace uso de lista lista_metricas para almacenar valores númericos validos ingresados a la calculadora, regresando mensaje de confirmación y avanzando consecutivamente hasta llegar a apartado final de resultados.

En caso de introducirse dato no valido, se repite la etapa de captura de datos que corresponda hasta que se introduzca un dato aceptable para el programa. En caso de cumplirse condición solicitada en rango de valores planteado, se activa break en el programa y se da inicio a siguiente fase de captura de datos.

En el apartado de resultados se hace operacion peso en kilos/estatura en metros/estaturapersona para obtener valor del IMC. Se ofrece lista de total de datos ingresados por el usuario para ejecutar programa de calculadora IMC (Nombre: nombrecompleto | Edad: edadpersona años | Peso: pesokilos | Estatura: estaturapersona | IMC: resultado de operacion). Se hace uso de condiciones if y elif para asignar mensaje de desnutrición, peso saludable o caso de obesidad en base a si la persona tiene menos de 11 años, si tiene 11 entre 18 años o si es mayor de edad, ademas del lugar en que se ubica la persona con respecto a su IMC (valor menor a 13.10 a valor mayor a 29.30 para menor de edad / valor menor a 18.50 a valor mayor a 40.00 para menor de edad).

Se restablece lista de nombre booleano y registro de datos metricos a listas vacias para el posible futuro ingreso de 

Como punto final, se establece un punto de decisión al inicio y fin de operación de la calculadora, donse se le presenta al usuario la opción de continuar con el proceso o si desea cerrar el programa. Solo se admite la entrada del caracter S y N en minuscula o mayuscula. La entrada de cualquier otro caracter resulta en la repetición del ciclo hasta que se ingrese dato valido.

-----------------------------

OBSERVACIONES DURANTE DESARROLLO DEL PROGRAMA:
Se presentaron complicaciones en lo que fue la captura, registro y muestra de nombre y apellidos, ya que inicialmente se tenia contemplado hacer uso de listado de nombre de pila, apellido paterno y apellido materno por separado dentro de tabla de resultados, clasificación solicitada en instrucciones que ya se encontraba cumplida con el requisito de ingresar un mínimo de tres nombres para continuar el proceso de captura de datos.

Tambien se tomo en cuenta para el desarrollo del programa la aplicación de principios de programación defensiva para el manejo de errores y la entrada de datos falso o incorrectos por el usuario, probandose cada segmento de la calculadora individualmente hasta que el registro de nombre, edad, peso y estatura se ejecutaron correctamente. De igual forma se comprobó la ejecución del programa en su totalidad una vez llegado al punto de tabla de resultados, probando colocación dentro de tabla de IMC por rango de edad y resultado de operacion peso/estatura/estatura.

-----------------------------

REFLEXIONES DEL BOOTCAMP UTEL - FUNDAMENTOS DE PYTHON C28 - MODULO 01:
Me siento muy satisfecho con los aprendizajes adquiridos a lo largo del curso, ya que al inicio no contaba con conocimiento alguno acerca del tema y ahora puedo entender como se puede llevar a cabo la entrada de datos en un programa informatico creado en python, como se distingue un string, una variable y cadena formateada, la forma en que debe prepararse una entrada de datos para recibir texto, número entero y número con decimales. 

Asimismo, aprendí sobre algunos metodos para modificar los datos almacenados en variables y operaciones aritmeticas ejecutadas dentro de un programa de Python y la forma en que se puede cargar y actualizar archivos desde un sistema local a una cuenta de GITHUB personal.

Considero que el modelo de Bootcamp UTEL para Python es muy provechoso al manejar una serie de dinamicas practicas y ser muy accesible en cuanto a horarios de trabajo y tiempos de estudio. El uso de videos informativos, ejercicios y sesiones en vivo semanales permite adquirir nuevos conocimienttos a un ritmo dinamico y acorde a la forma de aprendizaje de cada uno.
