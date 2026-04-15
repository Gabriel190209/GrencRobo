# 🤖 Robô de Limpeza para Calcinação em Fábrica de Cal

## 📌 Descrição do Projeto
Este projeto consiste no desenvolvimento de um **robô industrial automatizado** para atuar no processo de **limpeza de canais de calcinação** em uma fábrica de cal.

O sistema foi projetado para reduzir a exposição humana a ambientes agressivos, aumentar a eficiência operacional e padronizar o processo de limpeza.

---

## 🎯 Objetivos
- Automatizar a limpeza de canais de calcinação
- Reduzir esforço e risco para operadores humanos
- Aumentar a eficiência e repetibilidade do processo
- Permitir controle supervisionado pelo operador

---

## 🏗️ Estrutura do Robô

### 🚜 Base de Locomoção
- Sistema de movimentação por **esteiras**
- Dimensões reduzidas para operar em espaços confinados
- Segue uma **linha desenhada no chão** (sistema segue-linha)
- Movimentação ao redor de uma estrutura **cilíndrica (cuba)**

---

### 🔄 Plataforma Rotativa
- Estrutura superior rotativa semelhante à de um **tanque de guerra**
- Permite rotação do braço robótico para alcance lateral

---

### 🦾 Braço Robótico
- Dimensões compactas para manter estabilidade
- Movimentação **hidráulica**
- Apenas as articulações necessárias para a tarefa
- Sistema de troca de ferramentas automatizado (rosqueável)

---

### 🧰 Sistema de Módulos (Ferramentas)

O robô possui dois módulos principais acopláveis ao braço:

#### 🔓 Módulo de Destravamento de Tampa
- Estrutura semelhante a um **rolo de pintura metálico reforçado**
- Funções:
  - Impacto para destravar a tampa
  - Encaixe na estrutura da tampa
  - Movimento de alavanca para abertura
- Para fechamento:
  - Utiliza o lado oposto da ferramenta para travamento
  - Requer **intervenção humana parcial**

---

#### 🧹 Módulo de Limpeza
- Ferramenta no formato de **talhadeira (espátula reforçada)**
- Dimensão compatível com o diâmetro do canal
- Atua por **impacto mecânico** para remoção de crostas de cal

---

### 🧺 Suportes Laterais
- Dois compartimentos ("cestas") laterais
- Armazenamento dos módulos
- Permitem troca automática pelo braço robótico

---

## 🧠 Sistema de Controle

### 📱 Interface do Operador
- Computador de bordo móvel com **tela touch**
- Permite controle e monitoramento do robô

#### Funcionalidades:
- Definição da distância do braço até o canal
- Configuração da **cor da linha** a ser seguida
- Controle de posicionamento padrão
- Botões de:
  - ▶️ Iniciar
  - ⏸️ Pausar
  - ⛔ Parar (emergência)

---

### 📡 Comunicação
- Comunicação via **RF (Radiofrequência)**
- Estrutura:
  - Controle com adaptador USB + antena RF
  - Robô com microcontrolador embarcado + antena RF
- Comunicação direta (sem necessidade de internet)

---

## ⚙️ Funcionamento Geral

1. O robô segue a linha ao redor da cuba
2. Identifica pontos de parada (encruzilhadas da linha)
3. Alinha-se com o canal
4. Executa:
   - Destravamento da tampa
   - Abertura (com apoio humano)
   - Limpeza interna
   - Fechamento (com apoio humano)
5. Segue para o próximo ponto automaticamente

---

## 🤝 Intervenção Humana
Apesar da automação, algumas etapas exigem apoio do operador:
- Auxílio no manuseio da tampa
- Supervisão geral do processo
- Configuração inicial dos parâmetros

---

## 🛠️ Tecnologias Envolvidas

- Sistemas embarcados (microcontroladores)
- Comunicação RF
- Hidráulica industrial
- Automação e robótica
- Sensores para segue-linha
- Interface homem-máquina (HMI)

---

## ⚠️ Desafios do Projeto

- Operação em ambiente agressivo (cal e altas temperaturas)
- Estabilidade do robô em espaço reduzido
- Precisão no alinhamento com os canais
- Resistência mecânica das ferramentas
- Comunicação confiável via RF

---

## 🚀 Possíveis Melhorias Futuras

- Implementação de visão computacional
- Navegação autônoma mais avançada (sem linha)
- Monitoramento remoto via rede
- Feedback em tempo real (sensores de força/impacto)
- Integração com sistemas industriais (IoT)

---

## 📷 Ilustração Conceitual
*(Adicione aqui imagens ou diagramas do robô, se tiver)*

---

## 📄 Licença
Este projeto é de caráter acadêmico/experimental.

---
