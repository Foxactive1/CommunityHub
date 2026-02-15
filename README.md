
# 🏢 CommunityHub - Sistema de Gestão de Atividades Extensionistas

<div align="center">

![CommunityHub Logo](https://img.shields.io/badge/CommunityHub-v1.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/status-Protótipo-yellow?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Plataforma completa para gerenciamento de centros comunitários, atividades extensionistas e geração de relatórios acadêmicos alinhados com o ciclo PDCA.**

[Demo Online](#) • [Documentação](#-documentação) • [Reportar Bug](https://github.com/Foxactive1/communityhub/issues) • [Solicitar Feature](https://github.com/Foxactive1/communityhub/issues)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Características](#-características)
- [Tecnologias](#-tecnologias)
- [Instalação](#-instalação)
- [Uso](#-uso)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Módulos Principais](#-módulos-principais)
- [Metodologia PDCA](#-metodologia-pdca)
- [Roadmap](#-roadmap)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)
- [Contato](#-contato)
- [Agradecimentos](#-agradecimentos)

---

## 🎯 Sobre o Projeto

O **CommunityHub** é um sistema de gestão desenvolvido como parte das Atividades Extensionistas do curso de Análise e Desenvolvimento de Sistemas da Anhanguera Educacional. O projeto visa facilitar a administração de centros comunitários e ONGs através de uma plataforma digital moderna, intuitiva e alinhada com as diretrizes do Manual de Atividades Extensionistas.

### 📚 Contexto Acadêmico

- **Instituição:** Anhanguera Educacional
- **Curso:** Análise e Desenvolvimento de Sistemas (ADS)
- **Componente Curricular:** Atividades Extensionistas - 3° Semestre
- **Programa de Extensão:** Contexto à Comunidade / Ação Cultural / Inovação / Sustentabilidade
- **Alinhamento:** Resolução CNE/CES nº 7/2018

### 🎯 Objetivos

- ✅ Facilitar a gestão de centros comunitários e ONGs
- ✅ Organizar atividades sociais, culturais, esportivas e educacionais
- ✅ Automatizar a geração de relatórios extensionistas
- ✅ Implementar metodologia PDCA no gerenciamento de projetos
- ✅ Promover impacto social através da tecnologia
- ✅ Alinhar práticas acadêmicas com demandas reais da comunidade

---

## ✨ Características

### 🎨 Interface Moderna
- Design responsivo e mobile-first
- Gradientes e animações suaves
- Componentes Bootstrap 5.3.2
- Iconografia profissional (Bootstrap Icons)
- Paleta de cores consistente e acessível

### 📊 Dashboard Executivo
- Indicadores-chave de performance (KPIs)
- Gráficos interativos (Chart.js)
- Métricas de impacto social em tempo real
- Visualização de dados por categoria

### 🏢 Gestão de Centros Parceiros
- Cadastro completo de instituições
- Informações de contato e localização
- Vínculo com múltiplas atividades
- Sistema CRUD completo

### 🎭 Gestão de Atividades Extensionistas
- Categorização por programa de extensão
- Filtros avançados (categoria, centro, status)
- Cards visuais com informações detalhadas
- Badges de status e responsáveis

### 📅 Agenda Visual Inteligente
- Calendário semanal interativo
- Tabela de programação detalhada
- Indicadores visuais de eventos
- Informações de horário, local e responsável

### 📸 Galeria de Mídia
- Grid responsivo de imagens
- Upload de fotos e vídeos (simulado)
- Overlay com informações contextuais
- Organização por atividade

### 📄 Geração de Relatórios
- Timeline visual do ciclo PDCA
- Seleção de atividade e período
- Preview do relatório acadêmico
- Sistema de autoavaliação (0-10)
- Exportação em PDF e Excel (simulado)

### 🔒 Painel Administrativo
- Controle de acesso (simulado)
- Gerenciamento centralizado
- Operações CRUD em todas as entidades

---

## 🛠️ Tecnologias

O projeto utiliza as seguintes tecnologias e bibliotecas:

### Front-end
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada com gradientes e animações
- **JavaScript ES6+** - Interatividade e lógica de apresentação
- **Bootstrap 5.3.2** - Framework CSS responsivo
- **Bootstrap Icons 1.11.1** - Biblioteca de ícones

### Visualização de Dados
- **Chart.js 4.4.0** - Gráficos interativos (barras, pizza, linha)

### CDN Utilizados
```html
<!-- Bootstrap CSS -->
https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css

<!-- Bootstrap Icons -->
https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css

<!-- Chart.js -->
https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js

<!-- Bootstrap JS -->
https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js
```

---

## 🚀 Instalação

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional): Live Server, XAMPP, WAMP, ou similar
- Editor de código (recomendado): VS Code, Sublime Text

### Passo a Passo

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Foxactive1/communityhub.git
   ```

2. **Navegue até o diretório**
   ```bash
   cd communityhub
   ```

3. **Abra o arquivo principal**
   ```bash
   # Opção 1: Abrir diretamente no navegador
   open index_improved.html
   
   # Opção 2: Usar servidor local (VS Code Live Server)
   # Clique com botão direito em index_improved.html
   # Selecione "Open with Live Server"
   ```

4. **Acesse no navegador**
   ```
   http://localhost:5500/index_improved.html
   ```

### 📦 Sem Instalação

O projeto é 100% front-end e não requer instalação de dependências. Basta abrir o arquivo HTML em qualquer navegador moderno!

---

## 💻 Uso

### Navegação Principal

O sistema possui as seguintes seções principais acessíveis pelo menu de navegação:

1. **Dashboard** - Visualização geral de indicadores e métricas
2. **Centros** - Gestão de centros comunitários parceiros
3. **Atividades** - Gerenciamento de atividades extensionistas
4. **Agenda** - Programação semanal de eventos
5. **Galeria** - Acervo de fotos e vídeos das atividades
6. **Relatórios** - Geração de documentos acadêmicos

### Funcionalidades Principais

#### 📊 Dashboard
- Visualize 4 KPIs principais: Centros, Atividades, Participantes, Eventos
- Analise gráficos de distribuição por categoria
- Acompanhe métricas de impacto social

#### 🏢 Gestão de Centros
```
Botão "Novo Centro" → Cadastrar instituição parceira
Ações disponíveis:
  👁️ Visualizar - Ver detalhes completos
  ✏️ Editar - Alterar informações
  🗑️ Excluir - Remover centro
```

#### 🎭 Gestão de Atividades
```
Botão "Nova Atividade" → Cadastrar projeto extensionista
Filtros disponíveis:
  • Por categoria (Esporte, Cultura, Educação, Saúde)
  • Por centro parceiro
  • Por status (Ativa, Planejamento, Concluída)
```

#### 📄 Geração de Relatórios
```
1. Selecione a atividade
2. Escolha o período
3. Defina o tipo de relatório
4. Clique em "Gerar Relatório PDF"
5. Preencha a autoavaliação
6. Exporte o documento
```

---

## 📁 Estrutura do Projeto

```
communityhub/
│
├── index_improved.html          # Arquivo principal do protótipo
│
├── README.md                    # Documentação do projeto
│
├── docs/                        # Documentação adicional
│   ├── Relatório_extensionista.docx
│   └── SDD.pdf                  # Software Design Document
│
├── assets/                      # (Futuro) Recursos estáticos
│   ├── images/
│   ├── css/
│   └── js/
│
└── backend/                     # (Futuro) Implementação back-end
    ├── controllers/
    ├── models/
    ├── routes/
    └── database/
```

### 📂 Organização do Código HTML

```html
<!-- Estrutura Hierárquica -->
├── <head>
│   ├── Meta tags (SEO)
│   ├── Bootstrap CSS
│   ├── Bootstrap Icons
│   ├── Chart.js
│   └── Estilos personalizados
│
├── <body>
│   ├── Navbar (Navegação)
│   ├── Hero Section (Apresentação)
│   ├── Dashboard (Indicadores)
│   ├── Centros (Gestão)
│   ├── Atividades (Catálogo)
│   ├── Agenda (Calendário)
│   ├── Galeria (Mídia)
│   ├── Relatórios (PDCA)
│   ├── Footer (Rodapé)
│   └── Scripts (Bootstrap JS + Lógica)
```

---

## 🔧 Módulos Principais

### 1️⃣ Dashboard de Indicadores

**Localização:** `#dashboard`

**Componentes:**
- 4 Cards de Estatísticas (Centros, Atividades, Participantes, Eventos)
- Gráfico de barras - Atividades por Categoria
- Gráfico de pizza - Distribuição por Status

**Tecnologia:** Chart.js para visualização de dados

```javascript
// Exemplo de uso do Chart.js
new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Esporte', 'Cultura', 'Educação', 'Saúde'],
        datasets: [...]
    }
});
```

### 2️⃣ Sistema CRUD de Centros

**Localização:** `#centros`

**Funcionalidades:**
- ➕ Adicionar novo centro
- 👁️ Visualizar detalhes
- ✏️ Editar informações
- 🗑️ Excluir centro

**Dados Exibidos:**
- ID, Nome, Cidade/Estado, Telefone, E-mail, Número de Atividades

### 3️⃣ Gerenciador de Atividades

**Localização:** `#atividades`

**Categorias:**
- 🏃 Esporte (Badge azul)
- 🎨 Cultura (Badge roxo)
- 📚 Educação (Badge verde)
- 🏥 Saúde (Badge laranja)

**Filtros:**
- Por categoria de programa
- Por centro parceiro
- Por status de execução

### 4️⃣ Agenda Visual

**Localização:** `#agenda`

**Componentes:**
- Calendário semanal com indicadores
- Tabela detalhada de programação
- Informações de horário, local e responsável

### 5️⃣ Galeria de Mídia

**Localização:** `#galeria`

**Características:**
- Grid responsivo (CSS Grid)
- Efeito hover com overlay
- Integração com Unsplash (imagens de exemplo)
- Sistema de upload simulado

### 6️⃣ Gerador de Relatórios

**Localização:** `#relatorios`

**Metodologia PDCA:**
- **Plan (Planejar):** Cadastro e planejamento
- **Do (Fazer):** Execução e registro
- **Check (Verificar):** Análise de dados
- **Act (Agir):** Relatório final e melhorias

**Funcionalidades:**
- Seleção de atividade e período
- Preview do relatório acadêmico
- Sistema de autoavaliação
- Exportação PDF/Excel (simulado)

---

## 🔄 Metodologia PDCA

O CommunityHub implementa o ciclo PDCA em todo o fluxo de gestão:

### 📝 Plan (Planejar)
```
✓ Cadastro de centros parceiros
✓ Criação de atividades extensionistas
✓ Definição de objetivos e metas
✓ Configuração de metadados (SEO)
```

### ▶️ Do (Fazer)
```
✓ Registro de agenda e horários
✓ Upload de mídias (fotos/vídeos)
✓ Acompanhamento das atividades
✓ Documentação de processos
```

### ✅ Check (Verificar)
```
✓ Visualização de dados e métricas
✓ Análise de indicadores no Dashboard
✓ Checklist de conformidade
✓ Validação de resultados
```

### 🚀 Act (Agir)
```
✓ Geração do Relatório Final
✓ Autoavaliação do projeto
✓ Identificação de melhorias
✓ Exportação de documentos
```

---

## 🗺️ Roadmap

### Versão 1.0 (Atual) ✅
- [x] Protótipo front-end completo
- [x] Dashboard com indicadores
- [x] Interface de gestão de centros
- [x] Catálogo de atividades
- [x] Agenda visual
- [x] Galeria de mídia
- [x] Gerador de relatórios PDCA

### Versão 2.0 (Próxima) 🔜
- [ ] Implementação do back-end (Node.js + Express)
- [ ] Banco de dados PostgreSQL
- [ ] Sistema de autenticação JWT
- [ ] API RESTful completa
- [ ] Upload real de mídias (Cloudinary)
- [ ] Geração automática de PDF

### Versão 3.0 (Futuro) 💡
- [ ] Aplicativo mobile (React Native)
- [ ] Sistema de notificações
- [ ] Chat interno entre coordenadores
- [ ] Integração com redes sociais
- [ ] Dashboard analytics avançado
- [ ] Relatórios customizáveis
- [ ] Módulo financeiro
- [ ] Sistema de voluntários

### Melhorias Contínuas 🔧
- [ ] Testes unitários e integração
- [ ] CI/CD com GitHub Actions
- [ ] Documentação completa da API
- [ ] Acessibilidade (WCAG 2.1)
- [ ] Internacionalização (i18n)
- [ ] PWA (Progressive Web App)

---

## 🤝 Contribuindo

Contribuições são **bem-vindas** e fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição é **muito apreciada**.

### Como Contribuir

1. **Fork o projeto**
2. **Crie uma branch para sua feature**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit suas mudanças**
   ```bash
   git commit -m 'Add: nova funcionalidade incrível'
   ```
4. **Push para a branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Abra um Pull Request**

### 📝 Padrões de Commit

Utilizamos o padrão [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: adiciona nova funcionalidade
fix: corrige um bug
docs: atualiza documentação
style: formatação, ponto e vírgula, etc
refactor: refatoração de código
test: adiciona testes
chore: atualiza dependências
```

### 🐛 Reportando Bugs

Encontrou um bug? Abra uma [issue](https://github.com/Foxactive1/communityhub/issues) com:
- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs atual
- Screenshots (se aplicável)
- Ambiente (navegador, SO, versão)

### 💡 Sugerindo Melhorias

Tem uma ideia? Abra uma [issue](https://github.com/Foxactive1/communityhub/issues) com:
- Descrição detalhada da sugestão
- Motivação e casos de uso
- Exemplos de implementação (opcional)

---

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

```
MIT License

Copyright (c) 2026 Dione Castro Alves - InNovaIdeia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 📞 Contato

**Dione Castro Alves**  
Fundador da InNovaIdeia - Consultoria e Inovação

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dione-castro-alves)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Foxactive1)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:innovaideia2023@gmail.com)

**InNovaIdeia**  
Transformando desafios em soluções tecnológicas através de consultoria, desenvolvimento de software e treinamentos especializados.

### 🌐 Links do Projeto

- **Repositório:** [github.com/Foxactive1/communityhub](https://github.com/Foxactive1/communityhub)
- **Issues:** [github.com/Foxactive1/communityhub/issues](https://github.com/Foxactive1/communityhub/issues)
- **Documentação:** [Em breve]
- **Demo Online:** [Em breve]

---

## 🙏 Agradecimentos

Este projeto não seria possível sem:

- **Anhanguera Educacional** - Pela oportunidade de desenvolver este projeto extensionista
- **Professor/Tutor Orientador** - Pela orientação acadêmica
- **Centros Comunitários Parceiros** - Pela inspiração e feedback valioso
- **Bootstrap Team** - Pelo excelente framework CSS
- **Chart.js Team** - Pela biblioteca de visualização de dados
- **Unsplash** - Pelas imagens de alta qualidade
- **Comunidade Open Source** - Pela inspiração constante

### 🎓 Recursos e Referências

- [Manual de Atividades Extensionistas](https://www.anhanguera.com)
- [Resolução CNE/CES nº 7/2018](http://portal.mec.gov.br)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/)
- [Chart.js Documentation](https://www.chartjs.org/docs/)
- [MDN Web Docs](https://developer.mozilla.org/)

### 🌟 Inspirações

- Projetos sociais brasileiros de impacto
- Metodologias ágeis e gestão por processos
- Design thinking aplicado à inovação social
- Tecnologia como ferramenta de transformação

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela!

**Desenvolvido com ❤️ por [Dione Castro Alves](https://github.com/Foxactive1)**

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-💚-green?style=for-the-badge)
![Community](https://img.shields.io/badge/Community-🤝-blue?style=for-the-badge)

---

**CommunityHub** © 2026 | Atividades Extensionistas - 3° Semestre ADS

</div>
