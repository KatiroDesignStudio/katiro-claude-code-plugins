# Katiro Studio : plugins Claude Code

Le catalogue des plugins [Claude Code](https://claude.com/claude-code) de [Katiro Studio](https://katiro.studio).

## Ajouter le catalogue
Une seule fois :
```bash
claude plugin marketplace add KatiroDesignStudio/katiro-claude-code-plugins
```

## Les plugins
| Plugin | Ce qu'il fait | Installer |
|---|---|---|
| [Katiro UI Kit](https://github.com/KatiroDesignStudio/katiro-ui-kit-figma) | Remet au propre le UI Kit d'un fichier Figma, directement dans Figma | `claude plugin install katiro-ui-kit@katiro-studio` |
| Katiro DS (privé) | Design system IA Ready, de Figma à Mihon. Réservé aux membres de l'organisation KatiroDesignStudio sur GitHub | `claude plugin install katiro-ds@katiro-studio` |

Puis ouvre une nouvelle session Claude Code.

## Mettre à jour
Rafraîchis le catalogue, puis mets à jour chaque plugin installé, et ouvre une nouvelle session :
```bash
claude plugin marketplace update katiro-studio
```
```bash
claude plugin update katiro-ui-kit@katiro-studio
```
```bash
claude plugin update katiro-ds@katiro-studio
```

## Licence
MIT. Fait par [Katiro Studio](https://katiro.studio).
