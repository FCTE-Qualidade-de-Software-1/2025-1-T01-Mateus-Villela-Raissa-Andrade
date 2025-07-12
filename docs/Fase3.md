#  Fase 3 – Projetar a Avaliação

**Subcaracterística Avaliada:** _Compreensibilidade_  
**Critério de Qualidade:** _Manutenabilidade_ (ISO/IEC 25010)  
**Sistema Avaliado:** AgroMart – Repositórios `agromart-web` e `docs`

---

##  Objetivo

Executar o plano de avaliação da compreensibilidade do sistema AgroMart, medindo a clareza e facilidade de entendimento do código-fonte e da documentação técnica, com base nas métricas definidas na Fase 2.

---

##  Plano de Avaliação

A avaliação será realizada por meio da aplicação das **métricas GQM** definidas anteriormente, utilizando métodos de inspeção, simulação e análise documental.

---

## 1.  Estratégia de Avaliação

1. **Aplicação da abordagem GQM (Goal – Question – Metric)**  
2. **Divisão de responsabilidades por métrica**  
3. **Registro de dados em planilha de pontuação**  
4. **Classificação do sistema com base nos níveis definidos**  
5. **Geração de recomendações de melhoria**

---

## 2. Métricas e Métodos de Coleta

<div style="overflow-x: auto">

<table>
  <thead>
    <tr>
      <th><strong>Métrica</strong></th>
      <th><strong>Questão</strong></th>
      <th><strong>Descrição</strong></th>
      <th><strong>Método</strong></th>
      <th><strong>Tipo</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>M1</td>
      <td>Q1</td>
      <td>Organização modular do código</td>
      <td>Inspeção de pastas</td>
      <td>Objetiva</td>
    </tr>
    <tr>
      <td>M2</td>
      <td>Q1</td>
      <td>Clareza na nomeação de arquivos e componentes</td>
      <td>Avaliação cruzada</td>
      <td>Subjetiva</td>
    </tr>
    <tr>
      <td>M3</td>
      <td>Q2</td>
      <td>Existência de README, guia e arquitetura</td>
      <td>Checklist</td>
      <td>Binária</td>
    </tr>
    <tr>
      <td>M4</td>
      <td>Q2</td>
      <td>Clareza da documentação (escala 1–5)</td>
      <td>Avaliação com nota</td>
      <td>Subjetiva</td>
    </tr>
    <tr>
      <td>M5</td>
      <td>Q3</td>
      <td>Proporção de funções com comentários úteis</td>
      <td>Contagem manual</td>
      <td>Objetiva</td>
    </tr>
    <tr>
      <td>M6</td>
      <td>Q3</td>
      <td>Aderência a padrões de boas práticas</td>
      <td>Checklist e lint</td>
      <td>Subjetiva</td>
    </tr>
  </tbody>
</table>

</div>

---

## 3. Cronograma de Execução
<div style="overflow-x: auto">

<table>
  <thead>
    <tr>
      <th><strong>Etapa</strong></th>
      <th><strong>Responsável</strong></th>
      <th><strong>Duração Estimada</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Preparação do ambiente</td>
      <td><a href="https://github.com/MVConsorte">Mateus</a>  <a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>0,5h</td>
    </tr>
    <tr>
      <td>Avaliação das métricas M1, M2, M5, M6</td>
      <td><a href="https://github.com/MVConsorte">Mateus</a>  <a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>3h</td>
    </tr>
    <tr>
      <td>Avaliação das métricas M3, M4</td>
      <td><a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>3h</td>
    </tr>
    <tr>
      <td>Consolidação dos dados</td>
      <td><a href="https://github.com/MVConsorte">Mateus</a></td>
      <td>3h</td>
    </tr>
    <tr>
      <td>Redação do relatório final</td>
      <td><a href="https://github.com/MVConsorte">Mateus</a>  <a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>3h</td>
    </tr>
  </tbody>
</table>

</div>


---

##  4. Escalas de Pontuação

- 👍 **Alto** – Atende totalmente à expectativa  
- ⚠️ **Médio** – Atende parcialmente  
- 🚨 **Baixo** – Pouca ou nenhuma clareza/apoio

> ℹ As escalas específicas por métrica foram definidas na [Fase 2](Fase2.md).

---

## 5. Riscos e Mitigações

<div style="overflow-x: auto">

<table>
  <thead>
    <tr>
      <th><strong>Risco</strong></th>
      <th><strong>Mitigação</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Subjetividade nas métricas</td>
      <td>Uso de checklist e dupla avaliação</td>
    </tr>
    <tr>
      <td>Documentação desatualizada</td>
      <td>Verificação de data dos commits</td>
    </tr>
    <tr>
      <td>Dificuldade com novo dev</td>
      <td>Usar membro com pouca familiaridade com o projeto</td>
    </tr>
  </tbody>
</table>

</div>

---

##  6. Evidências Esperadas

- ✅ Planilha com pontuação por métrica  
- 🖼️ Capturas de tela dos arquivos avaliados  
- 📝 Relatório final com diagnóstico + recomendações  
- ⏱️ Tempo real de simulação de onboarding com novo dev

---

## 7. Critérios de Julgamento Final

<div style="overflow-x: auto">

<table>
  <thead>
    <tr>
      <th><strong>Classificação</strong></th>
      <th><strong>Critério</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Compreensível</strong></td>
      <td>≥ 4 métricas <strong>Altas</strong>, nenhuma <strong>Baixa</strong></td>
    </tr>
    <tr>
      <td><strong>Parcialmente compreensível</strong></td>
      <td>2–3 <strong>Altas</strong>, até 2 <strong>Baixas</strong></td>
    </tr>
    <tr>
      <td><strong>Pouco compreensível</strong></td>
      <td>&lt; 2 <strong>Altas</strong> ou ≥ 3 <strong>Baixas</strong></td>
    </tr>
  </tbody>
</table>

</div>

---

## 🔗 Referências

- [Fase 2 – Especificar Avaliação (GQM)](Fase2.md)
- [ISO/IEC 25010](https://iso25000.com/index.php/en/iso-25000-standards/iso-25010)
- [AgroMart Web](https://github.com/AgroMart/agromart-web)
- [AgroMart Docs](https://github.com/AgroMart/docs)


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
      <td>Criação da Fase 3, Planejamento</td>
      <td><a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td>–</td>
    </tr>
  </tbody>
</table>

</div>



