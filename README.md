# Instalación de Plugins en Neovim con vim-plug

Configuración de plugins en Neovim utilizando el gestor de plugins **vim-plug**. Sigue estos pasos para mejorar tu experiencia de edición en Neovim.

## 1. Instalar vim-plug

Para comenzar, necesitas instalar **vim-plug**, el gestor de plugins que utilizaremos. Ejecuta el siguiente comando en tu terminal para descargar e instalar `vim-plug` en la ubicación adecuada:

```bash
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim


# Configurar vim-plug en Neovim

Una vez instalado vim-plug, debes configurarlo en tu archivo de configuración de Neovim. Abre o crea el archivo ~/.config/nvim/init.vim (para Vimscript) o ~/.config/nvim/init.lua (para Lua) y añade la configuración a continuación.
Para init.vim (Vimscript)

Añade el siguiente bloque de código a tu archivo init.vim:
