# Projeto de Instalações Elétricas Industriais — Fábrica de Injeção de Plásticos

<p align="center">
  <img src="https://img.shields.io/badge/Categoria-Projeto%20Académico-blue" alt="Categoria: Projeto Académico">
  <img src="https://img.shields.io/badge/Software-AutoCAD-C81F2E?logo=autodesk" alt="Software: AutoCAD">
  <img src="https://img.shields.io/badge/Software-DIALux-005A9B" alt="Software: DIALux">
</p>

> [Projeto Académico] Projeto completo de instalações elétricas e licenciamento (DGEG ) para uma fábrica de injeção de plásticos, incluindo cálculo de potências (~700kVA), estudo luminotécnico (DIALux), esquemas em AutoCAD e dimensionamento de proteções (sistema TT).

---

## Índice

- O Enunciado e o Objetivo Técnico
- Arquitetura do Sistema: Alimentação, Distribuição e Proteções
- Metodologia de Projeto e Ferramentas Utilizadas
- Soluções Técnicas Implementadas
- Integração e Fluxo de Trabalho
- Resultados Técnicos, Conformidade e Dificuldades
- Conclusão e Aprendizados Técnicos
- Documentação do Projeto (Peças Escritas e Desenhadas)
- Licença

---

### 1. O Enunciado e o Objetivo Técnico

Este projeto integrado foi desenvolvido no âmbito da unidade curricular de **Projeto de Instalações Elétricas (PIIE)**, inserido no plano de estudos do CTeSP de Instalações Elétricas, na ESTGA – Universidade de Aveiro, no ano letivo de 2022/2023.

O objetivo central foi elaborar o **projeto elétrico completo de uma unidade industrial**, abrangendo desde a avaliação da potência elétrica previsível até à elaboração das peças escritas e desenhadas necessárias para licenciamento perante a **DGEG (Direção-Geral de Energia e Geologia)**.

As especificações técnicas obrigatórias incluíam:
- Avaliação da potência elétrica previsível com base nas máquinas da fábrica.
- Projeto luminotécnico de todos os espaços, utilizando software específico.
- Elaboração das **Peças Escritas**: Memória descritiva e justificativa, fichas de caracterização (MT/AT, Rede BT, Instalação de BT) e cálculos justificativos.
- Elaboração das **Peças Desenhadas**: Plantas de localização, traçado de caminhos de cabos, localização de quadros, diagrama da rede e esquemas elétricos de princípio (ELP).
- Preenchimento de documentação de licenciamento: Ficha Eletrotécnica, Termo de Responsabilidade e Identificação do Projeto.

### 2. Arquitetura do Sistema: Alimentação, Distribuição e Proteções

A estrutura do projeto é definida pelo sistema de alimentação e distribuição, concebido para garantir continuidade, segurança e eficiência.

- **Posto de Transformação (PT):** A fábrica é alimentada por uma linha subterrânea de 15 kV (neutro solidamente à terra, potência de curto-circuito de 350 MVA). O PT é uma cabine baixa pré-fabricada, com celas de MT, transformador e o Quadro Principal de Transformação (QPT).

- **Quadro Geral de Baixa Tensão (QGBT):** A partir do QPT, a energia é distribuída pelo QGBT, que alimenta:
  - 7 quadros parciais (QP1 a QP7) para força e tomadas.
  - 1 quadro independente para iluminação (QPI).
  - 1 Quadro Geral de Mobilidade (QGM) para os postos de veículos elétricos.

- **Cálculo de Potências e Balanceamento:** Com base em 25 equipamentos principais (máquinas de injeção, moinho de 70 kVA, etc.), a potência previsível total ascende a aproximadamente **700 kVA**. O balanceamento entre fases foi otimizado para evitar desequilíbrios superiores a 15%.

- **Sistema de Proteções:** Foi adotado o sistema **TT**, com neutro ligado à terra de serviço e massas ligadas à terra de proteção. A proteção contra contatos indiretos é garantida por disjuntores diferenciais. A resistência da rede de terras foi dimensionada para um máximo de 20 Ω.

- **Caminhos de Cabos e Tubagens:** Os cabos foram dimensionados conforme a corrente de serviço e queda de tensão admissível. O diâmetro das tubagens segue a regra: `∅tubo = 0,33 × Σ secção dos cabos`.

### 3. Metodologia de Projeto e Ferramentas Utilizadas

