# Focus Curve V2

Aplicativo estático para acompanhar sessões de estudo e estimar uma curva pessoal de foco.

## Novidades da V2

- Curva adaptativa do bloco
- Melhor horário do dia
- Sono, fome e distrações
- Comparações simples entre contexto e foco
- Tema claro/escuro
- CSV e backup JSON
- Sem backend e sem dependências externas

## Rodar localmente

Abra `index.html` ou use:

```bash
python -m http.server 8000
```

## GitHub Pages

1. Crie um repositório.
2. Envie estes arquivos para a branch `main`.
3. Vá em `Settings > Pages`.
4. Escolha `Deploy from a branch`.
5. Selecione `main` e `/ (root)`.

## Estrutura

```text
focus-curve-v2-github-ready/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    ├── css/styles.css
    └── js/app.js
```

## Privacidade

Os dados ficam no `localStorage` do navegador.

## Limitações

A curva é uma estimativa baseada nos registros do usuário e não substitui avaliação médica ou neuropsicológica.

## Licença

MIT
