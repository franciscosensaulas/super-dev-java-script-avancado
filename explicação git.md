Requisição => 

Servidor => PHP, Java, Python, C#

Cliente => Mobile, Software Dekstop, Web


Requisições:
- Criar       C   POST
- Consultar   R   GET
- Alterar     U   PUT (alterar todos os campos), PATCH (alteração parcial)
- Apagar      D   DELETE
nome
cnpj
razão social
data de abertura
endereço


request (requisição), response (resposta)

Cliente (mobile, web, desktop) => request
Servidor (php, python, java) receber o request e retornar => response (lista de cliente)

Request: É a solicitação(request) de dados, ou solicitação de cadastro, alteração, exclusão
Response: É a resposta que o servidor da para o cliente
Request URL: É o local que será executada a requisição
Request Method: É o verbo utilizado para a requisição
Status Code: É o status da resposta que o servidor deu, exemplos:
    - 200: OK
    - 201: Created
    - 404: Não encontrado
    - 500: Erro no servidor

GET => utilizado para consultar um dado ou vários(exemplo preciso da lista de clientes na tela)
POST => utilizado para cadastrar algo (exemplo preciso cadastrar o cliente)
PUT => utilizado para atualizar todos os campos de uma tabela (exemplo preciso alterar o cadastro completo do cliente)
PATCH => utilizado para atualizar dados parciais (exemplo preciso alterar o telefone do cliente)
DELETE => utilizado para apagar registro (exemplo preciso apagar o cliente)

Request Payload: dados que são enviados na requisição para o back-end

- lista de inteiro: [1, 2, 3, 4] 
- objeto:
{
    "nome": "Francisco",
    "idade": 20
} 
- lista de objetos
[
    {
        "nome": "Power Ranger Rosa",
        "arma": "arco e flecha"
    },
    {
        "nome": "Power Ranger Preto",
        "arma": "Tacape"
    }
]

JSON o que é

Text plain
1;Francisco;30;128
2;

<pessoa>
    <nome>Francisco</nome>
</pessoa>


Como depurar no navegador o código JavaScript?
- Colocar a palavra 'debugger' antes da linha que vc deseja analisar
- Voltar para o navegador
- Abrir as Ferramentas de desenvolvedor F12
- Executar a ação que faz chegar até naquela linha (se for na ação de um botão, clique no botão)
- PS.: Sources é o lugar onde fica os códigos no navegador (JS, CSS)
- F11 - Step Into (se estiver em uma linha que chama uma function entrará nessa function)
- F10 - Step Over (vai para a próxima linha)
- F8 - Continuar até o próximo debugger/breakpoint


PS.: Breakpoint é um ponto de parada, mesma coisa que o debugger.

Depurar é a ação de analisar um problema, linha a linha.