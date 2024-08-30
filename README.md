# Instalación de Plugins en Neovim con vim-plug

Configuración de plugins en Neovim utilizando el gestor de plugins **vim-plug**. Sigue estos pasos para mejorar tu experiencia de edición en Neovim.

## 1. Instalar vim-plug

Para comenzar, necesitas instalar **vim-plug**, el gestor de plugins que utilizaremos. Ejecuta el siguiente comando en tu terminal para descargar e instalar `vim-plug` en la ubicación adecuada:

```bash
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \ https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

# Configurar vim-plug en Neovim

Una vez instalado vim-plug, debes configurarlo en tu archivo de configuración de Neovim. Abre o crea el archivo ~/.config/nvim/init.vim (para Vimscript) o ~/.config/nvim/init.lua (para Lua) y añade la configuración a continuación.
Para init.vim (Vimscript)

Añade el siguiente bloque de código a tu archivo init.vim:

```bash
" Inicializa vim-plug
call plug#begin('~/.local/share/nvim/plugged')

" Ejemplo de plugins
Configuración en el archivo anexo

" Finaliza la configuración de vim-plug
call plug#end()

````

# Instalar los Plugins

Después de configurar vim-plug, abre Neovim y ejecuta el siguiente comando para instalar los plugins que has añadido:
```bash
vim
:PlugInstall
```

Este comando descargará e instalará todos los plugins especificados en tu archivo de configuración.
