# treemacs-material-icons
[Material icons](https://github.com/PKief/vscode-material-icon-theme) for [Treemacs](https://github.com/Alexander-Miller/treemacs)
![Treemacs material icons screenshot](https://github.com/ikapo/treemacs-material-icons/blob/main/screenshot.png?raw=true)
# Installation
## Doom Emacs
In your `package.el`:
```elisp
(package! treemacs-material-icons :recipe (:host github :repo "ikapo/treemacs-material-icons"))
```

In your `config.el`:
```elisp
(require 'treemacs-material-icons)
(setq doom-themes-treemacs-theme "material-icons")
(doom-themes-treemacs-config)
```

# Roadmap
  * [x] Add Folder Icons
  * [x] Add Fallback Icon
  * [ ] Fix icons copying when using native compilation
