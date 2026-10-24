# Serviços Já — Página de Divulgação Oficial

> **“Precisou de um serviço? Encontre o caminho certo!”**

Página de divulgação moderna, profissional, acolhedora, responsiva e persuasiva para o **Serviços Já**, uma plataforma brasileira voltada a aproximar clientes de profissionais prestadores de serviços de diversas especialidades.

---

## 🎯 1. Objetivos Atendidos
- **Divulgação da plataforma:** Apresentar a proposta de valor do Serviços Já de forma clara, moderna e transparente.
- **Captação de Profissionais:** Seção dedicada valorizando o prestador de serviço, incentivando a demonstração de interesse sem promessas irreais de renda garantida.
- **Estímulo para Clientes:** Apresentação prática de busca, visualização de categorias e orientações de segurança para contratação.
- **Transparência Absoluta:** Categorias identificadas honestamente como sugestões/em expansão e etapas futuras devidamente explicadas sem alegar recursos inexistentes.

---

## 🎨 2. Identidade Visual e Experiência
- **Cores Principais:** Azul Profundo (`#0A1E3F`, `#07152B`, `#1E40AF`), Branco Puro e detalhes em Verde Esmeralda (`#10B981`, `#059669`) transmitindo confiança, credibilidade e dinamismo.
- **Design:** Cantos arredondados (`border-radius: 14px-20px`), sombras suaves, ícones SVG vetoriais leves e botões com destaque visual.
- **Tipografia:** Google Fonts (*Plus Jakarta Sans* para títulos e destaques; *Inter* para leitura fluida e acessível).
- **Responsividade Total:** Testado e otimizado para celulares (Android, iPhone), tablets e monitores desktop.
- **Acessibilidade e SEO:** Tags semânticas HTML5, contrastes conforme diretrizes WCAG, meta tags Open Graph (para WhatsApp e redes sociais), Twitter Card e dados estruturados Schema.org.

---

## 🏗️ 3. Estrutura e Funcionalidades da Página
1. **Header e Navegação:**
   - Logotipo com slogan integrado.
   - Menu desktop e menu drawer mobile com botão hambúrguer.
   - Botão rápido para cadastro de interesse.
2. **Hero (Destaque Principal):**
   - Título: *"Seu próximo cliente ou profissional está mais perto do que você imagina."*
   - Subtítulo: *"O Serviços Já está construindo uma maneira prática de aproximar quem precisa de serviços de quem sabe fazer."*
   - Botões de ação rápida:
     - *Sou profissional — Quero me cadastrar* (leva ao formulário focado no profissional).
     - *Preciso de um serviço — Quero encontrar* (leva à busca e categorias).
   - Barra de confiança com garantias da fase de lançamento.
3. **Seção para Profissionais:**
   - Título: *"Transforme sua habilidade em novas oportunidades."*
   - 4 Destaques: Cadastro simples, divulgação futura, acesso móvel/desktop e participação inicial gratuita.
   - Botão: *Quero participar*.
4. **Seção para Clientes:**
   - Título: *"Encontre profissionais para o que você precisa."*
   - Simulação interativa de busca por serviço e localização.
   - Botão: *Conhecer a plataforma*.
5. **Categorias de Serviços (com filtro em tempo real):**
   - 8 cartões visuais com ícones dedicados:
     - Serviços residenciais
     - Elétrica e instalações
     - Hidráulica
     - Limpeza e organização
     - Beleza e cuidados pessoais
     - Informática e tecnologia
     - Manutenção e reparos
     - Outros serviços
   - Tag de identificação: *"Sugestão • Em cadastro"*.
   - Ao clicar em qualquer categoria, o formulário é pré-preenchido automaticamente.
6. **Como Funciona:**
   - Etapas numeradas e claras separadas para Clientes e Profissionais.
   - Caixa de compromisso de transparência: etapas não implementadas não são prometidas como ativas.
