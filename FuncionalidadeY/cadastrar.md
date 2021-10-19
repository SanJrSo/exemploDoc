**Feature: Utilizando funcionalidade Y**  
=
**Scenario: Cadastrar funcionalidade Y**  

**Given** usuário acessa o ambiente da funcionalidade Y  
**And** clica no botão mais registro  
**And** informa a "*descrição*" do registro  

|Cenário |descrição             |
|--------|----------------------|
|1       | Teste sem caracteres |
|2       | Teste com caracteres |

**When** clica no botão salvar  
**Then** está presente a mensagem salvo com sucesso  
**And** está presente as informações na listagem  