## Cómo deshacer commits

## Deshacer el último commit (manteniendo cambios)
```bash
git reset --soft HEAD~1
```
## Deshacer el último commit (eliminando cambios)
```bash
git reset --hard HEAD~1
```
## Modificar el último commit
```bash
git commit --amend -m "Nuevo mensaje"
```
## Revertir un commit ya publicado
```bash
git revert ID_del_commit
```
