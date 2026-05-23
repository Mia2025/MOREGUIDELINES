# MORE — Brand Center (site hospedável)

Site estático pronto pra GitHub + Vercel. Quem acessa o link baixa logo, fontes,
ícones, assinatura e o pacote completo direto no navegador.

## Estrutura
- index.html ... versão Português
- en.html ...... versão Inglês (link PT/EN no canto superior)
- assets/ ...... arquivos para download (logos, fontes, ícones, assinatura, pacote)
- vercel.json .. configuração

## Como subir no Vercel (sem GitHub)
1. vercel.com -> Add New -> Project -> "Deploy" arrastando a pasta inteira
2. Pronto: recebe um link *.vercel.app
3. Em Settings -> Domains, conecte seu dominio (ex.: branding.seudominio.com)

## Como subir via GitHub
1. Cria um repositorio e sobe esta pasta
2. Em vercel.com -> Add New -> Project -> Import o repositorio
3. Framework: "Other" / Output: raiz. Deploy.

Links finais:
  seudominio.com         -> Portugues
  seudominio.com/en      -> Ingles
