# Quantum_Map - Mapeamento do Ecossistema Quântico

> **Projeto de Iniciação Científica (IC) em Computação Quântica**  
> Documentação inicial, glossário e estado da arte.

## Introdução
Antes de mergulharmos nas equações de mecânica quântica, álgebra linear e na programação de algoritmos complexos, o nosso primeiro passo será entender o ecossistema global da Computação Quântica.

A ciência não acontece no vácuo. Para que a pesquisa de vocês tenha impacto, vocês precisam saber: quem está construindo os computadores? Como acessá-los? Qual linguagem usar? E quem são as pessoas e governos por trás disso?

Esta primeira atividade é um **Mapeamento do Estado da Arte**. Vocês atuarão como uma força-tarefa de pesquisa nas próximas semanas.

---

##  Dinâmica do Grupo
Como vocês são um time de 5 alunos de Iniciação Científica, a atividade está dividida em **Módulos de Especialidade**. Cada aluno escolherá um módulo principal para ser o "Líder de Pesquisa", ficando responsável por compilar os dados daquela área. 

**Regra de Ouro:** O líder pesquisa e documenta, mas o conhecimento deve ser compartilhado com todos da equipe!

---

## 📂 Estrutura do Projeto (Pages)
Cada módulo deste mapeamento possui sua própria página no menu. 

*   [`glossario.md`](glossario.md) - Dicionário Quântico (Módulo 0)
*   [`modulo1-hardware.md`](modulo1-hardware.md) - O Hardware Quântico e a Indústria
*   [`modulo2-nuvem.md`](modulo2-nuvem.md) - Simuladores e Computação em Nuvem
*   [`modulo3-software.md`](modulo3-software.md) - O Stack de Software e Frameworks
*   [`modulo4-geopolitica.md`](modulo4-geopolitica.md) - Geopolítica, Instituições e Mercado Real
*   [`modulo5-historia.md`](modulo5-historia.md) - Os Pioneiros e a História

---

## Módulo 0: O Dicionário Quântico (Tarefa Compartilhada)
*Página de destino:* `glossario.md`
*Objetivo: Nivelar o vocabulário da equipe.*

Abaixo estão os principais termos de comunicação e computação quântica. **Cada aluno ficará responsável por pesquisar, definir de forma simples e documentar os termos atrelados à sua numeração**, desenvolvendo isso em paralelo ao seu módulo principal.

*   **Pesquisador 1:** QUBITS | Portas quânticas | Superposição | Entrelaçamento
*   **Pesquisador 2:** Fóton polarizado | Teorema do não-clonamento | Desigualdade de Bell
*   **Pesquisador 3:** Algoritmo de Shor | Algoritmo de Grover | Criptografia pós-quântica
*   **Pesquisador 4:** QKD (Quantum Key Distribution) | Protocolos: BB84, E91, B92 | CV-QKD
*   **Pesquisador 5:** Repetidor quântico | Memória quântica | Nó confiável (Trusted node) | OTP (One-Time Pad)

---

## Módulos de Pesquisa (Estado da Arte)

### 🔹 Módulo 1: O Hardware Quântico e a Indústria 
**Objetivo:** Mapear o que são os computadores quânticos físicos e quem os fabrica.
*   **Mapeamento Global e Nacional:** Quantos computadores quânticos temos hoje e onde? E já temos no Brasil? Onde?
*   **Tecnologias:** Quais são as principais abordagens físicas para criar qubits hoje? *(Diferencie Supercondutores, Íons Armadilhados, Fotônicos, Átomos Neutros e Quantum Annealers).*
*   **Empresas:** Quais são as empresas que estão construindo essas máquinas? *(Pesquise sobre IBM, Google Quantum AI, IonQ, D-Wave, Rigetti, Quantinuum, Xanadu).*
*   **Métricas:** O que é "Volume Quântico" (Quantum Volume) e por que não basta apenas contar o número de qubits?
*   **Horizontes:** Quais outras tecnologias quânticas existem além da computação? *(Criptografia quântica, geração de números aleatórios, sensoriamento quântico…)*

