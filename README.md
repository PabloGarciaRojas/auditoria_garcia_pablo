## REFACTORIZACION TechNova Cloud v2.0

**¿Cuántas líneas de código habéis ahorrado al usar grupos?**
Como hemos usado attributeGroup y group, he podido hacer que el xsd sea mucho mas corto ya que habia muchas líneas repetidas.
Tambien he podido hacer que si por ejemplo tuviese que añadir un campo a un servidor solo tenga que cambiar una linea del grupo y no una linea por cada servidor.

**¿Qué error os da VS Code si intentáis poner dos servidores con el mismo ID?**
Si pongo el mismo ID en dos servidor, daria error y se marcaría en rojo.
También sale el siguiente error, el cual dice que ha saltado la regla de unicidad y que no puede haber dos servidores con el mismo id:
Identity Constraint error: the identity-constraint 'UnicoID' failed..."
