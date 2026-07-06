# 📊 Rastreador de Respostas CXA - Torre de Controle

Sistema web de rastreamento de respostas de CXAs (Customer Experience Advocates) da rede de concessionários Mercedes-Benz.

## ✨ Funcionalidades

- 📅 **Calendário Interativo**: Marque dias úteis para rastrear respostas
- 🔍 **Busca Inteligente**: Procure CXAs por concessionário, cidade ou estado
- 📊 **Tabela Consolidada**: Visualize resumo de todos os CXAs com taxa de resposta
- 💾 **Armazenamento Local**: Dados salvos no navegador (localStorage)
- 📥 **Exportação**: Exporte dados em TXT e CSV
- 🗑️ **Deleção Segura**: Com confirmação e histórico mantido
- 🌙 **Design Dark**: Interface corporativa com verde florescente

## 🚀 Como Usar Localmente

1. **Baixe o arquivo** `index.html`
2. **Abra em seu navegador** (duplo clique ou arrastar para o navegador)
3. **Comece a usar!** - Selecione um CXA e marque os dias

## 📁 Estrutura de Arquivo

```
rastreador-cxa/
├── index.html           # Arquivo principal (abra este arquivo)
└── README.md           # Este arquivo
```

## 🌐 Hospedar no GitHub Pages

### Passo 1: Criar um Repositório GitHub

1. Acesse [github.com](https://github.com)
2. Clique em "**New**" para criar um novo repositório
3. Nome do repositório: `rastreador-cxa` (ou qualquer nome)
4. Descrição: "Sistema de rastreamento de respostas CXA"
5. Clique em "**Create repository**"

### Passo 2: Upload dos Arquivos

**Opção A - Via GitHub Web:**

1. No repositório, clique em "**Add file**" → "**Upload files**"
2. Arraste os arquivos (`index.html` e `README.md`) para a área
3. Clique em "**Commit changes**"

**Opção B - Via Git (terminal):**

```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/rastreador-cxa.git
cd rastreador-cxa

# Copie os arquivos para a pasta
# (Coloque index.html e README.md aqui)

# Faça commit
git add .
git commit -m "Adicionar Rastreador CXA"
git push origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** (⚙️)
2. Desça até **"Pages"** (no menu esquerdo)
3. Em **"Source"**, selecione **"main"** branch
4. Em **"Folder"**, selecione **"/ (root)"**
5. Clique em **"Save"**

### Passo 4: Acessar o Site

Após alguns minutos, seu site estará disponível em:
```
https://SEU_USUARIO.github.io/rastreador-cxa
```

**Substitua:**
- `SEU_USUARIO` → Seu nome de usuário GitHub
- `rastreador-cxa` → Nome do seu repositório (se diferente)

## 📋 Dados do Sistema

### CXAs Integrados

O sistema possui **34 CXAs** da rede Mercedes-Benz:
- **Rodobens** (6 unidades)
- **Ingá** (9 unidades)
- **Mardisa Veículos** (8 unidades)
- **Minas Máquinas** (4 unidades)
- **Mecasul/Savar** (2 unidades)
- **Vitória Diesel** (1 unidade)
- **Savana** (1 unidade)
- **Mallon** (1 unidade)
- **Prodoeste** (2 unidades)

### Armazenamento de Dados

- **Localização**: Navegador (localStorage)
- **Dados Salvos**: Seleção de CXA + Marcações de dias
- **Persistência**: Dados permanecem mesmo após fechar o navegador
- **Limite**: ~5MB por domínio

## 🎯 Guia de Uso

### 1. Selecionar um CXA

- Digite o nome do concessionário, cidade ou estado na aba "Buscar CXA"
- Clique na sugestão para selecionar
- Os campos se preenchem automaticamente

### 2. Marcar Dias

- Clique nos dias úteis (seg-sex) do calendário
- Dias de fim de semana são desabilitados
- Dados são salvos automaticamente

### 3. Controles do Calendário

- **✓ Marcar Tudo**: Marca todos os dias do mês
- **✕ Limpar Tudo**: Remove todas as marcações (com confirmação)
- **💾 Salvar Dados**: Força a gravação (feito automaticamente)

### 4. Tabela Consolidada

- Mostra resumo de TODOS os CXAs com dados
- Colunas: Concessionário, Cidade, Estado, Responsável, Status, Taxa de Resposta
- Marque linhas para deletar múltiplos registros

### 5. Exportar Dados

- **📊 Exportar Tabela (Excel)**: CSV com resumo consolidado
- **📝 Exportar em TXT**: Relatório do CXA selecionado

### 6. Deletar Dados

- Marque a linha na tabela consolidada
- Clique **"🗑️ Deletar Selecionados"**
- Confirme na modal
- Histórico de outros meses é mantido

## 🎨 Design

- **Tema**: Dark mode com verde florescente
- **Cores**: #0f1419 (fundo) + #00ff6a (accent)
- **Fonte**: Segoe UI (corporativo)
- **Responsividade**: Funciona em desktop, tablet e mobile

## 🔒 Privacidade & Segurança

- ✅ Dados armazenados LOCALMENTE no navegador
- ✅ Nenhum servidor recebe informações
- ✅ Sem cookies de rastreamento
- ✅ Sem login necessário
- ⚠️ Limpar histórico do navegador apaga os dados

## 🐛 Resolução de Problemas

### "Dados não estão salvando"
- Verifique se o localStorage está habilitado
- Limpe o cache e recarregue a página

### "Não consigo deletar uma linha"
- Marque a linha na tabela consolidada (checkbox esquerdo)
- Aguarde alguns segundos para a interface atualizar
- Clique em "Deletar Selecionados"

### "CXA não aparece na busca"
- Digite partes do nome (concessionário, cidade ou estado)
- Use minúsculas ou maiúsculas indistintamente
- Remova espaços extras

## 📞 Suporte

Para relatar bugs ou sugerir melhorias:
1. Abra uma **Issue** no repositório GitHub
2. Descreva o problema e como reproduzir
3. Inclua screenshots se possível

## 📄 Licença

Sistema de uso interno - Mercedes-Benz Caminhões e Ônibus

---

**Versão**: 1.0.0  
**Data**: Julho 2026  
**Desenvolvido para**: Torre de Concessionários - CXA Program
