### Projeto PlasticPurge: Embarcação Autônoma para Remoção Sustentável de Microplásticos nos Oceanos

O **PlasticPurge** é uma embarcação autônoma inovadora e sustentável, destinada a identificar, coletar e processar microplásticos nos oceanos. Ao combinar tecnologias avançadas de detecção e coleta com soluções de reaproveitamento e filtragem, o projeto visa promover a saúde dos ecossistemas marinhos e contribuir para a Economia Azul sustentável.

#### **Objetivos do Projeto:**
1. **Identificação de Plásticos:**
   - **Sensores Avançados:** Utilização de câmeras de alta resolução e espectroscopia de infravermelho para detectar e identificar microplásticos na água.
   - **Machine Learning:** Implementação de algoritmos de aprendizado de máquina para diferenciar plásticos de outros elementos marinhos, como peixes e plantas aquáticas.

2. **Sistemas de Coleta:**
   - **Sensores Ultrassônicos:** Serão utilizados para medir a distância dos plásticos identificados e coordenar a coleta eficiente.
   - **Garras e Redes Submersíveis:** Desenvolver garras robóticas e redes submersíveis que possam ser lançadas e recolhidas automaticamente para capturar microplásticos em várias profundidades.

3. **Processamento a Bordo:**
   - **Separação e Reaproveitamento:** Desenvolvimento de sistemas para separar plásticos de outros tipos de lixo. Utilizar os plásticos coletados para a construção de novas embarcações, promovendo ainda mais sustentabilidade em nosso projeto.
   - **Compactação e Armazenamento:** Criar sistemas de compactação para reduzir o volume dos plásticos coletados, facilitando o armazenamento.

4. **Filtragem e Devolução da Água:**
   - **Tecnologia de Filtragem:** Permite devolver água limpa ao oceano após a remoção de microplásticos realizada pelo equipamento.

5. **Autonomia e Eficiência Energética:**
   - **Fontes de Energia Renováveis:** Equipar a embarcação com painéis solares afim de garantir um abastecimento contínuo de energia.
   - **Inteligência Artificial:** Utilizar IA para otimizar rotas de coleta, maximizando a eficiência energética e a cobertura das áreas afetadas.

6. **Monitoramento e Relatórios em Tempo Real:**
   - **Transmissão de Dados:** Incorporar sistemas de transmissão de dados via satélite para monitoramento remoto e relatórios em tempo real das operações.
   - **Plataforma Online:** Criar uma plataforma online onde os dados coletados possam ser visualizados por pesquisadores e o público em geral, promovendo transparência e colaboração.
   - **Sistema Operacional de Tempo Real (RTOS):** Utilização de sistemas de tempo real rígido (crítico) para garantir a confiabilidade do monitoramento e funcionamento do nosso equipamento em alto mar.


#### **Detalhamento Técnico:**

##### **1. Ferramentas de Machine Learning/IA:**
- **Coleta de Dados:**
  - **Imagem e Vídeo:** Captura de imagens e vídeos subaquáticos utilizando câmeras de alta resolução.
  - **Espectroscopia de Infravermelho:** Analise da composição dos objetos identificados para distinguir entre plásticos e materiais orgânicos.

- **Treinamento de Modelos:**
  - **Redes Neurais Convolucionais (CNNs):** Utilização de CNNs para análise de imagens, treinadas com um grande conjunto de dados de imagens de plásticos, peixes e outros materiais marinhos.
  - **Transferência de Aprendizado:** Aplicação de modelos pré-treinados em grandes conjuntos de dados de imagem para acelerar o processo de treinamento e melhorar a precisão.

- **Algoritmos de Detecção e Classificação:**
  - **YOLO (You Only Look Once):** Implementação do software YOLO para detecção em tempo real de objetos subaquáticos, permitindo a identificação rápida de plásticos.
  - **Segmentação Semântica:** Utilização de técnicas de segmentação para identificar a localização exata dos plásticos na imagem e diferenciá-los de outros objetos.

##### **2. Sistemas de Coleta:**
- **Garras Robóticas:**
  - **Desenvolvimento:** Criação de garras robóticas equipadas com sensores de pressão para manipular plásticos sem danificar a vida marinha.
  - **Controle:** Desenvolvimento de algoritmos de controle de movimento baseados em IA para coordenar a coleta precisa dos plásticos identificados.

- **Redes Submersíveis:**
  - **Desenho:** Utilização de redes submersíveis com malhas finas para capturar microplásticos em diferentes profundidades.
  - **Mecanismo de Lançamento e Recolhimento:** Implementação de um sistema automatizado para lançar e recolher as redes, integrado aos sensores ultrassônicos para otimizar a coleta.

##### **3. Processamento e Reaproveitamento de Plásticos:**
- **Separação:**
  - **Técnicas de Flotação:** Uso de técnicas de flotação para separar plásticos de outros materiais capturados.
  - **Classificação:** Uso de classificação automatizadas para separar diferentes tipos de plásticos.

- **Compactação:**
  - **Compactadores:** Desenvolvimento de compactadores para reduzir o volume dos plásticos coletados, facilitando o armazenamento e transporte.

- **Reaproveitamento:**
  - **Reprocessamento:** Implementação de sistemas de reprocessamento a bordo que transformem os plásticos em materiais utilizáveis para a construção de novas embarcações.
  - **Impressão 3D:** Uso de impressoras 3D para criar componentes de novas embarcações a partir dos plásticos reciclados, fechando o ciclo de sustentabilidade.

#### **Implementação Técnica:**
- **Integração de Sensores:** Sensores ópticos e ultrassônicos serão integrados à embarcação para a detecção precisa e coleta eficiente dos microplásticos.
- **Algoritmos de Machine Learning:** Algoritmos treinados em dados coletados de ambientes marinhos ajudarão a embarcação a diferenciar entre plásticos, lixo e vida marinha.
- **Sistemas de Energia Renovável:** Painéis solares fornecerão energia, garantindo operações sustentáveis a longo prazo.

-------------------------------------------------------------------------

#### **Detalhes do Projeto:**
Projeto desenvolvido para o desafio proposto em nossa Global Solution pela FIAP junto com a Unesco, O20 e outros parceiros.
Link para mais informações: https://www.fiap.com.br/graduacao/global-solution/

**Membros do Projeto:**
- Bianca Fioretti dos Santos (RM96019)
- Gustavo Kenzo Abe (RM 93944)
- Greidimar Ferreira Lagares (RM 93827)

-------------------------------------------------------------------------

**Arquivos do Projeto:**
-Microplastic.ipynb
Código desenvolvido para a matéria Inteligência Artificial e Computacional ministrada pelo professor André Tritiack.

O grupo deve escolher um conjunto de dados abrangente contendo dados tabulares relevantes à poluição plástica. A avaliação dos modelos deve se basear nas principais métricas relacionadas à técnica de Machine Learning escolhida (Classificação ou Regressão).

Dataset utilizado: Global Microplastic Initiative by Adventure Scientists
Links: https://www.adventurescientists.org/microplastics.html; https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.nodc:0211009
