# 📋 Projeto Cadastro de Clientes - Full Stack Foundation

> **Engenharia de Software & Gestão de Dados**
> Este projeto demonstra a aplicação prática de conceitos de Orientação a Objetos (POO) em Java, integrando lógica de negócios com uma estrutura de dados organizada.

---

## 👤 Perfil do Desenvolvedor
**Willian Junio**
*Software Engineer | Foco em Liderança Técnica e Gestão de Projetos*
*Candidato a MBA em Gestão de TI / Business*

---

## 🚀 Sobre o Projeto
O sistema foi desenvolvido para gerenciar cadastros de diferentes perfis dentro de um ecossistema educacional ou corporativo. O foco principal foi a criação de um código limpo, modular e de fácil manutenção, aplicando os pilares da POO.

### Principais Funcionalidades:
* **Gestão de Perfis:** Cadastro diferenciado para Alunos, Professores e Funcionários.
* **Arquitetura Escalável:** Uso de herança para evitar repetição de código (DRY - Don't Repeat Yourself).
* **Documentação Estratégica:** Acompanha roteiro técnico detalhando as etapas de desenvolvimento.

---

## 🛠️ Stack Técnica
* **Linguagem:** Java (JDK 17+)
* **Paradigma:** Programação Orientada a Objetos
* **Estrutura de Dados:** Atributos encapsulados e métodos de acesso (Getters/Setters)
* **Versionamento:** Git

---

## 🏗️ Estrutura de Classes

Abaixo, a representação da hierarquia de classes implementada no projeto:



| Classe | Papel no Sistema |
| :--- | :--- |
| `Pessoa.java` | **Classe Base (Pai):** Contém atributos genéricos como nome e identificação. |
| `Aluno.java` | **Especialização:** Herda de Pessoa e adiciona atributos acadêmicos. |
| `Professor.java` | **Especialização:** Focado em dados do corpo docente. |
| `Funcionario.java` | **Especialização:** Atributos voltados à gestão administrativa. |
| `Main.java` | **Orquestrador:** Contém o método principal que executa a aplicação. |

---

## 🧠 Destaques Técnicos (Engineering Mindset)

Como gestor técnico em formação, priorizei os seguintes aspectos:

1.  **Polimorfismo e Herança:** Otimização da memória e organização lógica das entidades.
2.  **Encapsulamento:** Garantia de que os dados internos de cada classe só sejam acessados via métodos autorizados.
3.  **Clean Code:** Nomenclatura de variáveis e métodos em português (conforme o roteiro) para facilitar o entendimento em contextos específicos de extensão.

---

## 📖 Como visualizar e executar

1. **Clonagem:**
   ```bash
   git clone [https://github.com/Willianjcss/Projeto-Cadastro-De-Clientes.git](https://github.com/Willianjcss/Projeto-Cadastro-De-Clientes.git)
