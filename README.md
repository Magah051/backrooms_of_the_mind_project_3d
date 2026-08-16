# Backrooms of the Mind (3D)

*Protótipo 3D inspirado na estética **Backrooms**, desenvolvido com a engine **Unity**. O projeto inicia com a cena `TheGame` como base para um ambiente liminal em primeira ou terceira pessoa. Conceitos presentes / a expandir:*

- Projeto Unity 3D (template + cena própria)
- Cena principal `TheGame.unity`
- Estrutura padrão para level design 3D
- Base para exploração, iluminação e áudio atmosférico

---

## Sobre o projeto

**Backrooms of the Mind** é um protótipo de horror/exploração espacial liminal. A ideia é construir corredores monótonos, iluminação estranha e uma sensação de desorientação — como se a mente estivesse presa em um loop de salas amarelas sem fim.

O repositório está no estágio inicial: cena criada, pronta para receber level design, player controller e áudio.

## Tecnologias

| Item | Detalhe |
|------|---------|
| Engine | Unity **2023.1.15f1** |
| Linguagem | C# (quando scripts forem adicionados) |
| Tipo | Protótipo 3D / horror atmosférico |

## Estrutura atual

```
backrooms_of_the_mind_project_3d/
├── Assets/
│   └── Scenes/
│       └── TheGame.unity     # Cena principal do protótipo
├── Packages/
├── ProjectSettings/
├── .gitignore
└── .vsconfig
```

## Como abrir no Unity

1. Instale o **Unity Hub** e a versão **2023.1.15f1** (ou compatível 2023.1.x).
2. Clone o repositório:
   ```bash
   git clone https://github.com/Magah051/backrooms_of_the_mind_project_3d.git
   ```
3. Abra o projeto no Unity Hub.
4. Abra `Assets/Scenes/TheGame.unity`.
5. Pressione **Play** e comece a construir o ambiente.

## Direção criativa (sugestão)

- Corredores repetitivos com pouca variação visual
- Luz fluorescentes / zumbido ambiente
- Fog leve e paleta dessaturada/amarelada
- Sons distantes, eco e footsteps
- Objetivo opcional: encontrar a saída / “acordar”

## Próximos passos sugeridos

- [ ] Controller FPS (movimento + mouse look)
- [ ] Modular corridors (prefabs de sala)
- [ ] Lighting + Post Processing
- [ ] Ambient audio / footsteps
- [ ] Trigger de game over / “noclip” moment

## Status

**Protótipo / WIP** — cena base criada; gameplay e level design ainda em construção.
