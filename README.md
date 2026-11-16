# Plataforma Matrix

Plataforma para aprender, construir, vender e entregar soluções de IA para empresas: trilhas de aprendizado, catálogo de 20 soluções, estúdio, biblioteca de prompts, nichos, CRM, diagnóstico, propostas, calculadora de preços, scripts de venda, métricas e gestão de projetos.

Site estático em um único arquivo (`index.html`), sem build e sem backend. Os dados (progresso, CRM, propostas) ficam salvos no navegador de quem usa (localStorage); use Configurações → Backup para exportar e importar.

## Rodar localmente
```bash
python3 -m http.server 8000   # abra http://localhost:8000
```

## Publicação
O workflow em `.github/workflows/pages.yml` publica no GitHub Pages a cada push na `main`.

> O Consultor IA só aparece dentro do claude.ai; fora dele a plataforma funciona sem essa função.
