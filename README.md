#Example Base Project

##**Estructura del Proyecto**

```bash
Proyect
|_ src/ #Aqui van todos los archivos .c incluyendo el main.c
|_ include/ #Aqui van todos los archivos .h
|_ build/ #Aqui se generaran todos los .o y .exe
|_ config.yaml #Archivo de configuracion para Next
|_ next_w.exe #Ejecutable de Next Builder
|_ README #Archivo donde esta la descripcion del Proyecto
|_ .gitignore #Archivo para omitor el seguimiento de git en algunos archivos
```

##**Compilar Proyecto**

**Con [Next](https://next-b3d34.web.app/en/landing-page/)**
```bash
./next_w.exe build basic_release
#El ejecutable se guardara en ./build/basic_release
```

- Notas
    - No se requiere ningun otro programa solo con next_w.exe basta
