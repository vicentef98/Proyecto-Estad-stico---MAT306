# Instrucciones de uso

El objetivo de este portafolio es que el estudiante aprenda a utilizar `Github` y posea material demostrable de las habilidades aprendidas en el curso. Las instrucciones se dividen en la configuración del repositorio personal, configuración del repositorio del curso y en un flujo típico a lo largo del semestre.

> **Nota:** La información generada en el proyecto de laboratorio de modelación
> (códigos, datos, informes) es **CONFIDENCIAL**. Por lo tanto, **NO** debe ser
> compartida con personas que no estén directamente involucradas en el proyecto.

## Configuración inicial para el curso

1. Crear cuenta de GitHub [aquí](https://github.com/join).
2. Instalar [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
    - En Windows lo ideal sería instalar _Git for Windows_.
    - También existe una alternativa con interfaz gráfica, [GitHub Desktop](https://desktop.github.com/) pero no es recomendable, pues uno de los objetivos del curso es aprender los fundamentos de Git.
3. Configurar tu forma de acceder a GitHub. [Recomendaciones.](https://help.github.com/en/articles/which-remote-url-should-i-use)
    - Recomendado pero menos seguro: HTTPS
        * Te podría ser útil configurar [_credential helper_ ](https://help.github.com/en/articles/caching-your-github-password-in-git) para recordar tu usuario en tu computador.
    - Más engorroso pero más seguro: SSH
        * Sigue [estas instrucciones](https://help.github.com/en/articles/connecting-to-github-with-ssh).
4. Ir al repositorio [MAT283-Portfolio](https://github.com/fralfaro/MAT283-Portfolio) y presionar el botón *__Use this template__* <img src="../images/template.png" width=80>.
5. Nombar el nuevo repositorio como __MAT283_portfolio__ y dejarlo en modo **privado**.
7. Se recomienda crear un directorio en el computador personal para repositorios de Git. Por ejemplo en `~/Documents/git/`.
6. Clonar el repositorio recién creado. Dependiendo de tu configuración de Git, reemplazar `{username}` por el nombre de usuario personal de GitHub uno de los siguientes comandos en la terminal (usuarios de Windows probablemente tengan que utilizar _Git Shell_.)
    - HTTPS: `git clone https://github.com/{GITHUB_USER}/MAT283_portfolio.git`
    - SSH: `git clone git@github.com:{GITHUB_USER}/MAT283_portfolio.git`
7. En el archivo `README.md` editar los campos personales:
    - Nombre y si se desea algún link a perfil profesional, por ejemplo Linkedin o GitHub.


## Estrucutura de Carpetas:

```
├───docs
│   ├─── codes
│   │     └── README.md
│   ├─── reports
│   │     └── README.md
│   └─── setup.md
└─── images
      ├─── dmat.png
      ├─── template.png
      └──  utfsm.png
├─── .gitignore
├─── LICENSE
└──  README.md
```

- **docs**: Carpeta que contiene documentación relacionada con el proyecto.
  - **setup.md**: Archivo markdown que describe cómo configurar el proyecto.
  - **codes**: Carpeta que contiene los códigos o scripts relacionados con el proyecto.
  - **reports**: Carpeta que contiene informes relacionados con el proyecto.
- **images**: Carpeta que  contiene imágenes relacionadas con el proyecto.


- **.gitignore**: Archivo que contiene patrones de archivos que se deben ignorar.
- **LICENSE**: Archivo que contiene información sobre la licencia de uso del proyecto.
- **README.md**: Archivo markdown que contiene información general sobre el proyecto.
