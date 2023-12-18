## Projet d'autogénération de CV basé sur un fichier markdown.
Basé sur le projet [there4/markdown-resume](https://github.com/there4/markdown-resume) (que je remercie, super pratique !)
Automatisé avec Github Actions afin de générer le html et les pdf, puis déployer sur Github Pages.

Run local
```bash
docker run -v ${PWD}:/resume there4/markdown-resume:2.3.1 md2resume pdf --ansi --template swissen cv.md .
docker run -v ${PWD}:/resume there4/markdown-resume:2.3.1 md2resume pdf --ansi --template swissen cv_full.md .
docker run -v ${PWD}:/resume there4/markdown-resume:2.3.1 md2resume html --ansi --template swissen cv_full.md .
```