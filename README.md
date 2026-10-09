# Rede-semente-ong[README.md](https://github.com/user-attachments/files/33270634/README.md)

# Rede Semente

Protótipo acadêmico de plataforma institucional para uma organização social fictícia. O site estático reúne apresentação institucional, projetos, oportunidades para voluntariado, transparência demonstrativa e cadastro de interesse.

## Estrutura

- `index.html` — início, missão, valores, projetos em destaque, contato e newsletter.
- `projetos.html` — projetos com filtro por categoria, oportunidades, área demonstrativa de doação e transparência.
- `cadastro.html` — cadastro de interesse com campos semânticos, validação nativa, máscaras e verificação dos dígitos do CPF.
- `style.css` — identidade visual, layout mobile-first, breakpoints e estados de foco/acessibilidade.
- `script.js` — navegação móvel, filtros e comportamentos demonstrativos dos formulários.
- `assets/` — ilustrações SVG locais e escaláveis.

## Executar

Abra `index.html` em um navegador ou sirva a pasta com qualquer servidor web estático. Não há dependências de build nem recursos externos obrigatórios.

## Acessibilidade e desempenho

As páginas usam landmarks HTML5, títulos hierárquicos, link para pular ao conteúdo, navegação por teclado, rótulos associados, anúncios de estado com `aria-live`, foco visível e suporte a `prefers-reduced-motion`. Imagens decorativas são SVGs locais; imagens fora do primeiro viewport usam carregamento tardio. O layout possui adaptações para telas móveis, intermediárias e amplas.

## Limites importantes da demonstração

- O formulário valida os dados no navegador, mas **não envia nem armazena informações pessoais**. Não informe dados reais neste protótipo.
- Máscaras de CPF, telefone e CEP são conveniências de entrada; o CPF também tem os dígitos verificadores conferidos no navegador. Validação no cliente não substitui validação segura no servidor.
- A área de doação **não processa pagamentos**. Para uso real, é necessário backend, integração com um provedor de pagamento, HTTPS, proteção contra abuso e políticas de privacidade e retenção de dados.
- Newsletter, certificados, autenticação/painel administrativo, relatórios para download e inscrição/seleção persistente de voluntários precisam de serviços e implementação de backend.
- Nome, endereço, telefone, e-mail, CNPJ, estatísticas, vagas, relatórios e contato exibidos são dados fictícios de demonstração e devem ser substituídos e verificados pela ONG antes da publicação.
- HTTPS é configurado no serviço de hospedagem, não por arquivos HTML locais. Nenhum link público do GitHub foi criado por este protótipo.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub e envie os arquivos desta pasta mantendo os caminhos.
2. Em **Settings → Pages**, escolha a branch e a pasta raiz como origem.
3. Acesse o endereço fornecido pelo GitHub Pages e verifique as três páginas em desktop e celular.
4. Antes de divulgar, substitua os dados demonstrativos, configure domínio/HTTPS se necessário e conecte serviços reais de forma segura.

## Validação HTML

Valide cada página publicada ou o código copiado no [W3C Nu HTML Checker](https://validator.w3.org/nu/). Revise também a acessibilidade e contraste com testes automatizados e navegação manual por teclado/leitor de tela; a estrutura de um protótipo não representa, por si só, certificação WCAG 2.1 AA.
