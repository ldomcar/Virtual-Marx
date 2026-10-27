# Virtual-Marx

En este proyecto se intenta demostrar como el ajusto adecuado de los consecuentes archivos de configuración/contexto, pueden derivar en grandes diferencias a la hora de razonar problemas, y las conversaciones rutinarias con un modelo. 

En este caso, hemos usado Qwen 3.5-9B MTP con cuantización Q4_K_M, este es un modelo pequeño altamente capaz y que puede ser ejecutado localmente sin necesidad de hardware excesivamente costoso. Hemos añadido instrucciones sobre el método de razonamiento a seguir para determinados problemas (políticos, económicos, sociales, etc) y el papel que el modelo debe adoptar, consiguiendo una inmersión en el personaje excepcional. También se incluyen archivos con contexto histórico, económico, político, y información precisa sobre las teorías y pensamientos de Marx.  

Hemos observado un incremento de precisión en las respuestas a preguntas de carácter filosófico y abstracto, sin presentar un retraso excesivamente notable. El modelo responde bajo el nombre de Marx y a la hora de formular la respuesta, recorrerá la base de datos (en función de lo que sea necesario) para, con la información adjuntado sobre Marx, elaborar una respuesta que intenta plagiar una dada por el personaje replicado.

No sigue un protocolo rígido e inmutable, el modelo puede ajustar las instrucciones en función de lo que considere necesario, obteniéndose asi una respuesta mucho mas ajustada al usuario.

En conclusión, el modelo entiendo y plagia con sorprendente exactitud su roll, consigue responder preguntas de carácter abstracto, político, económico, filosófico, etc; dejando de lado las respuestas generales, llegando a unas conclusiones mas profundas y verdaderas (según el punto de vista del Marx). 

En los archivos MEMORY.md y USER.md se establece un limite aproximado de 40 palabras por respuesta, esta establecido para primar la naturaleza y fluidez de de las conversaciones en modo voz. Si se quiere se puede abolir, quedando un modelo plenamente funcional y con respuestas más profundas (aunque mas densas) que el original.
