# Alacritty Configuration

This is my general configuration file for Alacritty for windows. 

### Instructions

1. To configure Alacritty you need to create the following file in this location:

```
~\AppData\Roaming\alacritty\alacritty.yml
```

2. Install the “Source Code Pro” font, you can download it from here: https://fonts.google.com/specimen/Source+Code+Pro 
3. Inside the ~\AppData\Roaming\alacritty folder, clone the repository: 

```
git clone https://github.com/eendroroy/alacritty-theme.git ~/.alacritty-colorscheme
```

5. Copy the contents of this repositoriy's alacritty.yml file to your local alacritty.yml file.

### Changing Theme

6. Inside alacritty.yml file, search for the line "import" and chage the theme used, for example:

```
import:
  - ~/.alacritty-colorscheme/themes/moonlight_ii_vscode.yaml
```

