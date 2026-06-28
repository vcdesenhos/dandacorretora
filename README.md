# Danda · Corretora de Imóveis — Landing Page

Site de página única (estático). Sem build, sem dependências.

## Estrutura
```
danda-corretora/
├── index.html
└── assets/
    ├── logo-danda.png
    ├── danda-retrato.png
    └── imoveis/  (4 imóveis × 5 fotos)
```

## Como publicar
- **Vercel:** arraste a pasta `danda-corretora` em vercel.com/new, ou conecte um repositório GitHub. Sem configuração — é HTML puro.
- **GitHub Pages:** suba a pasta no repositório e ative o Pages na branch principal.
- **Testar local:** abra o `index.html` no navegador.

## O que editar depois
- **WhatsApp / CRECI:** número `5511999888501` e CRECI `299420` estão no `index.html` (constante `WA` e rodapé).
- **Imóveis:** array `IMOVEIS` no `<script>` — adicionar/editar imóvel, preço, fotos, etc.
- **Números da seção de estatísticas, depoimentos e Instagram:** marcados com comentários `NOTA p/ a Danda` no HTML — trocar por dados reais antes de publicar.
