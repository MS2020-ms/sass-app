# Inicio
>npm i -g sass
Extensiones VSCode:
    Instalar -> sass
    Instalar -> Live Sass Compiler en VSC
        Settings / arriba drch: icono (abrir configuracion json)
                "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"],
                "liveSassCompile.settings.excludeList": [
                    "**/node_modules/**",
                     ".vscode/**"
                 ],
                 "liveSassCompile.settings.formats": [
                     {
                         "format": "expanded",
                         "extensionName": ".css",
                         "savePath": "/css"
                     }
                  ],

# Compilar sass
Clickar boton barra inferior Watch Sass = compilar
Ir a html y linckar archivo compilado <link rel="stylesheet" href="css/styles.css">

# Variales
# Nesting
# Parciales (_reset.scss) (_ = no son compilados)
Snippets en otro archivo y lo importo
# Mixin
No repetir codigo
# Extend
Similar a Mixin. Copiar el mismo estilo de otra clase
# Map
Ir a _variables.scss
# Function
# Operations
Operaciones matematicas
# Units

# Sass Meister
Tranformar syntax CSS -> SCSS -> SASS
https://www.sassmeister.com/