Projeto desenvolvido para a disciplina de Desenvolvimento de Sistemas da FATEC.

Implementar uma pipeline CI/CD utilizando GitHub Actions com:

Integração Contínua (CI)
Pull Request automático
Build automatizado
Testes automatizados
Análise de segurança com CodeQL

---

Tecnologias Utilizadas
Python
Git
GitHub
GitHub Actions
CodeQL
Pytest
Flake8

---

Estrutura do Projeto
.github/
│
├── workflows/
│   └── ci-cd-pipeline.yml
│
├── codeql-config.yml
│
tests/
│   └── test_main.py
│
main.py
requirements.txt
README.md


---

Funcionamento da Pipeline
A pipeline executa automaticamente quando ocorre:

Push para a branch main
Abertura de Pull Request

Fluxo da Pipeline
Análise de segurança com CodeQL
Execução dos testes automatizados
Deploy para ambiente stage

---

Pull Request
Foi criada uma branch de teste para validar o funcionamento da automação.

Exemplo:

git checkout -b feature/teste-pipeline


Após o push da branch, foi aberto um Pull Request no GitHub, disparando automaticamente a pipeline CI/CD.

---

Evidências
Pipeline executando com sucesso
Adicionar screenshot aqui.

Pull Request criado
Adicionar screenshot aqui.

Jobs da pipeline
CodeQL
Tests
Deploy Stage

Todos executados com sucesso.

---

Autor
Nome: Gustavo Paulo de Sousa 

Curso: Segurança da Informação — FATEC

Disciplina: Desenvolvimento de Sistemas

Professor: Idirley Soares