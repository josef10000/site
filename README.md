# Hub Symples - Ecossistema de Gestão e Vendas

Bem-vindo ao repositório oficial da **Hub Symples**, um ecossistema completo de gestão e vendas (Site Inteligente + Portal Hub) desenhado para trazer comodidade, ordem e previsibilidade para empreendedores sobrecarregados, eliminando a dependência excessiva do Instagram e o caos do WhatsApp.

O projeto é estruturado de forma ultra eficiente em um único arquivo de código-fonte (`index.html`), facilitando a manutenção e garantindo carregamento instantâneo.

---

## 🌟 Estrutura do Site

O site foi completamente redesenhado para adotar uma estética SaaS B2B moderna, limpa e fullscreen (inspirada no estilo do site da Ace Cortex), com cores suaves, cantos arredondados, sombras leves e menus flutuantes dinâmicos.

### ⚓ Barra de Navegação Flutuante (Glassmorphism)
Uma barra fixa no topo da página, pill-shaped com `backdrop-filter: blur(16px)` e fundo semitransparente, que acompanha a rolagem do usuário trazendo links de acesso rápido e um botão CTA chamativo para falar com especialistas no WhatsApp.

### 🚀 Dobra Inicial (Hero Section Fullscreen)
* **Design Limpo e Fluido**: Com um plano de fundo creme suave (`#f5f3ec`) e uma animação dinâmica de Aurora WebGL ao fundo, gerando um visual premium e relaxante.
* **Mensagem Forte de Valor**: Headline focada na dor do cliente ("Você não precisa de mais curtidas. Precisa de comodidade, ordem e previsibilidade.") e botão de ação em destaque.
* **Contador de Membros**: Mostra dinamicamente quantos negócios já adotaram a solução.

### 📝 Manifesto da Ordem (Filosofia)
Dois painéis modernos de leitura e um aviso de utilidade pública estilizado que explicam por que o empreendedor deve se libertar do caos operacional e focar no que realmente importa.

### ⚖️ Ecossistema Hub Symples
Cards modernos (`card-modern`) com bordas sutis e sombras elegantes descrevendo os dois pilares da solução:
1. **A Porta (O Site Inteligente)**: Focado em atração e qualificação de clientes qualificados.
2. **A Casa (O Portal Hub)**: Painel de gestão diária e controle do negócio.

### 📱 Slider Interativo "Antes vs. Depois"
Moldura metálica de smartphone moderna com slider funcional que contrasta o feed do Instagram desorganizado com o site oficial premium e rolável da marca do cliente.

### 💻 Painel Interativo Portal Hub (Simulador do Dashboard)
Painel interativo no qual o usuário pode navegar por 4 abas simuladas e executar ações reais em tempo real:
* **Agenda**: Simulação de confirmação de compromissos com disparo de notificações.
* **CRM Financeiro**: Exibição visual de receitas e simulação de cobrança Pix direta por WhatsApp.
* **Growth Hub**: Player para ouvir pílulas rápidas de áudio de mentoria e copiar scripts de venda prontos.
* **Máquina de LTV**: Geração rápida de copy de reativação personalizada em 1 clique para clientes antigos.

### 💳 Planos e Assinaturas
Tabela de preços com design limpo contendo 3 planos (Start, Pro e Elite), toggle interativo de faturamento Mensal/Anual com desconto aplicado, e visualização intuitiva de benefícios.

### 💬 FAQ & Prova Social
* **Depoimentos**: Carrossel de relatos reais com avatares, estrelas de avaliação e feedback de clientes.
* **Acordeão de Dúvidas**: FAQ interativa com animações suaves de abertura e fechamento para quebrar objeções comuns.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** & **Tailwind CSS** (via CDN com configurações personalizadas e tema moderno).
* **JavaScript Puro (Vanilla JS)**: Lógica de abas, slider de antes/depois, simulações financeiras e operacionais, FAQ, carrossel de depoimentos e formulário chatbot.
* **OGL Library**: Biblioteca WebGL minimalista de alta performance usada para gerar o background dinâmico de Aurora.
* **Font Awesome & Google Fonts**: Ícones vetorizados e a tipografia moderna *Inter*.

