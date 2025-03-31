# 1. Crear el diccionario "informacion_personal" con información ficticia
informacion_personal = {
    "nombre": "Geovanni Correa",
    "edad": 40,
    "ciudad": "Zapotillo",
    "profesion": "Estudiante"
}

# 2. Acceder y modificar valores
# Modificar la ciudad
informacion_personal["ciudad"] = "Gualaquiza"

# Agregar una nueva clave-valor para la profesión (si no existe ya)
informacion_personal["profesion"] = "Desarrollador de Software"

# 3. Verificar si la clave "telefono" existe
if "telefono" not in informacion_personal:
    # Si no existe, agregar la clave "telefono" con un número ficticio
    informacion_personal["telefono"] = "+593 993 437 3027"

# 4. Eliminar la clave "edad"
if "edad" in informacion_personal:
    del informacion_personal["edad"]

# 5. Imprimir el diccionario final
print(informacion_personal)
