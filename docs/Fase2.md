#  Especificação da Avaliação

**Critério de Qualidade:** Manutenabilidade  
**Subcaracterística Avaliada:** Compreensibilidade  
**Objetivo:** Verificar se o sistema AgroMart (código + documentação) é fácil de entender por novos desenvolvedores

---

## 1. Objetivo de Medição (GQM)

<table>
  <thead>
    <tr>
      <th>Dimensão</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Objeto de Análise</strong></td>
      <td>Analisar o sistema <strong>AgroMart</strong> (código-fonte + documentação)</td>
    </tr>
    <tr>
      <td><strong>Propósito</strong></td>
      <td>Avaliar sua <strong>compreensibilidade técnica</strong></td>
    </tr>
    <tr>
      <td><strong>Foco</strong></td>
      <td>Estrutura de arquivos, clareza dos nomes, comentários e qualidade dos documentos de apoio</td>
    </tr>
    <tr>
      <td><strong>Ponto de Vista</strong></td>
      <td>Equipe de desenvolvimento e novos colaboradores</td>
    </tr>
    <tr>
      <td><strong>Contexto</strong></td>
      <td>Disciplina Qualidade de Software</td>
    </tr>
  </tbody>
</table>

---

##  1.1 Questões Relacionadas ao Objetivo de Medição 

| Questão | Descrição | Hipótese |
|--------|-----------|----------|
| **Q1** | O código-fonte do `agromart-web` está estruturado e nomeado de forma compreensível? | A estrutura modular e a nomeação de arquivos e funções são suficientemente claras para facilitar a navegação no sistema. |
| **Q2** | A documentação do projeto (`docs`) ajuda na compreensão da arquitetura e do fluxo de execução? | Os arquivos de documentação fornecem instruções claras para que novos desenvolvedores entendam como o sistema funciona. |
| **Q3** | Existem comentários e convenções no código que contribuem para o entendimento das funções e responsabilidades? | As funções e componentes do sistema possuem comentários explicativos e seguem padrões de nomeação consistentes. |

---

## 2. Relação entre Objetivo de Medição – Questões – Métricas

![alt text](assets/imgs/QuestoeeMetricas.png)  
<center><em>Figura 1 - Relação entre questões e métricas</em></center>

---

## 3. Abstraction Sheet – Objetivo de Medição

| **Object** | **Purpose** | **Quality Focus** | **Viewpoint** |
|-----------|-------------|-------------------|----------------|
| Código-fonte e documentação do sistema AgroMart (`agromart-web` + `docs`) | Compreensão do sistema por novos colaboradores | Compreensibilidade técnica: estrutura, nomeação, comentários e documentação de apoio | Equipe de desenvolvimento e novos contribuidores |

---

###  Quality Focus

- Clareza da estrutura de pastas e arquivos  
- Nomeação de funções, variáveis e componentes  
- Existência de comentários explicativos  
- Presença e completude de README, guias e fluxos  

---

###  Variation Factors

- Qualidade e atualização da documentação  
- Grau de padronização entre os contribuidores  
- Nível de experiência da equipe de desenvolvimento  

---

###  Baseline Hypotheses (Estimates)

- A estrutura do projeto segue padrões comuns em projetos React  
- Pelo menos 70% das funções relevantes contêm comentários úteis  
- Os nomes dos arquivos e componentes refletem suas funções no sistema  
- Há README principal e guias suficientes para onboarding básico  

---

###  Impact of Variation Factors

- Melhor padronização e documentação reduzem o tempo necessário para novos desenvolvedores entenderem o sistema  
- Falta de comentários e nomes genéricos aumenta a dificuldade de leitura do código  
- Documentação desatualizada ou inexistente compromete a compreensão geral da arquitetura  

---

## 4. Níveis de Pontuação e Critérios de Julgamento

| Métrica | Tipo      | Nível Alto (👍)                                      | Nível Médio (⚠️)                                      | Nível Baixo (🚨)                                        |
|---------|-----------|------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------|
| **M1**  | Objetiva  | Estrutura clara, com pastas por função              | Algumas pastas agrupam múltiplas lógicas              | Pastas genéricas, sem divisão clara                      |
| **M2**  | Subjetiva | Nomes descritivos e padronizados                    | Nomes medianos, às vezes genéricos                    | Nomes confusos, siglas ou abreviações                    |
| **M3**  | Binária   | README + guia de contribuição + arquitetura         | Apenas README                                         | Sem documentação funcional                               |
| **M4**  | Escore    | 5 – Documentação completa e clara                   | 3 – Documentação parcial                              | 1 – Documentação confusa ou ausente                      |
| **M5**  | Objetiva  | ≥ 70% das funções têm comentários úteis             | 40% a 69%                                             | < 40%                                                    |
| **M6**  | Subjetiva | Código segue padrões consistentes (ex: ESLint)      | Parcialmente padronizado                              | Sem padrões visíveis ou confusos                         |

---

##  Tabela de Versionamento

<div style="overflow-x:auto">

<table>
  <thead>
    <tr>
      <th>Data</th>
      <th>Versão</th>
      <th>Descrição</th>
      <th>Autor</th>
      <th>Revisor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>11/07/2025</td>
      <td>1.0</td>
      <td>Criação da Fase 2, Objetivos e Questões</td>
      <td><a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>–</td>
    </tr>
  </tbody>
</table>

</div>