---

## 🚀 Como Rodar o Projeto

Como o projeto preza pelo minimalismo e máxima performance:
1. **Não há dependências complexas de backend**.
2. O Node.js e o npm estão instalados e configurados na máquina, mas para execução básica basta abrir o arquivo `index.html` em qualquer navegador.
3. Para desenvolvimento local do CSS/Tailwind e testes de sintaxe, pode ser utilizado um live server simples.

---

## 📌 Histórico de Evolução

* **[Junho/2026] Redesenho Visual Moderno (Inspirado em Ace Cortex)**:
  * **Adeus Jornal Antigo**: Remoção completa da estética vintage de jornal de banca, bordas pretas duplas, capitular serifada, gravuras e fundos envelhecidos.
  * **Nova Identidade Visual**: Implementação do design fullscreen moderno baseado em tons creme `#f5f3ec` e escuro `#1a1a1a`, com cards arredondados suaves (`card-modern`) e sombras profundas porém sutis.
  * **Floating Glassmorphism Navbar**: Criação do menu de navegação flutuante no topo com desfoque de fundo e links arredondados elegantes.
  * **Aurora WebGL**: Integração do fundo de aurora animada no Hero e cabeçalho, sintonizado com a paleta moderna.
  * **Ajuste de CTAs e Cores**: Preservada a cor de destaque azul elétrico `#0055ff` de acordo com a preferência do usuário e atualizado o layout de botões para formatos de pílula (`btn-pill`).
  * **Verificação e Validação**: Sintaxe inteiramente testada e validada com o script `check_syntax.js`.
* **[Junho/2026] Refinamento Estrutural e de Conversão (Layout Ace Cortex)**:
  * **Remoção do Banner de Urgência**: Retirado o banner de urgência vermelho do topo para um visual mais limpo e profissional.
  * **Hero em Duas Colunas**: A dobra inicial (Hero) foi otimizada para duas colunas (headline e CTA à esquerda, mockup tridimensional animado do Portal Hub com efeitos dinâmicos à direita) incorporando a logo e nome local.
  * **Antes vs. Depois Otimizado**: Reorganização em duas colunas (texto explicativo à esquerda, smartphone interativo à direita) e restauração do design premium original de alta autoridade (Dra. Alessandra Veiga) no mockup do celular.
  * **Seção de Criadores em Fundo Escuro**: A seção de influenciadores/criadores foi atualizada com fundo preto (`#050505`) e cards em glassmorphism escuro para maximizar o contraste e o apelo visual.
* **[Junho/2026] Pivot de Posicionamento para Ecossistema SaaS B2B**:
  * **Rebranding da Copy**: Nova Hero Section focada no fim do caos operacional no WhatsApp e previsibilidade real; reescrita do Manifesto da Autoridade para "Manifesto da Ordem".
  * **Reengenharia do Portal Hub (A Casa)**: Substituição dos painéis por ferramentas funcionais de **Agenda Integrada** (simulador de no-show), **CRM Financeiro** (cobrança Pix rápida), **Growth Hub** (mentoria em áudio) e **Máquina de LTV** (reativação de leads em 1 clique).
  * **Tabela Comercial**: Atualização da ancoragem de planos para destacar o Portal Hub e o robô de lembrete de WhatsApp contra faltas.ientes inativos e gerar scripts personalizados de WhatsApp em 1 clique).
  * **Sintonização Comercial**: Atualização da tabela de planos comerciais, depoimentos do carrossel (focados em tempo livre, redução de no-shows e inadimplência) e FAQ de acordo com a proposta de ecossistema de gestão.


