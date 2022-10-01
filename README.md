# Alacritty Configuration

This is my general configuration file for Alacritty (for Windows). 

### Instructions

1. To configure Alacritty you need to create the following file in this location:

```
~\AppData\Roaming\alacritty\alacritty.yml
```

2. To install the “Source Code Pro” font, you can download it here: https://fonts.google.com/specimen/Source+Code+Pro 
3. Inside the *~\AppData\Roaming\alacritty* folder, clone the repository: 

```
git clone https://github.com/eendroroy/alacritty-theme.git ~/.alacritty-colorscheme
```

5. Copy the contents of this repositoriy's *alacritty.yml* file to your local *alacritty.yml* file.

### Changing Theme

6. Inside the *alacritty.yml* file, search for the line "import" and chage the theme used; for example, the following line will use the *darcula* theme:

```
import:
  - ~/.alacritty-colorscheme/themes/darcula.yaml
```

