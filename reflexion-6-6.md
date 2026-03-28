1\.

git cherry-pick elige un solo cambio específico de una rama y copia en la mia.



merge: Junta dos ramas enteras. Crea un "commit de unión" que conecta ambas historias para siempre.

rebase: Corta tu rama actual y la pega al final de otra. Reescribe la historia para que parezca que siempre trabajaste sobre la versión más nueva.



2\.

Hotfix en producción: estás trabajando en una rama feature-nueva con cientos de cambios que aún no están listos. De repente, encuentras un error crítico en el código existente y lo arreglas con un commit en esa misma rama.

Commit en la rama equivocada: empiezas a programar, haces un commit brillante y luego te das cuenta de que seguías en la rama main en lugar de tu rama de desarrollo.

Reutilizar un pequeño cambio en varias ramas: Tu equipo mantiene dos versiones de un producto: la v2.0 (antigua) y la v3.0 (actual). Desarrollas una mejora pequeña o un parche de seguridad en la v3.0.



3\.

Aunque es una herramienta potente, se recomienda usar git cherry-pick con moderación porque rompe la trazabilidad y ensucia el historial del proyecto.

