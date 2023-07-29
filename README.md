
 <h1>✔ Dia 1 (IA)</h1>
 
<h3>🕸Inteligencia Artificial</h3>

La inteligencia artificial es un campo de la maquina informática, el cual busca desarrollar máquinas que sean capaces de aprender, razonar y tomar decisiones como lo hacen nosotros los humanos. La IA se aplica mas que todo en las áreas de aprendizajes como se menciono, pero este, esta mas enfocado en que sea autónomo, que tenga la capacidad de procesar tanto el lenguaje natural visión y robótica pero también involucrando lo que son desafíos que están planteando tanto de manera ética como tema sociable.

<img src=https://blogibsamericas.com/wp-content/uploads/2023/04/Img-IA-1920-x-1080-2-1920x960.jpg alt="Descripción de la imagen" width="380" height="300">


<h3>🕸Machine Learning</h3>
Es una parte de la inteligencia artificial que busca enseñar a las máquinas cómo aprender de datos y mejorar su rendimiento en tareas sin la necesidad que sea una programación que sea explícita. Se recopilan datos, que entrenan el modelo que tiene toma de decisiones sobre datos nuevos que se esta implementando. Tiene múltiples funciones las cuales están relacionadas con las aplicaciones, con el fin de que este pueda mejorar la precisión y eficiencia en diversas tareas. 

<img src=https://nodd3r.com/media/blog/Portadas_blog_24.png alt="Descripción de la imagen" width="380" height="300">

<h3>🕸Chatgpt</h3>
Es un  modelo de lenguaje el cual esta desarrollado por OpenAI que puede mantener conversaciones coherentes con los usuarios. Esta basado en enormes cantidades de datos de texto que tiene relación con el texto que puede ampliarse a la del ser humano, utilizando para que sea lo mas optimo para la asistencia virtual y involucrando otras aplicaciones basadas en texto.

<img src=https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/ChatGPT_logo.svg/1200px-ChatGPT_logo.svg.png alt="Descripción de la imagen" width="280" height="200">

<h3>🕸Alpha Go</h3>
Es una app el cual esta desarrollado por parte de DeepMindo(Google) para poder jugar un juego desarrollado por la mano de la empresa el cual se llama Go. Go utiliza una aprendizaje profundo y por refuerzo para aprender y para sorpresa de los demás este pudo ganar al campeón mundial Go en 2016, mostrando avances significativos en inteligencia artificial.

<img src=https://i.ytimg.com/vi/WXuK6gekU1Y/sddefault.jpg alt="Descripción de la imagen" width="380" height="300">
<h3>🕸Ética y Sesgo</h3>
La ética en la inteligencia artificial se refiere a garantizar que su desarrollo y uso sean responsables y respetuosos con los valores humanos y derechos. El sesgo en la inteligencia artificial es la tendencia de los algoritmos a favorecer ciertos grupos o tomar decisiones desiguales basadas en datos sesgados. Ambos aspectos son importantes para garantizar un uso ético y justo de la inteligencia artificial.

<h1>✔Dia dos</h1>
<img src=https://logos-world.net/wp-content/uploads/2021/10/Python-Logo.png alt="Descripción de la imagen" width="380" height="200">
<h3>🕸Python</h3>
Python es un lenguaje de programación de alto nivel, con el propósito general y fácil de aprender. Es conocido por su sintaxis sencilla y legible, lo que lo hace ideal para principiantes y programadores experimentados. Python es ampliamente utilizando en diversas áreas debido a sus ventajas:

1. Versatilidad: Python es adecuado para una amplia variedad de tareas, desde desarrollo web y análisis de datos hasta inteligencia artificial y automatización.
    
2. Fácil de aprender: Su sintaxis clara y concisa facilita el proceso de aprendizaje, permitiendo a los programadores escribir código de manera más rápida y eficiente.
    
3. Amplia comunidad y bibliotecas: Python cuenta con una comunidad activa que ha creado una gran cantidad de bibliotecas y módulos que facilitan el desarrollo y aceleran el proceso de programación.
    
