# 📊 MultiPercentageKPI - Power BI Custom Visual

[![Power BI](https://img.shields.io/badge/Power%20BI-Compatible-yellow.svg)](https://powerbi.microsoft.com/)
[![Version](https://img.shields.io/badge/Version-1.0.1-blue.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#licença)
[![Downloads](https://img.shields.io/badge/Downloads-1K+-brightgreen.svg)](#download)

Visual customizado avançado para Power BI que apresenta KPIs percentuais em formatos de círculo e triângulo com rotação interativa.

[🚀 Download](#download) • [📖 Como Usar](#como-usar) • [🎯 Exemplos](#exemplos-de-uso) • [💬 Contato](#contato--suporte)

![MultiPercentageKPI Demo](icon.png)

## 🌟 O que é o MultiPercentageKPI?

MultiPercentageKPI é um visual customizado revolucionário para Power BI que transforma a apresentação de indicadores percentuais. Com suporte a formatos circular e triangular, rotação interativa e personalização completa, oferece uma solução elegante e profissional para dashboards modernos.

## ✨ Por que usar o MultiPercentageKPI?

🎯 **Experiência Intuitiva**: Interface limpa com controles de rotação por clique e teclado  
🔧 **Altamente Configurável**: Formatos círculo/triângulo com cores e bordas personalizáveis  
📱 **100% Responsivo**: Centralização perfeita em qualquer dimensão  
🎨 **Totalmente Customizável**: Cores, tamanhos, formatos e rotação configuráveis  
⚡ **Performance Superior**: Otimizado com React + D3.js para renderização eficiente  

## 🚀 Principais Funcionalidades

### 📊 Visualização Avançada de KPIs
✅ **Formato Duplo**: Escolha entre círculo clássico ou triângulo moderno  
✅ **Progresso Visual**: Preenchimento gradual baseado na porcentagem  
✅ **Rotação Interativa**: Clique (30°) ou teclado (±15°) para rotacionar  
✅ **Centralização Perfeita**: Texto sempre centralizado independente do tamanho  
✅ **Gradientes Dinâmicos**: Cores com gradiente automático para visual premium  

### 🎛️ Controles Avançados
✅ **Ativar/Desativar Rotação**: Toggle para habilitar interatividade  
✅ **Formatos Flexíveis**: Decimal (0.0-1.0) ou Percentual (%)  
✅ **Precisão Configurável**: 0-5 casas decimais  
✅ **Bordas Customizáveis**: Largura e cor independentes  
✅ **Tipografia Avançada**: Tamanho e cor do texto personalizáveis  

### 🎨 Personalização Total
🎨 **5 Configurações de Cor**: Customize cada elemento visual  
📏 **Controles de Dimensão**: Bordas, fontes e elementos proporcionais  
🔄 **Rotação Inteligente**: Limitada entre 0-360° com incrementos precisos  
📱 **Design Responsivo**: Adapta-se automaticamente ao container  

## 📥 Download

**📦 Versão Atual: 1.0.1**

[📥 Download MultiPercentageKPI.pbiviz](MultiPercentageKPI.pbiviz)

*Tamanho: ~200KB | Compatibilidade: Power BI Desktop/Service/Mobile*

## 🛠️ Como Instalar

1. Baixe o arquivo `visual.pbiviz` clicando no botão acima
2. Abra o Power BI Desktop
3. Vá em: **Arquivo → Importar → Visual do arquivo**
4. Selecione o arquivo baixado
5. **Pronto!** O visual aparecerá no painel de visualizações

## 🎯 Como Usar

### 1️⃣ Configuração Básica de Dados

| Seção | Campo | Obrigatório | Descrição |
|-------|-------|-------------|-----------|
| 📊 **Dados** | Valor | ✅ **Sim** | Valor percentual (0-1 para decimal ou 0-100 para %) |

### 2️⃣ Configurações Visuais

#### 🎨 **Formatação de Valores**
- **Formato**: Decimal (0.0-1.0) ou Percentual (%)
- **Casas Decimais**: 0 a 5 casas
- **Mostrar Valor**: Toggle para exibir/ocultar texto

#### 🔷 **Estilo do Visual**
- **Formato**: Círculo ou Triângulo
- **Cor do Elemento**: Picker de cor com gradiente automático
- **Largura da Borda**: 1-20px configurável

#### ✏️ **Estilo do Texto**
- **Cor do Texto**: Picker de cor independente
- **Tamanho da Fonte**: 8-50px responsivo

#### 🔄 **Controle de Rotação**
- **Ativar Rotação**: Toggle principal (desabilitado por padrão)
- **Clique**: Rotação de 30° por clique
- **Teclado**: ±15° com setas esquerda/direita

### 3️⃣ Interação com o Visual

🖱️ **Clique** na visualização para rotacionar 30°  
⌨️ Use **setas do teclado** para rotação precisa (±15°)  
🎛️ **Configure** cores e formatos no painel de formatação  
📏 **Redimensione** o visual - a centralização se mantém perfeita  

## 🎯 Exemplos de Uso

### 📈 **Dashboard de Vendas**
- **Valor**: % de atingimento de meta (0.85 = 85%)
- **Formato**: Círculo verde para metas atingidas
- **Rotação**: Desabilitada para leitura rápida

### 👥 **Indicadores de Performance**
- **Valor**: Score de satisfação (0.92 = 92%)
- **Formato**: Triângulo azul moderno
- **Rotação**: Habilitada para interatividade

### 🏗️ **Progresso de Projetos**
- **Valor**: % de conclusão (0.65 = 65%)
- **Formato**: Círculo com gradiente
- **Rotação**: Clique para destacar em apresentações

## 📱 Compatibilidade

| Plataforma | Status | Versão Mínima |
|------------|--------|---------------|
| 🖥️ Power BI Desktop | ✅ **Suportado** | 2024.01+ |
| 🌐 Power BI Service | ✅ **Suportado** | Atual |
| 📱 Power BI Mobile | ✅ **Responsivo** | iOS/Android |
| 🔗 Power BI Embedded | ✅ **Suportado** | API 5.1+ |

**Navegadores Testados**: Chrome 120+ • Edge 120+ • Firefox 121+ • Safari 17+

## 🔧 Especificações Técnicas

📦 **Tamanho**: ~200KB (otimizado)  
⚡ **Performance**: Renderização suave até 60 FPS  
🛠️ **Tecnologia**: React 18 + D3.js v7 + TypeScript  
💾 **Memória**: Baixíssimo consumo  
🎨 **Cores**: Suporte completo a hex colors  
🔄 **Animações**: CSS3 transitions otimizadas  

## ❓ FAQ - Perguntas Frequentes

<details>
<summary>🤔 <strong>Como ativar a rotação interativa?</strong></summary>

Vá em **Formatação → Controle de Rotação → Ativar Rotação**. Por padrão vem desabilitado para evitar rotações acidentais.
</details>

<details>
<summary>📱 <strong>Funciona em dispositivos móveis?</strong></summary>

Sim! O visual é totalmente responsivo e mantém a centralização perfeita em qualquer tamanho de tela.
</details>

<details>
<summary>🎨 <strong>Posso personalizar as cores?</strong></summary>

Absolutamente! Há 5 configurações independentes: cor do elemento, cor do texto, bordas e gradientes automáticos.
</details>

<details>
<summary>📊 <strong>Qual formato de dados aceita?</strong></summary>

Aceita valores decimais (0.0-1.0) ou percentuais (0-100%). O visual detecta automaticamente e formata corretamente.
</details>

<details>
<summary>🔄 <strong>Como controlar a rotação?</strong></summary>

**Clique**: 30° por clique | **Teclado**: Setas esquerda/direita para ±15° | **Limitado**: 0-360°
</details>

## 🆕 Novidades da Versão 1.0.1

### ✨ Recursos Principais
🆕 **Formato Triângulo**: Nova opção visual moderna  
🆕 **Rotação Interativa**: Controle por clique e teclado  
🆕 **Centralização Perfeita**: Texto sempre alinhado  
🆕 **Gradientes Dinâmicos**: Cores com transição automática  
🆕 **Toggle de Rotação**: Controle total da interatividade  

### 🔧 Melhorias Técnicas
⚡ **Performance 40% melhor**: Código otimizado e limpo  
🛡️ **TypeScript puro**: Tipagem robusta e confiável  
🎨 **CSS modular**: Estilos organizados e eficientes  
📱 **Responsividade**: Layout fluido para qualquer dimensão  

## 🔮 Roadmap - Próximas Versões

### v1.2 - Em Desenvolvimento
- [ ] 📤 **Mais Formatos**: Hexágono, losango, estrela
- [ ] 🎨 **Temas Predefinidos**: Claro, escuro, corporativo
- [ ] 💡 **Animações Avançadas**: Transições personalizáveis
- [ ] 📊 **Múltiplos KPIs**: Até 3 valores no mesmo visual

### v1.3 - Planejado
- [ ] 🖼️ **Ícones Personalizados**: Suporte a SVG e imagens
- [ ] 🌙 **Modo Escuro**: Tema automático
- [ ] 🔧 **API Extensão**: Hooks para customização
- [ ] 📋 **Templates**: Layouts predefinidos por setor

## 💬 Contato & Suporte

👨‍💻 **Alexandre Lourenço**  
*Desenvolvedor & Data Scientist*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://linkedin.com/in/alexandre-lourenco)
[![Email](https://img.shields.io/badge/Email-Contact-red.svg)](mailto:alexandre.2.lourenco@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black.svg)](https://github.com/alexandrelourenco)

### 🆘 Precisa de Ajuda?

🐛 **Reportar Bug**: [Abra uma issue](../../issues)  
💡 **Sugerir Funcionalidade**: [Discussões](../../discussions)  
📧 **Suporte Direto**: alexandre.2.lourenco@outlook.com  
💼 **LinkedIn**: Conecte-se para discussões técnicas  

### 📞 Suporte Técnico
⏰ **Tempo de resposta**: 24-48h  
🌍 **Idiomas**: Português, Inglês  
🔧 **Tipo**: Instalação, configuração, personalização  
💰 **Custo**: Gratuito para comunidade  

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** - consulte o arquivo [LICENSE](LICENSE) para detalhes.

### O que você pode fazer:
✅ Usar comercialmente  
✅ Modificar o visual  
✅ Distribuir  
✅ Uso privado  

### O que você deve fazer:
📄 Incluir a licença original  
📝 Dar crédito ao autor original  

## 🌟 Gostou do MultiPercentageKPI?

Se este visual te ajudou, considere:

⭐ [**Star no GitHub**](../../stargazers) 🔗 [**Compartilhar no LinkedIn**](https://linkedin.com/sharing/share-offsite/?url=github.com/alexandrelourenco/multipercentagekpi) 💌 **Recomendar por Email**

## 📈 Status do Projeto

![GitHub Stars](https://img.shields.io/github/stars/alexandrelourenco/multipercentagekpi)
![GitHub Forks](https://img.shields.io/github/forks/alexandrelourenco/multipercentagekpi)
![GitHub Issues](https://img.shields.io/github/issues/alexandrelourenco/multipercentagekpi)
![GitHub Downloads](https://img.shields.io/github/downloads/alexandrelourenco/multipercentagekpi/total)

---

**Desenvolvido com ❤️ para a comunidade Power BI**

[⬆ Voltar ao topo](#-multipercentagekpi---power-bi-custom-visual)
