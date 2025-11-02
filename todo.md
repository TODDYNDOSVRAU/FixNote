# QuoteTech - Project TODO

## Features

- [x] Design system and global styling (colors, typography, animations)
- [x] Header/Navigation component with sticky positioning
- [x] Home page with hero section
- [x] Search component with input field and "Buscar Cotação" button
- [x] "Como Funciona" section with 3 columns and icons
- [x] API integration for quotation search (mock data)
- [x] Loading animation (shimmer effect) during API calls
- [x] Results page with dynamic data binding
- [x] Machine information section (model, image)
- [x] Labor analysis section (difficulty, time, suggested value)
- [x] Dynamic parts list with cards
- [x] Supplier links section with prices
- [ ] Export to PDF functionality
- [ ] Save quotation functionality (for logged-in users)
- [x] About Us page (static)
- [x] Contact page (static)
- [x] Responsive design (mobile-first)
- [x] Footer component

## Bugs & Issues

(None yet)

## Correções Solicitadas

- [x] Corrigir data binding na página de Resultados com JSON de exemplo
- [x] Verificar exibição do modelo identificado (Dell G15 5511)
- [x] Verificar exibição da dificuldade de reparo (Médio/Difícil)
- [x] Verificar exibição do valor de mão de obra (R$ 250,00 - R$ 300,00)
- [x] Verificar repetidor de peças (3 cards: Tela, Bateria, Teclado)
- [x] Verificar sub-repetidor de fornecedores (links clicáveis com URLs corretas)
- [x] Testar fluxo completo Home -> Busca -> Resultados


## Implementação IA + APIs (Nova)

- [x] Criar procedimento tRPC para identificação de notebook com IA (Claude)
- [x] Implementar análise de especificações exatas do notebook via IA
- [x] Integrar API de busca de peças (Mercado Livre, Amazon, AliExpress)
- [x] Implementar busca inteligente de peças compatíveis com IA
- [x] Gerar links reais de compra com preços atualizados
- [x] Integrar chamadas tRPC no frontend (Home.tsx)
- [x] Testar fluxo completo com dados reais
- [x] Validar links de compra funcionando corretamente


## Aprimoramentos (Imagens + Links Precisos + Velocidade)

- [x] Implementar busca de imagens para notebooks (Google Images ou Bing)
- [x] Implementar busca de imagens para peças específicas
- [x] Implementar web scraping inteligente com IA para links precisos
- [x] Buscar produtos exatos em Mercado Livre, Amazon, AliExpress, Shopee
- [x] Validar preços e disponibilidade em tempo real
- [x] Paralelizar buscas de múltiplos fornecedores
- [x] Otimizar prompts da IA para resposta mais rápida
- [ ] Implementar cache de resultados para notebooks já pesquisados
- [ ] Testar com múltiplos modelos de notebook
- [ ] Validar links e preços funcionando corretamente

## Implementação de Imagens Reais (Nova)

- [x] Buscar imagens reais de notebooks de Google Images ou sites especializados
- [x] Extrair imagens de produtos dos links de e-commerce (Amazon, Mercado Livre, AliExpress)
- [x] Implementar fallback para placeholder se imagem não encontrada
- [x] Testar fluxo completo com imagens reais


## Validação de Links e Imagens do Google (Nova)

- [x] Implementar validação de links com IA para confirmar que o produto existe
- [x] Verificar se o produto no link é exatamente o correto (não apenas código semelhante)
- [x] Exibir "Não encontrado" quando o produto não existir em um site específico
- [x] Buscar imagens reais do Google Images para notebooks e peças
- [x] Testar validação com múltiplos produtos e fornecedores


## Correções de Precisão (Nova)

- [ ] Ajustar IA para ser mais flexível - só marcar "Não disponível" quando REALMENTE não encontrar nada
- [ ] Corrigir busca de imagens do Google para retornar URLs válidas
- [ ] Melhorar prompts da IA para ser mais assertiva e precisa
- [ ] Testar com múltiplos notebooks e validar precisão
