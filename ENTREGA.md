# Evidencia

```
djimenez@mb ai4devs-openspec-sandbox-2026-06 % openspec --version
1.4.1
```

```
djimenez@mb ai4devs-openspec-sandbox-2026-06 % ls -R openspec/.
changes		config.yaml	specs

openspec/./changes:
archive

openspec/./changes/archive:

openspec/./specs:
```

# Plantilla

```# Micro-tarea: Validar una cuenta de email
# Pilar 1 — Herramienta: Claude code
 ¿Por qué esta y no otra?: Es la que sé usar.
# Pilar 2 — Contexto: 
¿Qué información estás aportando? (lenguaje, framework, restricciones, ejemplos…)
java, JDK 23
A standard email address follows the structure of username@domain.com. It consists of a local username, an "@" symbol, and a domain name. It must contain no spaces and be under 320 characters
 ¿Hay algo del contexto que has decidido omitir conscientemente?

# Pilar 3 — Prompt: ¿Cómo lo estructuras? (estilo, formato de salida, ejemplos…)

## CONTEXTO/ROLE
   "Eres un desarrollador que quiere validar el formato de una cuenta de correo"

## OBJETIVO/TAREA
   "Desarrollar una librería que permita validar cuentas de correo electrónico"

## CRITERIOS DE ÉXITO EXPLÍCITOS
   "Sabes que terminaste cuando:
    - Los test unitarios pasan en verde"

## RECURSOS/CONTEXTO
   "La librería java será un sólo jar, sin dependencias, que pueda ser utilizado por otros programas"

## Datos ejemplo

Casos a validar:
 * mail
 * mail.subname
 * mail.subname@
 * @
 * @mail
 * @mail.com
 * name@mail
 * name@mail.com.uy

## CLARIFICACIÓN
   "Si tienes dudas sobre el cambio, pregunta antes de implementar."
  
#Resultado: ¿Funcionó a la primera o tuviste que iterar?
 Una mejora que harías si volvieras a hacerlo.
```

# Observaciones

Veo que hay un fichero de configuración inicial: config.yaml (no me gustan los yaml...).
La carpeta "specs" tendrá ficheros para las especificaciones, imagino que serán features/bugs a llevar a cabo.
La carpeta "changes" imagino que se utilizará para gestionar el estado o acende del agente al ir desarrollado las specs.
