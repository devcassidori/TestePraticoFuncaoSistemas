# 🧩 Teste Prático de Desenvolvimento — Função Sistemas

Repositório referente ao **Teste Prático de Desenvolvimento** da **Função Sistemas**, voltado à avaliação de conhecimentos técnicos em **C#**, **ASP.NET MVC**, **Entity Framework** e **SQL Server**.

O teste tem como base o sistema **FI.WebAtividadeEntrevista**, voltado à manutenção de dados de clientes.

---

## 🎯 Objetivos do Desafio

O teste propõe a evolução do sistema existente com foco em regras de negócio, manipulação de dados e aprimoramento de interface.  
As principais diretrizes envolvem:

### 🧾 1. Campo CPF no Cadastro de Clientes
- Incluir campo **CPF** na tela de cadastro/alteração de clientes.  
- Aplicar máscara de formatação padrão (`999.999.999-99`).  
- Garantir a obrigatoriedade do preenchimento.  
- Validar a estrutura e o dígito verificador do CPF.  
- Impedir duplicidade de registros de CPF.  
- Refletir a alteração no banco de dados (`CLIENTES`), com o novo campo `CPF`.

---

### 👥 2. Módulo de Beneficiários
- Adicionar o botão **“Beneficiários”** na tela de cliente.  
- Exibir um **pop-up modal** para cadastro e manutenção dos beneficiários associados.  
- Incluir os campos **Nome** e **CPF** do beneficiário.  
- Apresentar um grid com beneficiários já registrados.  
- Permitir **edição** e **exclusão** direta no grid.  
- Garantir validação de CPF e proibição de duplicidade para um mesmo cliente.  
- Persistir os beneficiários no banco de dados ao salvar o cliente, na tabela `BENEFICIARIOS`.

---

## ⚙️ Tecnologias e Ferramentas

- **C# / .NET Framework 4.8**
- **ASP.NET MVC**
- **Entity Framework**
- **SQL Server Express 2019 LocalDB**
- **JavaScript / jQuery / jQuery Mask**
- **Bootstrap**
- **Visual Studio 2022**

---

## 💡 Pontos de Atenção

- Manter a coerência visual e funcional com o layout original da aplicação.  
- Aplicar boas práticas de desenvolvimento (camadas, validação, consistência de dados).  
- Considerar a integridade relacional entre clientes e beneficiários.  
- Garantir experiência fluida de uso, com feedbacks visuais adequados.