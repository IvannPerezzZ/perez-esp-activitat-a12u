# Projecte: Markdown avançat i `.gitignore`

## Objectiu
> Practicar GitHub i Markdown avançat, i entendre el funcionament del fitxer `.gitignore`. Caldrà invitar a joanpardogine per poder veure l'activitat quan la pujeu.

## Crear el repositori
NO marcar "Add a README file".

Clicar Create repository.

Convidar al col·laborador joanpardogine al teu repositori remot.

## Clonar repositori al ordinador
> cd /c/projectes
git clone https://github.com/<el-teu-usuari>/portfoli-tecnic-markdown.git
cd portfoli-tecnic-markdown


## Enllaços útils
- [Guia Markdown](https://guides.github.com/features/mastering-markdown/)
- [`.gitignore` oficial](https://git-scm.com/docs/gitignore)

## Taula comparativa
taula = [
    ["Funcionalitat", "Disponible", "Notes"],
    [".gitignore", "✅", "Evita pujar fitxers innecessaris"],
    ["README.md", "✅", "Explica què fa el projecte"],
    ["Imatges", "✅", "Inserides via enllaç extern"],
    ["Quotes", "✅", "Per destacar idees importants"],
    ["Enllaços", "✅", "A recursos útils"],
    ["Taules", "✅", "Com aquesta"],
    ["Llistes definició", "✅", "Per explicar conceptes tècnics"]

## `.gitignore`
```bash
*.log
/classe/
config.tmp
