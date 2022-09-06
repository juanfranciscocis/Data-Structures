## QUE VAMOS A ESTUDIAR?
    Algoritmos -> metodos para resolver problemas
    
    Estructuras de Datos -> metodos para guardar informacion
    
## POR QUE ESTUDIAMOS?

    - Es la fundacion de ingenieria de software
    - Se encuentra en muchas areas
    - Aplicar lo que aprendamos es importante para escribir codigo eficiente
    
## SYLLABUS

    - aproano@asig.com.ec

## INTRO TO ALGORITHMS
    - Al-Khwarizmi fundador del algebra lineal
    
    - Es un procedimiento para resolver problemas matematicos.Paso por paso
    
    -> entrada -> algoritmo -> salida
    
### MODELO DE COMPUTACION
    
    - Se especifica las operaciones que podemos hacer
    
    - Cuanto cuesta hacer esta operacion en terminos de tiempo, memoria, etc...
    
    - Finalmente el estilo de programacion
    
    -> Dos tipos:
        - Random access machine
        - Pointer Machine
        
#### RANDOM ACESS MACHINE (RAM)
    
    - 1 Procesador
    
    - La Ram la modelamos como un arreglo gigante con numero de registros constante ejemplo : 100 registros
    
    - El modelo nos ayuda a compararlo con otros.

#### POINTER MACHINE
    - Similar a la programacion orientada a objetos.
    
    - Podemos alocar objetos dinamicamente (crearlos y destruilos cuando necesitamos)
    - Ejemplo:
            El -> [objeto con valor 3]-> apunta al -> [objeto con valor 8] -> este objeto apunta -> null. 
        --> Cada paso toma una unidad de tiempo 
    - Este modelo es mas debil que el modelo ram
       
#### PYTHON MODEL
    - Asumo que las listas de python son arreglos RAM
    
 
### RUNTIME (numero de veces que toma una operacion en darse)
    - Prediccion de cuanto timepo nos toma corre el programa en timepo de ejecucion
    - Nos permite comparar el rendimiento y optimizacion
    
    '''
    n = int(input('Ingrese un numero'))
    def sum(n):
    total = 0; #1 read
    for i in range(n+1): ;#1 read, 1 write
        total+=i ;# 2 reads, 1 write || 5 total
    return total
    '''
        

### USAMOS EL METODO CIENTIFICO
    - Observe: runtime o memoria
    - Hipotesis: con las observaciones planteamos una hipotesis. Por ejemplo: nuestro programa tiene un rutime de tipo funcion lineal o exponencial
    - Predict: Dar entradas muy grandes que una computadora no pueda calcular
    - Verificar
    - Validar Resultados: Ver si se verifica o no la hipotesis
    

##### COMO CAPTURAMOS EL RUNTIME

    '''
    def sum_time(n):
    start = 1000000*time.time()
    total = 0
    for i in range(1,n+1):
        total+=i
        return 1000000*time.time() -start
    print('Milisegundos',sum_time(10)) = 3.0!!!
    '''
    
##### MODELOS MATEMATICOS
    - El runtime total = suma del costo de todas las operaciones basicas del prpgrmaa multiplicado por su frecuencia




    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
