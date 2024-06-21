# Projeto Java Gestão de Funcionários

## Descrição
Projeto para gerenciamento de funcionários com operações CRUD, agrupamento de funcionários e regras de negócios conforme requisitos abaixo do Desafio.
Desenvolvido utilizando Java 17, com suporte para Maven, se necessário, e utilizando a IDE IntelliJ. 

## Requisitos/Funcionalidades
1. **Classe Pessoa**:
   - Atributos:
     - `nome` (String)
     - `dataNascimento` (LocalDate)

2. **Classe Funcionario**:
   - Estende a classe `Pessoa`
   - Atributos adicionais:
     - `salario` (BigDecimal)
     - `funcao` (String)

3. **Classe Principal**:
   - Deve executar as seguintes ações:
     1. Inserir todos os funcionários na mesma ordem e com as informações da tabela fornecida.
     2. Remover o funcionário “João” da lista.
     3. Imprimir todos os funcionários com todas suas informações, com formatação específica:
        - Data no formato `dd/MM/yyyy`
        - Valores numéricos com separador de milhar como ponto e decimal como vírgula.
     4. Aplicar um aumento de 10% no salário de todos os funcionários e atualizar a lista.
     5. Agrupar os funcionários por função em um mapa (`Map`), onde a chave é a `função` e o valor é a `lista de funcionários`.
     6. Imprimir os funcionários agrupados por função.
     7. Imprimir os funcionários que fazem aniversário nos meses de outubro (10) e dezembro (12).
     8. Imprimir o funcionário com a maior idade, exibindo os atributos `nome` e `idade`.
     9. Imprimir a lista de funcionários em ordem alfabética.
     10. Imprimir o total dos salários dos funcionários.
     11. Imprimir quantos salários mínimos cada funcionário ganha, considerando que o salário mínimo é R$ 1212.00.

## Tabela de Dados dos Funcionários

| Nome    | Data Nascimento | Salário  | Função         |
|---------|-----------------|----------|----------------|
| Maria   | 18/10/2000      | 2009.44  | Operador       |
| João    | 12/05/1990      | 2284.38  | Operador       |
| Caio    | 02/05/1961      | 9836.14  | Coordenador    |
| Miguel  | 14/10/1988      | 19119.88 | Diretor        |
| Alice   | 05/01/1995      | 2234.68  | Recepcionista  |
| Heitor  | 19/11/1999      | 1582.72  | Operador       |
| Arthur  | 31/03/1993      | 4071.84  | Contador       |
| Laura   | 08/07/1994      | 3017.45  | Gerente        |
| Heloísa | 24/05/2003      | 1606.85  | Eletricista    |
| Helena  | 02/09/1996      | 2799.93  | Gerente        |

## Instruções de Execução
1. **Clone o repositório via SSH**:
   ```sh
   git clone git@github.com:dopimentel/desafio-projedata.git
