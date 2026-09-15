# CISP1 — nova versão

Site institucional reconstruído do zero, sem leitura ou reaproveitamento dos HTMLs, CSS ou JavaScript anteriores. Conteúdo baseado nos Markdown da CISP1; referência de composição e narrativa: https://scale.com/.

## Visualizar

Abra `index.html` no navegador ou sirva esta pasta com um servidor HTTP estático. A prévia da sessão está em http://127.0.0.1:8765/cisp1-premium/.

## Conteúdo e interações

- Abertura com vídeo do cliente e controle para pausar vídeos.
- Narrativa de rolagem com GSAP no desktop e leitura linear no celular.
- Arquitetura ilustrada com o material fornecido.
- Oito camadas selecionáveis por clique ou teclado.
- Dezenove cases anônimos, filtros por setor e detalhes em diálogo.
- Seis pilares de segurança expansíveis.
- Modelo operacional em seis etapas, diferenciais e impacto esperado.
- Navegação responsiva e menu de plataforma.

## Organização

`index.html`: página e conteúdo institucional.
`style.css`: identidade visual e responsividade.
`app.js`: camadas, cases, menus, vídeos e movimento.
`assets/`: cópias dos materiais originais usados na versão; a pasta pode ser movida como uma unidade.

Sora é carregada pelo Google Fonts. GSAP e ScrollTrigger 3.13.0 são carregados pelo jsDelivr. Sem essas dependências externas, fontes locais de fallback e conteúdo estático continuam disponíveis.

Os CTAs de contato encaminham para https://cisp1.io/oportunidades. Não há formulário com envio simulado. Os cases não incluem métricas ou nomes de clientes ausentes das fontes. Esta entrega é local; nenhum domínio ou site em produção foi alterado.

## Verificação

Sintaxe de JavaScript validada. Verificados em navegador: menu de plataforma, troca de camada, navegação de tabs por teclado, filtro Saúde, expansão dos 19 cases, abertura e fechamento do diálogo, menu mobile e ausência de rolagem horizontal na menor largura testada. Console sem erros no teste.

## Páginas internas

A versão agora inclui 27 páginas HTML: home, Plataforma, Como trabalhamos, Segurança & Governança, Cases, Sobre, Demonstrações, Contato e 19 páginas individuais de cases. As rotas usam diretórios com `index.html` e funcionam em hospedagem estática.

O catálogo permite combinar setor e capacidade; filtros ficam na URL e podem ser compartilhados. A taxonomia de capacidades é uma organização editorial baseada nos títulos documentados, não uma declaração do stack de cada projeto. Os detalhes de cases se limitam a aplicação e contexto disponíveis nas fontes, sem resultados quantitativos, depoimentos ou arquitetura inventados.

A página de demonstrações apresenta as capacidades documentadas e encaminha a uma conversa com a equipe. Execução de IA ao vivo depende do ambiente original de Playground, cuja integração não foi fornecida. O contato encaminha ao canal atual da CISP1.

Verificação desta expansão: 27 páginas e 834 referências locais verificadas sem arquivos ausentes; filtros combinados, estado vazio, limpeza de filtros e navegação para case individual conferidos no navegador. Conteúdo das páginas internas servido diretamente, sem depender de JavaScript para leitura.

## Coleção visual dos cards

30 ilustrações originais geradas com a ferramenta nativa de imagens: 19 cases, 5 diferenciais e 6 etapas do método. Todas seguem vidro fumê, reflexos azul-cobalto e fundo azul-marinho. Aplicadas nos cards e nas capas internas dos cases.

Originais PNG, versões JPEG para web, manifesto e prompts completos ficam em `assets/illustrations/`. As versões web somam aproximadamente 10,3 MB, 84% menores que os originais. O carregamento dos cards é adiado até próximo da área visível.

Verificação: referências de imagens sem arquivos ausentes, sintaxe de JavaScript validada e composição das capas conferida no navegador em desktop e celular.

## Revisão global de grid e espaçamento

`layout.css` centraliza a largura de página, margens fluidas, ritmo vertical, grids e larguras de leitura nas 27 páginas. Cards, capas de cases, etapas do método, páginas editoriais e rodapé compartilham os mesmos alinhamentos. Layouts de todos os nove tipos de página conferidos em larguras de 1066 e 318 pixels; sem transbordamento horizontal no celular.
