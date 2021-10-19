**Feature: Utilizando funcionalidade X**  
=
**Scenario: Cadastrar funcionalidade x**  

**Informações dependentes**

* [Cadastrar funcionalidade Y] (link do arquivo aqui)  

**Given** usuário acessa o ambiente da funcionalidade X  
**And** clica no botão mais registro  
**And** informa a "*descrição*" do registro  

|Cenário |descrição             |
|--------|----------------------|
|1       | Teste sem caracteres |
|2       | Teste com caracteres |

**And** seleciona a "*opção*" do registro  

|Cenário |descrição |
|--------|----------|
|1       | Opção 1  |
|2       | Opção 2  |

**When** clica no botão salvar  
**Then** está presente a mensagem salvo com sucesso  
**And** está presente as informações na listagem  