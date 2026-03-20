<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Engenharia%20de%20Computação%20UNIFEV&fontSize=32&fontColor=58a6ff&fontAlignY=38&desc=Landing%20Page%20Institucional%20&descAlignY=58&descSize=16&descColor=8b949e" />

![Preview da Landing Page](components/image/index.jpg)

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-engenhariadecomputacao.vercel.app-58a6ff?style=for-the-badge&logo=vercel&logoColor=white)](https://engenhariadecomputacao.vercel.app)
[![GitHub repo](https://img.shields.io/badge/Repositório-vhtasca%2FLPEC-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vhtasca/LPEC)
![Status](https://img.shields.io/badge/status-live-brightgreen?style=for-the-badge)

</div>

## Sobre o Projeto

Este projeto nasceu de uma iniciativa dos próprios alunos do curso junto com o coordenador, desenvolvida de forma independente **fora da grade curricular**, com o objetivo de criar uma presença digital moderna e acessível para o curso de Engenharia de Computação da UNIFEV.

A página serve três públicos principais:
- **Jovens universitários** em busca de um curso de graduação em tecnologia
- **Diretores de TI** interessados no perfil dos futuros profissionais formados
- **Comunidade local** de Votuporanga e região

## Funcionalidades

- **Carrossel de professores** com loop infinito, navegação por teclado e suporte a swipe mobile
- **Seção de projetos** com destaque para o Eniac Cast, Reengenharia e UNIC
- **Menu responsivo** com hambúrguer para dispositivos móveis
- **Navegação suave** com scroll behavior e highlight do link ativo
- **Header inteligente** que se esconde ao rolar para baixo e reaparece ao subir
- **Acessibilidade** com `aria-label`, `aria-hidden` nos clones, navegação por teclado e dots acessíveis
- **SEO** com meta tags, Open Graph, Twitter Card e canonical

## Tecnologias

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-Poppins-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

Sem frameworks. Sem dependências externas. HTML, CSS e JavaScript puro.
</div>

## Estrutura do Projeto
```
LPEC/
├── index.html              # Página principal
├── main.css                # Estilos globais
├── carrossel.js            # Lógica do carrossel de professores
├── app.js                  # Scripts auxiliares
└── components/
    └── image/
        ├── profs/          # Fotos dos professores
        ├── logoCOMP.png    # Logo do curso
        ├── background.png  # Imagem de fundo
        └── ...             # Demais imagens
```

## Como Rodar Localmente

Não é necessário instalar nada. Basta clonar o repositório e abrir o arquivo HTML:
```bash
git clone https://github.com/vhtasca/LPEC.git
cd LPEC
```

Depois abra o `index.html` no navegador, ou use a extensão **Live Server** no VS Code para hot reload.

> ⚠️ Abrir via `file://` pode causar bloqueio de recursos por CORS em alguns navegadores. Recomenda-se usar o Live Server.


## Como Adicionar um Novo Professor

1. Adicione a foto em `components/image/profs/` (formato `.jpg` ou `.png`, proporção quadrada, recomendada **1080×1080px**)
2. No `index.html`, localize a `<div class="track">` dentro da seção `#professores`
3. Copie um bloco `.card` existente e substitua os dados:
```html
<div class="card">
    <div class="quadrado">
        <img src="components/image/profs/nome-arquivo.jpg"
             alt="Foto do professor Nome Completo"
             loading="lazy">
    </div>
    <h3>Nome Completo</h3>
    <p>Breve descrição da formação acadêmica.</p>
</div>
```

> Imagens dos professores fornecidas pelo marketing UNIFEV - [publicadas no flickr da faculdade.](https://www.flickr.com/photos/unifevvotu/albums)

## Acessibilidade

- `aria-label` nos botões de navegação do carrossel
- `aria-hidden="true"` nos cards clonados (loop infinito)
- `role="region"` e `aria-live="polite"` no carrossel
- Navegação por teclado (`←` `→`) no carrossel
- Dots de navegação como `<button>` com `aria-label` e `aria-current`
- `loading="lazy"` em todas as imagens
- `alt` descritivo em todas as imagens
- `skip-link` para pular ao conteúdo principal

## SEO

- Meta description configurada
- Open Graph completo (título, descrição, imagem, URL, tipo)
- Twitter Card com `summary_large_image`
- Link canonical
- Fonte Poppins com `preconnect` para carregamento otimizado

## Autores

Projeto iniciado e desenvolvido por alunos de Engenharia de Computação - UNIFEV.

<div align="center">

| Nome | GitHub |
|------|--------|
| Victor | [@vhtasca](https://github.com/vhtasca) |
| Gabriel | [@gabrielpassos7](https://github.com/gabrielpassos7) |
| Alanna | [@alannaaaa](https://github.com/alannaaaa) |
| Cauê | [@cauesalvioni](https://github.com/cauesalvioni) |
| Henrique | [@HenriqueBHeck](https://github.com/HenriqueBHeck) |
| Hugo | [@TDVLoredius](https://github.com/TDVLoredius) |
| João | -

</div>

---
<br>

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/vhtasca/LPEC?style=flat-square&color=58a6ff)
![GitHub last commit](https://img.shields.io/github/last-commit/vhtasca/LPEC?style=flat-square&color=58a6ff)
![GitHub contributors](https://img.shields.io/github/contributors/vhtasca/LPEC?style=flat-square&color=58a6ff)

</div>



<div align="center">

Este projeto é de uso institucional do curso de Engenharia de Computação da UNIFEV.

*Desenvolvido por* **.zip** *· 2025–2026*
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" />

</div>