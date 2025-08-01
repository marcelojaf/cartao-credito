# 💳 Análise de Gastos do Cartão de Crédito

Dashboard interativo para análise de gastos do cartão de crédito C6 Carbon, desenvolvido para Marcelo Jose Amador Filho.

## 🚀 Funcionalidades

- **📊 Dashboard Resumo**: Visão geral dos gastos com métricas principais
- **📈 Gráficos Interativos**: 
  - Gráfico de pizza mostrando distribuição por categoria
  - Gráfico de barras com top 10 categorias
- **🔍 Detalhamento Expandível**: Clique em qualquer categoria para ver transações individuais
- **📱 Design Responsivo**: Funciona perfeitamente em desktop e mobile
- **⚡ Performance**: Carregamento rápido com separação de arquivos

## 📁 Estrutura do Projeto

```
C:\dev\cartao-credito\
├── index.html              # Página principal
├── FaturaCPF.xls           # Arquivo Excel original (fonte)
├── data/
│   └── transactions.json   # Dados processados em JSON
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos da aplicação
│   └── js/
│       └── dashboard.js    # Lógica da aplicação
└── README.md               # Este arquivo
```

## 🎯 Como Usar

1. **Abrir o Dashboard**:
   - Navegue até `C:\dev\cartao-credito\`
   - Abra o arquivo `index.html` em qualquer navegador moderno

2. **Explorar os Dados**:
   - Visualize o resumo nos cards superiores
   - Analise os gráficos de pizza e barras
   - **Clique em qualquer categoria** na seção "Detalhamento por Categoria" para expandir e ver as transações individuais

3. **Navegação**:
   - **F5** ou **Ctrl+R**: Atualizar dados
   - **Responsivo**: Use em qualquer dispositivo

## 📊 Dados Analisados

### Resumo dos Gastos (Junho/Julho 2025)
- **Total Gasto**: R$ 8.270,65
- **Transações**: 61
- **Ticket Médio**: R$ 135,50
- **Categorias**: 13

### Top 5 Categorias
1. **Supermercados/Mercearias** - R$ 2.031,99 (24,6%)
2. **Restaurantes/Bares** - R$ 1.824,57 (22,1%)
3. **Serviços Pessoais** - R$ 846,33 (10,2%)
4. **Serviços Profissionais** - R$ 755,30 (9,1%)
5. **T&E** - R$ 688,72 (8,3%)

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Design moderno com gradientes e animações
- **JavaScript ES6+**: Lógica de interação e manipulação de dados
- **Chart.js**: Biblioteca para gráficos interativos
- **JSON**: Formato de dados estruturados

## 🎨 Características do Design

- **Tema Moderno**: Gradientes suaves e glassmorphism
- **Animações Suaves**: Transições de 0.3s para interações
- **Cores Acessíveis**: Paleta otimizada para legibilidade
- **Typography**: Fonte Segoe UI para melhor legibilidade
- **Cards Interativos**: Hover effects e shadows

## 🔧 Personalização

### Atualizando os Dados
1. Substitua o arquivo `data/transactions.json` com novos dados
2. Mantenha a mesma estrutura JSON
3. Pressione F5 para recarregar

### Modificando Estilos
- Edite `assets/css/style.css` para personalizar aparência
- Use variáveis CSS para mudanças globais

### Adicionando Funcionalidades
- Modifique `assets/js/dashboard.js`
- A classe `CreditCardDashboard` é extensível

## 📱 Compatibilidade

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers

## 🐛 Solução de Problemas

### Gráficos não aparecem
- Verifique se está acessando via HTTP/HTTPS (não file://)
- Verifique conexão com internet (Chart.js CDN)

### Dados não carregam
- Verifique se `data/transactions.json` existe
- Verifique estrutura do JSON
- Abra o Console do navegador (F12) para ver erros

### Layout quebrado
- Verifique se `assets/css/style.css` está no local correto
- Teste em navegador atualizado

## 📈 Próximas Melhorias

- [ ] Filtros por período
- [ ] Comparação entre meses
- [ ] Exportar relatórios em PDF
- [ ] Gráfico de evolução temporal
- [ ] Alertas de gastos excessivos
- [ ] Categorização automática

## 📧 Suporte

Para dúvidas ou sugestões sobre este dashboard, consulte a documentação ou analise o código-fonte comentado.

---

**Desenvolvido com ❤️ para análise inteligente de gastos**