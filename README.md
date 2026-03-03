# 🍄 Selene - Detecção de Fungos Parasitas em Cogumelos usando Aprendizagem Profunda

[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Computer%20Vision-blue)](https://pytorch.org/)
[![IoT](https://img.shields.io/badge/IoT-Sensors-green)](https://www.arduino.cc/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://python.org)

## 📋 Visão Geral

Sistema inteligente de monitoramento para cultivo de cogumelos **shimeji** que integra **visão computacional** e **Internet das Coisas** para detecção precoce de fungos parasitas. Desenvolvido para auxiliar produtores da região do **Vale do Ribeira** no controle e prevenção de contaminações em tempo real.

## 🎯 Objetivo

> Desenvolver um sistema inteligente de monitoramento para o cultivo de cogumelos, utilizando sensores ambientais e inteligência artificial, a fim de prevenir infecções e infestações por parasitas, proporcionando maior controle, segurança e produtividade ao produtor.

## ✨ Funcionalidades Principais

### 🔍 Monitoramento por Visão Computacional
- **Captura contínua** de vídeos em todos os estágios do cultivo
- **Conversão automática** para imagens (1024×760 pixels)
- **Detecção em tempo real** de fungos parasitas usando Deep Learning
- **Base de treinamento** com mais de 2.000.000 de frames
- **Estimativa probabilística** de ocorrência de contaminação

### 📱 Aplicação Mobile
- **Dashboard em tempo real** com métricas do cultivo
- **Alertas personalizados** e notificações push
- **Monitoramento** de temperatura e umidade
- **Relatórios consolidados** e histórico de eventos

### 🌡️ Sistema IoT Integrado
- **Sensores ambientais** de temperatura e umidade
- **Controle automático** das condições da estufa
- **Alertas para variações críticas**
- **Integração completa** com a plataforma de IA

## 🏗️ Arquitetura do Sistema

### Componentes Principais

| Módulo | Tecnologia | Função |
|--------|------------|--------|
| **Captura Visual** | Câmeras HD | Gravação contínua do cultivo |
| **Processamento** | Python + OpenCV | Conversão vídeo→imagens |
| **IA** | Deep Learning | Detecção de padrões e anomalias |
| **IoT** | Sensores + Microcontroladores | Monitoramento ambiental |
| **Backend** | API REST | Integração dos sistemas |
| **Frontend** | Mobile + Desktop | Interfaces do usuário |

### Fluxo de Dados

```
Câmeras → Conversão → Análise IA → Alertas → Ação
    ↓         ↓           ↓         ↓        ↓
 Gravação   Frames    Detecção  Mobile   Produtor
 Contínua  (1024×760)  Pattern  App      Intervém
```

## 🎯 Metas Técnicas

- **✅ Acurácia do modelo**: > 50%
- **✅ Taxa de falsos positivos**: < 10%
- **✅ Processamento**: 60 frames/minuto
- **✅ Detecção de padrões** morfológicos complexos
- **✅ Análise de variações** de coloração e textura

## 🛠️ Tecnologias Utilizadas

### Inteligência Artificial
- **PyTorch/TensorFlow** - Frameworks de Deep Learning
- **OpenCV** - Processamento de imagens
- **Redes Neurais Convolucionais** - Detecção de padrões visuais

### Infraestrutura
- **Python 3.8+** - Linguagem principal
- **Arduino/Raspberry Pi** - Sensores IoT
- **Banco de Dados NoSQL** - Armazenamento de imagens
- **API REST** - Comunicação entre módulos

### Aplicações
- **React Native/Flutter** - App Mobile
- **Electron/Qt** - App Desktop
- **Docker** - Containerização

## 📁 Estrutura do Projeto

```
project-root/
│
├── 📱 mobile-app/          # Aplicação mobile
├── 🖥️ desktop-app/         # Aplicação desktop
├── 🔬 ai-model/           # Modelos de IA
│   ├── training/
│   ├── inference/
│   └── datasets/
├── 🌐 backend-api/        # API e servidores
├── 🔌 iot-sensors/        # Código dos sensores
├── 📊 docs/              # Documentação
└── 📋 tests/             # Testes automatizados
```

## 📊 Resultados Esperados

### Para Produtores
- **🔻 Redução de 30%** nas perdas por contaminação
- **⏰ Monitoramento 24/7** automático
- **🚨 Alertas precoces** para intervenção
- **💡 Otimização** do manejo produtivo

### Impacto Regional
- **💪 Fortalecimento** da produção no Vale do Ribeira
- **🌱 Sustentabilidade** na fungicultura
- **🎯 Alinhamento com ODS 2** (Fome Zero)

## 👥 Equipe

| Integrante | Função | Contato |
|------------|--------|---------|
| **Bruno de Lucca Soares Miranda** | Backend & Documentação | [![GitHub](https://img.shields.io/badge/GitHub-BDlucca-black)](https://github.com/BDlucca) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue)](https://linkedin.com/in/seu-linkedin) |
| **Filipe de Oliveira Lima** | Frontend & Mobile | [![GitHub](https://img.shields.io/badge/GitHub-1filipeolv-black)](https://github.com/1filipeolv) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue)](https://www.linkedin.com/in/filipeolv/) |
| **Lucas de Barros Parada** | Banco de dados & Documentação | [![GitHub](https://img.shields.io/badge/GitHub-LucasBParada-black)](https://github.com/LucasBParada) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue)]([https://linkedin.com/in/seu-linkedin](https://www.linkedin.com/in/lucas-parada-943467321/)) |
| **Paulo Seiji Yamamoto Junior** | Full-stack | [![GitHub](https://img.shields.io/badge/GitHub-Psyj1-black)](https://github.com/Psyj1) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue)](www.linkedin.com/in/paulo-junior-921676321) |

## 📄 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

<div align="center">

**Desenvolvido com ❤️ para o cultivo sustentável de shimeji no Vale do Ribeira**

*Tecnologia a serviço da agricultura familiar*

</div>

