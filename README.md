# Kino – mini-editor de texto em C

Kino é um simples editor de texto em C, baseado no [kilo](https://github.com/antirez/kilo) de Salvatore Sanfilippo; tem menos de 1 000 linhas de C puro, sem dependências externas.

## Compilação
```bash
make          # gera o binário `kino`
sudo make install  # opcional – instala em /usr/local/bin
````

## Uso rápido

| Atalho      | Ação                 |
| ----------- | -------------------- |
| `Ctrl-S`    | Salvar arquivo       |
| `Ctrl-Q`    | Sair                 |
| `Ctrl-F`    | Buscar texto         |
| `Ctrl-Z`    | Undo (última edição) |
| `PgUp/PgDn` | Rolagem por página   |


## Créditos e licenças

Este projeto começou a partir do tutorial **“Build Your Own Text Editor”** ([https://viewsourcecode.org/snaptoken/kilo/](https://viewsourcecode.org/snaptoken/kilo/)) e do repositório original **kilo** de Salvatore Sanfilippo (antirez)
