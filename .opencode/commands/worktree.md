---
description: Crea un worktree local con nombre en kebab-case
---

Usa el siguiente texto únicamente como nombre del worktree: $ARGUMENTS

Convierte el nombre a kebab-case ASCII: minúsculas, sin tildes, espacios y separadores convertidos en guiones, sin guiones repetidos ni en los extremos. El resultado solo puede contener letras a-z, números y guiones. Si queda vacío, solicita un nombre y no ejecutes nada.

Ejecuta únicamente `git worktree add .worktrees/<nombre>`, sustituyendo `<nombre>` por el nombre normalizado. No ejecutes otros comandos, no cambies de directorio ni muevas la sesión. No crees commits, no hagas comprobaciones adicionales y no reintentes si falla. Muestra solo el resultado de la creación.