### 🔹 Módulo 2: Simuladores e Computação em Nuvem
**Objetivo:** Descobrir como nós (pesquisadores) acessamos essas máquinas e quanto isso custa.
*   **Plataformas de Acesso:** Como funciona o Amazon Braket (AWS) e o Azure Quantum (Microsoft)?
*   **Acesso Gratuito:** Quais recursos estão disponíveis gratuitamente para estudantes e pesquisadores?
*   **Simulador vs. Máquina Real:** Qual a diferença entre rodar um circuito em um simulador clássico *(ex: Aer Simulator)* e em uma QPU *(Quantum Processing Unit)* real?
*   **Planos de Pagamento:** Faça um mapeamento de custos. Como funciona o plano gratuito (*Open Plan*) da IBM Quantum Platform? Quantos qubits podemos usar de graça? Qual é o custo médio para rodar em máquinas via AWS Braket?

### 🔹 Módulo 3: O Stack de Software e Frameworks
**Objetivo:** Mapear as ferramentas de desenvolvimento.
*   **Linguagens e Bibliotecas:** Quais são os principais frameworks open-source hoje?
*   **Aprofundamento:** Descreva o foco e a empresa por trás dos seguintes frameworks:
    *   *Qiskit* (IBM - foco geral/Python)
    *   *Cirq* (Google)
    *   *PennyLane* (Xanadu - foco em Machine Learning Quântico)
    *   *Q#* (Microsoft)
*   **Limites:** O que conseguimos (e o que não conseguimos) fazer com cada linguagem atualmente?
*   **Comunidade e Hackathons:** Como essas empresas incentivam estudantes? *(Pesquise sobre o Qiskit Advocate Program)*. Existem hackathons nessa área? Quais são os principais?

### 🔹 Módulo 4: Geopolítica, Instituições e Mercado Real
**Objetivo:** Entender o financiamento e as aplicações práticas.
*   **Governos:** Mapeie os grandes programas governamentais *(ex: National Quantum Initiative dos EUA, Quantum Flagship da Europa, e os investimentos da China, como o satélite Micius)*. Como o Brasil está se posicionando?
*   **Aplicações Reais:** Que instituições já aplicam/pesquisam algoritmos quânticos na prática?
    *   *Finanças:* O que o JPMorgan e o Goldman Sachs estão fazendo?
    *   *Saúde/Indústria:* Cleveland Clinic e Mercedes-Benz.
    *   *Pesquisa:* CERN.
*   **Ecossistema Brasileiro:** Existem instituições, editais ou empresas brasileiras que estão financiando pesquisa em quântica?
*   **Eventos:** Quais são as principais conferências e eventos de quântica no mundo e no Brasil?

### 🔹 Módulo 5: Os Pioneiros e a História
**Objetivo:** Dar rosto e contexto histórico à teoria, mapeando as origens da área.
*   **A Origem e os Gigantes:**
    *   Qual foi o papel de Richard Feynman (1981) e David Deutsch na idealização da computação quântica?
*   **Os Algoritmos que Mudaram Tudo:** 
    *   Quem é Peter Shor e por que seu algoritmo de fatoração assustou a segurança mundial?
    *   Quem é Lov Grover e qual a importância de seu algoritmo de busca?
*   **Reconhecimento Recente:** 
    *   Pesquise sobre o Prêmio Nobel de Física de 2022 (Alain Aspect, John Clauser e Anton Zeilinger). O que é o "Emaranhamento Quântico" e por que prová-lo definitivamente rendeu um Nobel?

---

## 📌 Como contribuir neste repositório
1. Crie uma branch no padrão docs/moduloX e os commits devem ser feitos utilizando a convenção de commits ex: "docs: adiciona diagrama módulo 1 - hardware"
2. Para o **Módulo 0**, para evitar conflitos no Git quando todos forem editar o mesmo arquivo do glossário, a dica de ouro é sempre pular duas linhas em branco antes e depois de inserir o seu bloco de termos; além disso, mantenham o repositório organizado criando suas branches no padrão docs/glossario-seunome (ex: docs/glossario-maria) e padronizem as mensagens de salvamento utilizando commits semânticos, como git commit -m "docs: adiciona termos de criptografia ao glossario", garantindo um histórico limpo antes de abrirem o Pull Request para a branch main.
3. Preparem-se para um seminário onde todos compartilharão suas descobertas com a equipe!
