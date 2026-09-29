# Configuración de GitHub y Guía de Markdown

## Proyecto de Prueba 2ASIR

Este documento sirva como guía y **demostración de uso** del lenguaje de marcas *Markdown*, ideal para documentar código de forma `limpia` y estructurada dentro de un repositorio de Git.

```bash
# Comandos para clonar y subir cambios por SSH
git clone git@github.com:usuario/prueba_tu_nombre.git
cd prueba_tu_nombre
git status
git add .
git commit -m "Añadida documentación en README.md"
git push origin main
```

### Pasos para Configurar Claves SSH (Lista Ordenada)

1. Generar la clave SSH localmente con el comando `ssh-keygen -t rsa -b 4096`.
2. Copiar el contenido del archivo de la clave pública `cat ~/.ssh/id_rsa.pub`.
3. Pegar la clave pública dentro de la sección **SSH keys** de la configuración de perfil en GitHub.

### Requisitos del Proyecto (Lista Desordenada)

* Sistema operativo Linux / UNIX
* Git instalado y configurado
* Editor de texto `nano` o `VS Code`
* Cuenta activa en GitHub

### Enlaces Útiles

* **Enlace Externo:** Consulta la [Guía de Sintaxis de GitHub](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
* **Enlace Interno:** Revisa nuestro archivo secundario de [Documentación Técnica del Repositorio](./DOCUMENTACION.md).

### Imagen Informativa

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Cheat Sheet / Referencia Rápida de Markdown

| Elemento | Sintaxis Markdown | Resultado / Descripción |
| :--- | :--- | :--- |
| **Título Principal** | `# Título` | Encabezado de nivel 1 (H1) |
| **Subtítulo** | `## Subtítulo` | Encabezado de nivel 2 (H2) |
| **Negrita** | `**Texto**` | Texto resaltado en **negrita** |
| **Cursiva** | `*Texto*` | Texto en *cursiva* |
| **Código en línea** | `` `código` `` | Formato de `código` |
| **Cita** | `> Texto` | Bloque de texto citado |
| **Enlace** | `[Texto](URL)` | Crea un hipervínculo |
| **Imagen** | `![Alt](URL_Imagen)` | Muestra una imagen incrustada |
