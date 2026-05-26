Sistema Acadêmico Pro: Banco de Dados Estilo Anos 60 (C & Python)

**Visão Geral**
Sistema híbrido que recria o conceito de gerenciamento de dados de baixo nível inspirado nos primórdios da computação. O projeto une a alta performance e o controle de memória da **Linguagem C** com uma interface gráfica integrada em **Python** (Tkinter), simulando a identidade visual clássica dos sistemas legados.

---

### Como Funciona a Arquitetura e Recursos:

* **O Motor (Core em C):** Responsável pela manipulação direta do arquivo binário (`database.bin`). Executa com máxima performance as operações estruturadas de persistência em disco, lógica de ponteiros e o processamento de arquivos para importação e exportação de dados.
* **A Interface (Camada Python):** Desenvolvida em Python (`app.py`), provê a abstração visual. Ela gerencia o formulário de cadastro, os filtros de busca dinâmica e regras de negócio como validação de CPF e cálculo automático do painel "Status da Turma" (Exibindo Total, Média Geral e Taxa de Aprovação).

---

### Funcionalidades Práticas Visíveis:

* **CRUD Completo:** Cadastro, leitura, ordenação (por ID, Nome, Matéria, Nota, Frequência e Situação) e exclusão de registros acadêmicos.
* **Interoperabilidade:** Botões dedicados para importação e exportação de arquivos nos formatos `.TXT` e `.EXCEL`.
* **Regras de Negócio Automatizadas:** Formatação de máscaras de documentos e alteração visual reativa (destaque em verde para alunos aprovados e vermelho para reprovados).

---

### Competências Demonstradas:

* **Manipulação de Baixo Nível:** Domínio de estruturas de dados fixas (`structs`) e persistência binária sem depender de frameworks prontos.
* **Desenvolvimento de Interfaces (GUI):** Construção de um painel de controle intuitivo, limpo e responsivo para manipulação de dados complexos.
* **Arquitetura de Software:** Separação clara de responsabilidades entre a interface de usuário (Python) e o motor de armazenamento interno (C).
