En los recursos de Organization, el atributo "qualification" queda pendiente de completar a falta de encontrar un estándar de certificación de hospitales.

Rec. Organization está pensado para modelar entidades, una entidad puede tener varias localizaciones
Rec. Location se refiere a una sede física 
HUVR es una organización que a su vez ha de tener un recurso location para referirse a su sede física
Por eso, en Location existe el atributo "position" que no existe en Organization

Las especialidades se modelan como Organizations pq son departamentos y se interpretan como entidades

A la hora de especificar el tipo de Location, encontramos una lista de posibilidades pero no hay ninguna que englobe nuestros requsitos.
poner ejemplos para especificar, un centro con varios departamentos, ...


Asisa: organization con muchas locations en distintas ciudades y varias locations dentro de una misma ciudad
