# AgroMart: Avaliação da Qualidade do Software 

## Estabelecer os requisitos de avaliação

- **Subcaracterística avaliada**: Compreensibilidade  
- **Critério de qualidade**: Manutenabilidade  
- **Foco**: [Código web](https://github.com/AgroMart/agromart-web) e [documentação](https://github.com/AgroMart/docs)

---

### 1. Propósito da Avaliação

O objetivo da avaliação é **verificar a compreensibilidade do sistema AgroMart**, com ênfase tanto na estrutura do código web quanto na documentação e na qualidade do código.

- Tem uma base de código clara, legível, coesa e bem estruturada;
- Tenha documentação acessível e atualizada para facilitar a compreensão e situar novos desenvolvedores;
- Possua boas práticas de modularização, comentários, e testes que suportem a evolução contínua do sistema;
- Possibilite que vários desenvolvedores, com diferentes níveis de experiência, possam contribuir ou modificar o sistema com segurança.

O AgroMart é um software que possui código aberto e colaborativo, que pode receber manutenção por diferentes desenvolvedores ao longo do tempo. Logo, a clareza, organização e documentação são de extrema importância para garantir a longevidade e reusabilidade.

---

### 2. Identificação do Tipo de Produto

Produtos avaliados: Interface Web + Documentação Técnica

<div style="overflow-x:auto">

<table>
  <thead>
    <tr>
      <th>Aspecto</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Tipo</strong></td><td>Aplicação Web (React/TypeScript) + Repositório de Documentação (docs)</td></tr>
    <tr><td><strong>Usuários-alvo</strong></td><td>Desenvolvedores atuais e futuros colaboradores do AgroMart</td></tr>
    <tr><td><strong>Finalidade</strong></td><td>Permitir fácil entendimento, modificação e extensão do sistema</td></tr>
    <tr><td><strong>Tecnologias Utilizadas</strong></td><td>React, TypeScript, HTML, CSS, Markdown, GitHub Pages</td></tr>
    <tr><td><strong>Repositórios Avaliados</strong></td><td><code>agromart-web</code> e <code>docs</code></td></tr>
    <tr><td><strong>Ambientes Esperados</strong></td><td>Ambientes de desenvolvimento modernos (Node.js, navegadores atualizados)</td></tr>
  </tbody>
</table>

</div>

---

## 2.1. Critérios de Qualidade e Ênfase

A tabela abaixo detalha os critérios de qualidade considerados e o nível de ênfase atribuído a cada um (em uma escala de 0 a 5, onde 0 é o menor e 5 é o maior):

<div style="overflow-x:auto">

<table>
  <thead>
    <tr>
      <th>Critério de Qualidade</th>
      <th>Ênfase (0 a 5)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Funcionalidade</td><td>2</td></tr>
    <tr><td>Confiabilidade</td><td>3</td></tr>
    <tr><td>Usabilidade</td><td>3</td></tr>
    <tr><td>Portabilidade</td><td>1</td></tr>
    <tr><td>Eficiência</td><td>2</td></tr>
    <tr><td>Completude</td><td>3</td></tr>
    <tr><td><strong>Manutenabilidade</strong></td><td><strong>5</strong></td></tr>
  </tbody>
</table>

</div>

---

## 2.2. Componentes a Serem Avaliados

Para esta avaliação, os componentes centrais da interface web do AgroMart que serão analisados são:

- **Código-fonte**: Organização dos componentes, uso de boas práticas e estrutura do projeto;
- **Arquivos React e TypeScript**: Nomenclatura, modularidade, separação de responsabilidades;
- **Testes automatizados**: Presença, cobertura e clareza dos testes;
- **Documentação interna**: Comentários e arquivos de apoio à compreensão do sistema.

---

## 2.3. Modelo e Metodologia de Avaliação

### ISO/IEC 25010 — Subcaracterística: Compreensibilidade

A **compreensibilidade** está relacionada à capacidade dos desenvolvedores de entenderem a estrutura, o comportamento e as responsabilidades do sistema de forma rápida e precisa. Isso inclui:

- Organização e nomeação dos arquivos e componentes;
- Uso de comentários explicativos e boas práticas de código;
- Presença de documentação técnica, READMEs, diagramas e fluxos;
- Coerência entre o que está documentado e o que está implementado.

---

### Q-RAPID — Visão Estratégica

No modelo **Q-RAPID**, a compreensibilidade está associada a:

- Redução da curva de aprendizado para novos desenvolvedores;
- Minimização de erros por má interpretação;
- Facilidade na colaboração em equipe e transferência de conhecimento;
- Sustentabilidade do código a longo prazo, mesmo com mudanças na equipe.

---

### Avaliação da Manutenabilidade

A avaliação da manutenabilidade do AgroMart permitirá:

- Identificar pontos fracos na organização do código;
- Medir a qualidade dos testes existentes e sua cobertura;
- Avaliar se o sistema é compreensível e facilmente extensível por novos desenvolvedores.

---

## 3. Conexões com os Objetivos de Desenvolvimento Sustentável (ODS)

O grupo identificou o AgroMart como tendo alinhamento com os seguintes [ODS](https://brasil.un.org/pt-br/sdgs):

- **ODS 1 (Erradicação da Pobreza)** e **ODS 8 (Trabalho decente e crescimento Econômico)**: Promover o desenvolvimento econômico local e reduzir as desigualdades, proporcionando aos agricultores familiares uma plataforma para comercializar seus produtos diretamente aos consumidores.
- **ODS 2 (Fome Zero e Agricultura Sustentável)**: Contribuir para a segurança alimentar, reduzindo o desperdício de alimentos e promovendo práticas agrícolas sustentáveis.
- **ODS 10 (Redução das Desigualdades)**: Fomentar a autonomia dos produtores e fortalecer a agricultura familiar, reduzindo as desigualdades no acesso ao mercado.
- **ODS 12 (Consumo e Produção Responsáveis)**: Promover o consumo consciente e a produção responsável, conectando consumidores a co-agricultores e incentivando práticas sustentáveis.

---

## 4. Questões de Análise do Projeto

<div style="overflow-x:auto">

<table>
  <thead>
    <tr>
      <th>Questão</th>
      <th>Resposta</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>Q1:</strong> Quais são os principais usuários do produto?</td><td>Agricultores CSA e consumidores finais.</td></tr>
    <tr><td><strong>Q2:</strong> Quais são as principais tarefas do produto?</td><td>Cadastro de produtos, compra, gestão de loja, visualização em mapa.</td></tr>
    <tr><td><strong>Q3:</strong> Quais funções merecem maior dedicação durante a avaliação?</td><td>Componentes com alta complexidade e rotas principais da aplicação.</td></tr>
    <tr><td><strong>Q4:</strong> Quantas janelas de interação o sistema possui?</td><td>Oito interfaces principais com rotas distintas.</td></tr>
    <tr><td><strong>Q5:</strong> Qual o ambiente de execução do produto?</td><td>Navegadores modernos com frontend em React/TypeScript e backend no Firebase.</td></tr>
    <tr><td><strong>Q6:</strong> Qual o nível de conhecimento exigido dos desenvolvedores?</td><td>Médio a avançado em frontend moderno; básico em Git e Markdown.</td></tr>
    <tr><td><strong>Q7:</strong> Quais são os principais componentes a serem avaliados?</td><td>Estrutura de código (<code>agromart-web</code>) e documentação de apoio (<code>docs</code>).</td></tr>
    <tr><td><strong>Q8:</strong> Existe massa de dados disponível para a avaliação?</td><td>Não. A avaliação será feita por inspeção de código e análise da documentação existente.</td></tr>
    <tr><td><strong>Q9:</strong> Quais são os requisitos de desenvolvimento?</td><td>Node.js, npm/yarn, VSCode, navegador e ambiente Linux ou Windows.</td></tr>
    <tr><td><strong>Q10:</strong> Quais tecnologias o projeto utiliza?</td><td>React, TypeScript, Firebase, TailwindCSS, GitHub Pages, Markdown.</td></tr>
  </tbody>
</table>

</div>

---

## Tabela de Versionamento

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
      <td>10/07/2025</td>
      <td>1.0</td>
      <td>Criação da Fase 1</td>
      <td><a href="https://github.com/RaissaAndradeS">Raissa</a></td>
      <td><a href="https://github.com/MVConsorte">Mateus</a></td>
    </tr>
  </tbody>
</table>

</div>
