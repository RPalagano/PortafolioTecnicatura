# PortafolioTecnicatura
Landing de portafolio personal para una práctica formativa obligatoria (PFO1) de la materia Desarrollo de Sistemas Web (Front End).

El trabajo se realizó principalmente a partir de los conocimientos previos, el contenido proporcionado por la materia y búsquedas o investigaciones autodidactas mediante YouTube.

Además, se utilizó inteligencia artificial (ChatGPT/Gemini) como herramienta para resolver inconvenientes específicos durante el desarrollo. Por ejemplo, inicialmente se utilizó position: fixed en el header para mantenerlo visible al hacer scroll, pero esta implementación generaba inconvenientes en el posicionamiento y la distribución de los elementos de la página. Ante esta dificultad, se consultó a la inteligencia artificial sobre posibles alternativas y se optó finalmente por utilizar position: sticky, que permitió obtener el resultado deseado.

Otra situación en la que se presentó un inconveniente fue al intentar agregar scroll-margin-top únicamente a un <article> específico. Se conocía que podía utilizarse el selector article[id], pero este afectaba a todos los <article> que tuvieran un id. Por este motivo, se consultó a la inteligencia artificial sobre una alternativa que permitiera seleccionar específicamente el id al que se deseaba aplicar dicha propiedad (article[id="proyectos"]).