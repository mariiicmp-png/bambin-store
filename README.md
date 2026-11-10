# BAMBIN — loja virtual demonstrativa

Projeto de e-commerce responsivo desenvolvido para apresentação acadêmica (TCC).

## Como executar

1. Extraia a pasta `bambin-store`.
2. Abra `index.html` em um navegador moderno. Para melhor compatibilidade, execute um servidor local na pasta:

   ```bash
   python -m http.server 8000
   ```

3. Acesse `http://localhost:8000`.

Não há dependências de build ou instalação de pacotes. O projeto utiliza HTML, CSS e JavaScript puros.

## Funcionalidades implementadas

- Navegação por páginas via hash: início, catálogo, detalhes de produto, clube, assinatura, sustentabilidade, doação, guias, atendimento, favoritos e checkout.
- Catálogo com filtros por faixa etária, busca e ordenação por preço.
- 12 produtos com descrições, modo de brincar, materiais indicativos, habilidades relacionadas e recomendações de segurança.
- Favoritos e carrinho com quantidades, remoção e persistência via `localStorage`.
- Fluxo demonstrativo de assinatura com três planos.
- Página de pontos de doação com orientações, campos demonstrativos e formulário de interesse validado.
- Formulário de atendimento e perguntas frequentes.
- Checkout em quatro etapas, com resumo, frete ilustrativo e seleção de forma de pagamento sem coleta de dados bancários.
- Layout adaptável para desktop, tablet e celular.

## Limites desta versão

- Não existe backend, banco de dados, autenticação, estoque, emissão de pedidos ou envio real de formulários.
- Nenhum gateway de pagamento está integrado. Cartão e PIX aparecem somente como opções ilustrativas; não inserir dados reais.
- O frete é calculado com regra demonstrativa e não consulta transportadoras.
- Os endereços dos pontos de coleta não foram inventados: a página informa que os locais oficiais ainda precisam ser cadastrados.
- Preços, quantidades, periodicidade, materiais, contatos e depoimentos são demonstrativos e devem ser revisados antes de uso comercial.

## Imagens

As imagens da pasta `assets/` estão em WebP. A imagem do banner e as imagens de lifestyle foram geradas por IA para este projeto e recortadas/otimizadas a partir das composições geradas nesta conversa. Os recortes apresentam cenas distintas de crianças brincando; não são fotografias de produtos reais de fornecedores nem substituem fotos de catálogo verificadas. Antes de lançar a loja, substitua cada imagem por fotografia própria/licenciada do produto exato e confirme a adequação de uso de imagens de crianças.

## Identidade visual

- Creme: `#F7F3E9`
- Terracota: `#814B3D`
- Marrom escuro: `#60351F`
- Verde sálvia: `#849477`
- Bege: `#EAD9C3`
- Branco: `#FFFFFF`
