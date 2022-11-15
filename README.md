# DotFiles

## .gitconfig (Windows)
```powershell

```
## .vscode (Windows)
```powershell
# Lista os itens existentes no diretório
ls "C:\Users\brunotassis\AppData\Roaming\Code\User"
# Ronomeia o arquivo origianal como backup
Rename-Item "C:\Users\brunotassis\AppData\Roaming\Code\User\settings.json" -NewName "settings.json.original"
# Cria o link simbolico para o dotfiles
New-Item -ItemType SymbolicLink -Path "C:\Users\brunotassis\AppData\Roaming\Code\User\settings.json" -Target "C:\Users\brunotassis\.dotfiles\.vscode\user\settings.json"
```