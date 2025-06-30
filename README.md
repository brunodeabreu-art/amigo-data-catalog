# AmigoTech Data Catalog

Sistema de catálogo de dados com autenticação baseado em Data Mesh principles para plataforma de análise de dados da AmigoTech.

## 🚀 Demo

Acesse o sistema em: [https://brunodeabreu-art.github.io/amigo-data-catalog/](https://brunodeabreu-art.github.io/amigo-data-catalog/)

## 🔐 Credenciais de Acesso

Use as seguintes credenciais para acessar o sistema:

| Usuário | Senha              | Perfil        |
|---------|-------------------|---------------|
| `root`  | `8dfds7j2skas##$a` | Administrador |

## 📋 Funcionalidades

### 🏠 Página Principal (index.html)
- Sistema de login com autenticação
- Interface terminal/console moderna
- Validação de credenciais
- Controle de sessão (8 horas)
- Redirecionamento automático

### 📊 Catálogo de Dados (data-catalog-complete.html)
- **Data Mesh Principles**: Visualização dos 4 princípios fundamentais
- **Governance Dashboard**: Métricas de qualidade e governança
- **Hierarchy View**: Organização por domínios (Business, Product, Tech Data)
- **Data Products**: 50+ produtos de dados catalogados
- **Canvas Técnico**: Especificações detalhadas de arquitetura
- **Search**: Busca por produtos, tipos e tags
- **User Management**: Exibição do usuário logado e logout

### 🏗️ Diagrama de Arquitetura (architecture-diagram.html)
- **Data Mesh Principles**: Implementação detalhada
- **Pipeline Architecture**: Fluxo end-to-end de dados
- **Enterprise Layers**: Arquitetura em 4 camadas
- **Technology Stack**: Stack completo com tecnologias específicas
- **Governance Framework**: Componentes de governança
- **Visual Diagrams**: Diagramas interativos da arquitetura
- **Market Benchmarking**: Comparação com empresas líderes
- **Maturity Assessment**: Avaliação de maturidade Data Mesh

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5/CSS3**: Interface responsiva
- **JavaScript ES6+**: Lógica de aplicação
- **LocalStorage**: Gerenciamento de sessão
- **CSS Grid/Flexbox**: Layout responsivo

### Data Architecture
- **Apache Kafka**: Streaming de dados
- **PostgreSQL**: Banco relacional
- **MongoDB**: Banco NoSQL
- **Amazon Redshift**: Data warehouse
- **Kubernetes**: Orquestração de containers
- **AWS**: Infraestrutura cloud

### Monitoring & Observability
- **CloudWatch**: Monitoramento AWS
- **Prometheus/Grafana**: Métricas e dashboards
- **Datadog**: APM e observabilidade

## 🏛️ Arquitetura do Sistema

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Login Page    │───▶│  Data Catalog    │───▶│  Architecture   │
│   (index.html)  │    │   (complete)     │    │   Diagrams      │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         │                        │                        │
         ▼                        ▼                        ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│ Authentication  │    │ Data Products    │    │   Data Mesh     │
│   Management    │    │    Canvas        │    │  Architecture   │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

## 📁 Estrutura de Arquivos

```
amigo-data-catalog/
├── index.html                    # Página de login principal
├── data-catalog-complete.html    # Catálogo completo de dados
├── architecture-diagram.html     # Diagramas de arquitetura
├── login.html                   # Template de referência
├── amigo-tech-data-mesh.json    # Dados do Data Mesh
└── README.md                    # Este arquivo
```

## 🔒 Segurança

- **Session Management**: Controle de sessão com timeout de 8 horas
- **Authentication**: Validação de credenciais no frontend
- **Auto-logout**: Limpeza automática de sessão expirada
- **Redirect Protection**: Redirecionamento para login se não autenticado

## 📱 Responsividade

O sistema é totalmente responsivo e funciona em:
- 💻 **Desktop**: Layout completo com todas as funcionalidades
- 📱 **Mobile**: Interface adaptada para dispositivos móveis
- 📟 **Tablet**: Experiência otimizada para tablets

## 🚀 Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/brunodeabreu-art/amigo-data-catalog.git
cd amigo-data-catalog
```

2. Sirva os arquivos usando um servidor web local:
```bash
# Python 3
python -m http.server 8000

# Node.js (se tiver http-server instalado)
npx http-server

# PHP
php -S localhost:8000
```

3. Acesse `http://localhost:8000` no navegador

## 🌟 Características Técnicas

### Data Products Canvas
- **12 Seções Técnicas**: North Star, Architecture, APIs, Schema, SLOs, Infrastructure, Security, Pipeline, Monitoring, ML Models, Performance, Integrations
- **Especificações Reais**: Métricas detalhadas, tecnologias específicas, configurações de infraestrutura
- **Layout Responsivo**: Grid de 3 colunas adaptável

### Governança de Dados
- **Métricas de Qualidade**: 94.2% de qualidade geral
- **Compliance**: LGPD, SOX, HIPAA
- **SLA Tracking**: 99.5% de uptime
- **Data Lineage**: Rastreamento completo

### Performance
- **50+ Data Products**: Catalogados e documentados
- **3 Domínios**: Business, Product, Tech Data
- **Real-time Metrics**: Processamento de 2.5TB/dia
- **12+ Domain Teams**: Times distribuídos

## 📄 Licença Nota

Este é um projeto de demonstração para fins educacionais e de portfólio.

---

**Desenvolvido por**: Bruno de Abreu  
**Data**: 2024  
**Tecnologia**: Data Mesh Architecture & Modern Web Technologies 