| Ferramenta | Propósito |
| :--- | :--- |
| **AutoCAD** | Produção de todas as peças desenhadas (plantas, diagramas, esquemas). |
| **DIALux** | Estudo luminotécnico, simulação de níveis de iluminância e seleção de luminárias. |
| **Excel** | Cálculos justificativos (balanceamento, dimensionamento de cabos, quedas de tensão). |
| **Word** | Elaboração da memória descritiva e fichas de caracterização da DGEG. |

O conjunto de peças desenhadas incluiu plantas de localização, traçado de caminhos de cabos, localização de quadros, alimentação de equipamentos, iluminação normal/emergência, diagrama unifilar e esquemas elétricos de princípio (ELP) de todos os quadros.

### 4. Soluções Técnicas Implementadas

- **Alimentação das Máquinas:** Circuitos dedicados com proteções termomagnéticas e diferenciais adequadas às correntes de arranque e regime nominal.
- **Circuito de Tomadas:** Circuitos de uso geral (máximo de 8 pontos por circuito) e circuitos específicos para equipamentos críticos.
- **Postos para Veículos Elétricos:** O QGM alimenta postos de carregamento com proteções diferenciais tipo A e circuitos independentes, em conformidade com a regulação atual.
- **Rede de Terras:** Dimensionada com condutores de cobre nu de 50 mm² e elétrodos de aço cobreado para garantir uma resistência de terra < 20 Ω.

### 5. Integração e Fluxo de Trabalho

O projeto seguiu um fluxo lógico e calendarizado:
1.  Levantamento de requisitos e análise do enunciado.
2.  Cálculos preliminares de potências e balanceamento.
3.  Estudo luminotécnico com DIALux.
4.  Desenvolvimento do diagrama unifilar e da arquitetura de quadros.
5.  Desenho técnico no AutoCAD de todas as plantas e esquemas.
6.  Dimensionamento detalhado de cabos, proteções e tubagens.
7.  Redação da memória descritiva e preenchimento dos anexos oficiais da DGEG.
8.  Consolidação de todo o material num portfólio digital.

### 6. Resultados Técnicos, Conformidade e Dificuldades Superadas

- **Resultado Final:** O projeto cumpriu integralmente os requisitos normativos e os objetivos do enunciado, com uma potência total prevista de ≈700 kVA, sistema de proteções TT completo, iluminação validada no DIALux e documentação formatada para licenciamento.
- **Dificuldades Superadas:**
  - **Síntese da Memória Descritiva:** A limitação de 5 páginas exigiu uma síntese rigorosa sem perda de conteúdo técnico.
  - **Aplicação Prática de Teoria:** Tradução de normas (R.T.I.E.B.T.) e conceitos teóricos para um projeto real e complexo.
- **Sugestão de Melhoria Apontada:** Inclusão de visões frontais em 2D dos quadros elétricos nas peças desenhadas para maior clareza.

### 7. Conclusão e Aprendizados Técnicos

Este projeto funcionou como um integrador prático de conhecimentos em eletrotecnia, normativas, desenho técnico e gestão de projeto. A principal aprendizagem foi compreender as fases de criação de um projeto de instalações elétricas e desenvolver a capacidade de pensar na perspetiva do projetista.

**Aprendizagens técnicas específicas:**
- Aplicação real do R.T.I.E.B.T., normas europeias e procedimentos da DGEG.
- Importância do balanceamento de fases e da seleção de proteções em ambiente industrial.
- Domínio de ferramentas profissionais como AutoCAD e DIALux.
- Estruturação de documentação técnica complexa para licenciamento.

**Perspectivas de Melhoria Técnica Futura:**
- Implementação de um sistema de monitorização de consumos (SCADA/Energy Management).
- Integração de geração fotovoltaica para autoconsumo.
- Aprofundamento do estudo de harmónicos gerados pelas máquinas.
- Utilização de quadros modulares inteligentes com comunicação para manutenção preditiva.

### 8. Documentação do Projeto (Peças Escritas e Desenhadas)

Toda a documentação técnica, incluindo a memória descritiva, os anexos DGEG preenchidos, a folha de cálculo de balanceamento e os ficheiros DWG, está disponível para consulta e download na pasta `project-files/` deste repositório.

*Nota: A memória descritiva fornecida é um exemplo representativo para proteger dados sensíveis do documento original entregue para avaliação.*

### 9. Licença

Este projeto está licenciado sob a **MIT License**. Veja o ficheiro `LICENSE` para mais detalhes.
