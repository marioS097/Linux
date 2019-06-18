# Teclado en español

## Solución rapida
> sudo setxkbmap -layout 'es,es' -model pc105

## Solución continua
- Modificar el fichero */etc/X11/xorg.conf*  
  ```
  Section “InputDevice”
  Identifier “Generic Keyboard”
  Driver “kbd”
  Option “CoreKeyboard”
  Option “XkbRules” “xorg”
  Option “XkbModel” “pc105”
  Option “XkbLayout” “es”
  Option “XkbOptions” “lv3:ralt_switch”
  EndSection
  ```
## Nota
- Usar el comando para que funcione correctamente la tecla Alt Gr que se encuentra a la derecha de la barra espaciadora
  > Option “XkbOptions” “lv3:ralt_switch”