4. Multiplataforma: Python es compatible con varias plataformas, lo que significa que el código escrito en Python puede ejecutarse en diferentes sistemas operativos.

Los usos son poco peculiares pero a la vez estan presentes en varios aplicaciones o paginas webs y como plus en los videojuegos pero siempre en formato backend:

1. Desarrollo web: Python se utiliza para construir aplicaciones web a través de marcos populares como Django y Flask.
    
2. Ciencia de datos y análisis: Python es ampliamente utilizado en el análisis de datos y la ciencia de datos gracias a bibliotecas como NumPy, Pandas y Matplotlib.
    
3. Inteligencia artificial y aprendizaje automático: Bibliotecas como TensorFlow y PyTorch han hecho de Python una opción popular para proyectos de IA y aprendizaje automático.
    
4. Automatización y scripting: Python es excelente para tareas de automatización y scripting, ya que permite realizar operaciones repetitivas con facilidad.
    
5. Desarrollo de juegos: Python también se ha utilizado para desarrollar juegos, especialmente con bibliotecas como Pygame.

Pues bien, durante nuestro aprendizaje de Python, hemos realizado una serie de ejercicios que nos han permitido mejorar y comprender mejor este lenguaje de programación. Para llevar a cabo estas actividades, utilizamos la plataforma de Google llamada Colab, la cual nos facilitó la creación y ejecución de código en Python. Es importante destacar que esta plataforma nos permitía trabajar exclusivamente con Python, tal como fue requerido por el docente encargado de impartir el curso."
Bueno el nos asigno crear un código el cual se relacionara con el juego de la lotería el cual consistía de los siguientes puntos:

1. Si el animal ingresado coincide con el animal que se planteo previamente, este resultara el ganador definitivamente.
2. También se puso un juego de números el cual si este coincide 3 veces automáticamente será el ganador.
3. Si estos ya mencionados no coinciden , en teoría debería perder y algo mas que mencionar se nos pidió que sea algo interactivo para el usuario ya que lo que se maneja ya es un apartado de software.
 Aqui las evidencias de lo que realizo:

🐍 Primer punto

    def obtener_mensaje(signo):
            mensajes = {

        'aries': 'Hoy es un buen día para tomar decisiones importantes.',

        'tauro': 'La perseverancia te llevará al éxito en tus proyectos.',

        'geminis': 'Es momento de comunicar tus sentimientos a alguien cercano.',

        'leo': '¡Felicidades! Ganaste la lotería.',

    }

    if signo in mensajes:

        return mensajes[signo]

    else:

        return 'No se a ingresado el signo correspondiente porfavor intentalo de nuevo'
       
       signos_zodiacales = ['aries', 'tauro', 'geminis', 'leo']
       
       usuario = input("Ingresa tu signo zodiacal: ")
      
	   mensaje = obtener_mensaje(usuario)
       
       print(mensaje)

Resultado de uno:
Ingresa tu signo zodiacal: geminis 
Es momento de comunicar tus sentimientos a alguien cercano.

🐍Segundo punto

    import random

        def jugar_loteria():
    
             animales = ['gato', 'perro', 'caballo']

             numeros = ['1', '2', '3']

             animal_ganador = random.choice(animales)

             numero_ganador = [animal_ganador] * 3

      print("Bienvenido/a a la lotería de animalitos y números!")

    print("Los animalitos posibles son: gato, perro, caballo")

        print("Los números posibles son: 1, 2, 3")

    intentos = 0  

    while True:

        animal_intento = input("Ingresa el nombre de un animalito: ").lower()

        numero_intento = input("Ingresa un número del 1 al 3: ")

        if animal_intento == animal_ganador and numero_intento == ''.join(numero_ganador):

            print(f"Felicidades, has ganado! El animalito y número ganadores son: {animal_ganador}, {numero_ganador[0]}")

            break

        elif intentos == 2:

            print(f"Has agotado tus intentos. El animalito y número ganadores eran: {animal_ganador}, {numero_ganador[0]}")

            break

        else:

            print("No has ganado. Sigue intentando.")

            intentos += 1
            
            jugar_loteria()

