# game-mods

Repositório organizacional para **mods de jogos**, separados por jogo e propósito.

Cada mod possui seu próprio repositório, mantendo histórico, versões e documentação independentes.

---

## Objetivo

- Organizar mods por jogo
- Manter cada mod versionado separadamente
- Facilitar manutenção e publicação
- Servir como vitrine técnica de modding

---

## Estrutura

```
game-mods/
 ├─ project-zomboid/
 └─ hattrick/
```

---

## Project Zomboid

Mods desenvolvidos para Project Zomboid.

```
project-zomboid/
 ├─ weapons
 ├─ translation-ptbr
 └─ more-pictures
```
---

## Hattrick

Ferramentas auxiliares para Hattrick.

```
hattrick/stats-track
 └─ stats-track
```

Cada pasta representa um **submodule** apontando para o repositório do mod.

---

## Submodules

Para clonar corretamente:

```bash
git clone --recurse-submodules https://github.com/siddigo/game-mods
```

Ou após clonar:

```bash
git submodule update --init --recursive
```

---

## Observação

Este repositório **não contém código direto**.  
Ele apenas organiza e referencia mods mantidos em repositórios próprios.

---

## Autor

Sidnei Rodrigo dos Santos