7. **Confiança e Segurança:**
   - Título: *"Mais transparência para escolher melhor."*
   - Recomendações: Conferir referências, combinar preço e escopo por escrito, proteger dados pessoais e comunicar situações abusivas.
8. **Formulário Funcional de Demonstração de Interesse:**
   - Alternador rápido: Profissional vs. Cliente.
   - Campos com validação: Nome, WhatsApp (com máscara automática), E-mail, Cidade/UF, Especialidade e Mensagem opcional.
   - Salva os dados em tempo real no `localStorage` do navegador.
   - Exibe confirmação imediata ao usuário.
9. **Seção de Divulgação e Compartilhamento Rápido:**
   - **Botão “Copiar link”**: Copia o endereço oficial da plataforma com confirmação imediata (*“Link copiado com sucesso!”*). Caso a cópia automática seja bloqueada pelo navegador, aciona o modal com campo selecionável para cópia manual.
   - **Botão “Copiar texto de divulgação”**: Copia uma mensagem promocional pronta contendo o nome Serviços Já, uma explicação breve das categorias e o link oficial. Exibe a confirmação (*“Texto de divulgação copiado com sucesso!”*) e conta com fallback manual.
   - **Botão “Divulgar no WhatsApp”**: Abre o WhatsApp com a mensagem promocional pré-preenchida, permitindo ao usuário selecionar contatos ou grupos para envio.
   - **Facilidade de Uso no Celular**: Botões grandes (altura mínima de 54px), touch-friendly, contrastes otimizados e espaçamento adequado para toque.
   - **Compartilhamento Secundário**: Atalhos em pílula para Facebook, X (Twitter) e LinkedIn.
10. **Segurança e Privacidade Absoluta:**
    - Nenhuma ferramenta administrativa ou de teste é exibida aos visitantes públicos.
    - Nenhum dado de clientes, profissionais ou anunciantes é exposto a terceiros.
    - O formulário de interesse opera com privacidade e conformidade com a LGPD.
11. **Modais Informativos:**
    - Modal de Cópia Manual (fallback de segurança e compatibilidade).
    - Política de Privacidade (em conformidade com a LGPD).
    - Termos de Uso (clareza sobre ausência de promessa de renda garantida).
    - Fale Conosco.

---

## 🚀 4. Como Testar e Visualizar Localmente

### Opção 1: Abrir diretamente no Navegador
Basta dar um duplo clique no arquivo `index.html` ou abri-lo em qualquer navegador (Google Chrome, Edge, Firefox, Safari):
```
C:\Users\edinaldo\.gemini\antigravity\scratch\servicos-ja\index.html
```

### Opção 2: Servidor Local (Node.js)
Abra o terminal na pasta do projeto e execute:
```bash
npx --yes serve .
```
Acesse `http://localhost:3000` no seu navegador.

---

## 🌐 5. Como Publicar no GitHub e Hospedar no Vercel / GitHub Pages

Se você desejar publicar a página online para ter um link público:

1. **Inicializar o repositório git local:**
   ```bash
   cd "C:\Users\edinaldo\.gemini\antigravity\scratch\servicos-ja"
   git init
   git add .
   git commit -m "Publicação inicial da página de divulgação do Serviços Já"
   ```

2. **Criar o repositório no seu GitHub:**
   Crie um repositório chamado `servicos-ja` no GitHub (conta `neoremtex-web`).

3. **Conectar e enviar:**
   ```bash
   git remote add origin https://github.com/neoremtex-web/servicos-ja.git
   git branch -M main
   git push -u origin main
   ```

4. **Publicação no Vercel (Gratuito):**
   - Acesse [vercel.com](https://vercel.com) e importe o repositório `servicos-ja`.
   - O Vercel detectará o arquivo `index.html` e `vercel.json` e publicará o site instantaneamente com domínio gratuito (ex: `https://servicos-ja.vercel.app`).
