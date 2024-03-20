# Common resources for scientific writing
This repository centralizes files that are common to multiple papers I write, e.g. acronyms, commands, packages, configuration, and so forth.

## Example usage

In a project in [Overleaf](https://www.overleaf.com/project), click 'New File', in the dialog select the `From External URL'. 
Then pick the file you wish to include (in raw format), e.g. for [setup.tex](https://github.com/bencardoen/resources/blob/main/setup.tex) this becomes
```bash
https://raw.githubusercontent.com/bencardoen/resources/main/setup.tex
```
The file is now available in your project, and you can use it, synchronize it, and so on.
You can also change the branch so changes do not clash.
![example](example.png)

## Files

- setup.tex: common packages and their configuration options. Includes Abbreviations.tex
- Abbreviations.tex: Acronyms (with citation) for use in acro v2.8+. Citations depend on `references.bib`
- references.bib: Common bibliography, exported from Zotero