Resultado final:
Bienvenido/a a la lotería de animalitos y números!
Los animalitos posibles son: gato, perro, caballo 
Los números posibles son: 1, 2, 3 
No has ganado. Sigue intentando.

<h1>✔Día tres </h1>

<h2>🕸Phyton y WebCam</h2>
Como ya se vino viendo la vez anterior, Python es un lenguaje de programación versátil, fácil de aprender y ampliamente utilizado en diversos campos, como desarrollo web, análisis de datos, inteligencia artificial y automatización. Su sintaxis legible y su gran comunidad lo hacen una opción popular para una amplia gama de proyectos.

El día de hoy realizamos una pequeña practica la cual da énfasis a un mini juego con relación al titanic, los errores que estuvieron presentes a lo largo del código, fueron de un total de 4 errores los cuales se nos indico corregirlo para que pudiera funcionar de manera optima, claro aclarando que debía de funcionar de manera remota para que con ello  pueda funcionar de lo contrario nos lanzaba un error de mal funcionamiento.

Para aclarar se utilizo, la aplicación Anaconda la cual proporciona varias herramientas para lenguaje de programación, en este caso nos estaremos enfocando en Jupyter el cual nos permitirá visualizar el código que nosotros vayamos a corregir.

Aquí la evidencia de lo que se realizo:


  ![[Imagen1.png]]

![[Imagen2.png]]

![[Imagen3.png]]

![[Imagen4.png]]

![[Imagen5.png]]

![[Imagen6.png]]

<h2>🕸Teachable Machine</h2>
<img src=https://d3uyj2gj5wa63n.cloudfront.net/wp-content/uploads/2021/07/teachable_machine_logo.png alt="Descripción de la imagen" width="380" height="100">
Ahora nos enfocaremos en un tema bastante interesante la cual va con relación a controlar con gestos un juego bastante conocida por la comunidad la cual se llama Snake.
Lo que se pretende hacer en esta plataforma es realizar grabaciones las cuales nos permitan poner un movimiento en especifico para controlar el objeto un ejemplo seria que si pongo el puño el muñeco debe girar hacia la derecha y así con las demás mímicas por así decirlo, punto que mencionar para que esto funcione de manera correcta se debe tener una webcam el cual captara los movimientos y estos movimientos creados previamente, se tendrán que colocar en una línea código, ósea solo el enlace del proyecto que ya se guardo para ya por fin jugar con nuestras mímicas en el mini juego.

Evidencias:

![[Imagen7.png]]

![[Imagen8.png]]
![[Imagen9.png]]

<h1>✔Día cuatro</h1>
<h2>🕸Consumir una API y Postman</h2>
El día de hoy realizamos una pequeña practica la cual trata sobre como una API consume, esto con relación a la CRUD y con ello ver los mensajes que se mandan mediante a una aplicación postman el cual nos mostrara los datos que nosotros guardamos posteriormente en el documento que se creo previamente.

Aquí las evidencia:



![[Imagen11.png]]

![[Imagen12.png]]

![[Imagen13.png]]

![[Imagen14.png]]

<h2>Aplicación de Api con ChatGPT</h2>
El objetivo de aquí es de era simplemente consumir una API en conjunto de ChatGPT, incluyendo una key el cual nos permitirá hacer en nuestra pagina por así decirlo, y desde ahí realizar varias preguntas las cuales nos servirían para ver si todo marchaba a la perfección, un detalle a decir es mientras mas preguntas se le hace se estará consumiendo una cuota  el cual si llega a su limite pues automáticamente dejara de dar respuestas y posteriormente nos lanzara un error.

Aquí las evidencias de lo que se realizo:

![[Imagen10.png]]

![[Imagen15.png]]
