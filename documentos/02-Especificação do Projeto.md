# Especificação do Projeto

## Perfis de Usuários

[Enumere e faça o detalhamento dos perfis de usuários. Utilize o modelo de tabela abaixo para sintetizá-los.]

<table >
    <tbody>
        <tr>
            <td  colspan="2">Empresa 01:</td>
        </tr>
        <tr>
            <td >Descrição:</td>
            <td >Cervejaria Artesanal</td>
        </tr>
        <tr>
            <td >Necessidades:<br></td>
            <td>
                <p>Cadastrar a receita de venda de cerveja por tipo</p>
                <p>Cadastrar a receita de comidas de boteco</p>
                <p>Projetação de venda e variação da entrada caixa conforme os meses o ano</p>
            </td>
        </tr>
    </tbody>
</table>

<table >
    <tbody>
        <tr>
            <td  colspan="2">Empresa 02:</td>
        </tr>
        <tr>
            <td >Descrição:</td>
            <td >Academia de Bairro</td>
        </tr>
        <tr>
            <td >Necessidades:<br></td>
            <td>
                <p>Cadastrar a receita de venda e fazer relação com o cadastro do cliente</p>
                 <p>Cadastrar a receita com venda de acessórios expostos no caixa</p>
                  <p>Projeção de venda e variação da entrada caixa conforme os meses o ano.</P>
            </td>
        </tr>
    </tbody>
</table>
<table >
    <tbody>
        <tr>
            <td  colspan="2">Empresa 03:</td>
        </tr>
        <tr>
            <td >Descrição:</td>
            <td >Restaurante que vende comida vegana em marmita</td>
        </tr>
        <tr>
            <td >Necessidades:<br></td>
            <td>
                <p>Cadastrar a receita de venda de marmita</p>
                <p>Cadastrar a receita com bebidas naturais</p>
                <p>Projeção de venda e variação da entrada caixa conforme os meses o ano</p>
            </td>
        </tr>
    </tbody>
</table>

<table >
    <tbody>
        <tr>
            <td  colspan="2">Empresa 04:</td>
        </tr>
        <tr>
            <td >Descrição:</td>
            <td >Empreendedor individual que vende infoprodutos sobre gestão financeira</td>
        </tr>
        <tr>
            <td >Necessidades:<br></td>
            <td>
                <p>Cadastrar a receita de venda separadamente por tipo de material</P>
                <p> Controle de vendas por mês e lançamentos</p>
                <p>Projeção de venda e variação da entrada caixa conforme os meses o ano.</p:>
            </td>
        </tr>
    </tbody>
</table>



## Histórias de Usuários

|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
|Produtor artesanal  | Preciso ter um relatório de vendas   | Para saber qual tipo de cerveja gera mais receita             |
| Personal Trainer  | Preciso ter um relatório de vendas | Para saber quantos alunos pagam a mensalidade|
|Proprietária do restaurante | Preciso de um relatório de vendas| Quantos usuários consome a marmita por dia|
|Empreendedor individual| Preciso de um relatório de vendas| Para analisar a quantidade de receita gerada em cada lançamento de produto|
|Produtor artesanal|Cadastrar uma receita|Sem precisar cadastrar um cliente/consumidor|
|Produtor artesanal|Cadastrar uma receita|Para fazer o controle do estoque pela quantidade vendida|
|Personal Trainer| Acessar as receitas geradas| Para ver a oscilação das mensalidades pagas por meses ao ano|
|Proprietária do restaurante|Acessar as receitas geradas|Para fazer projeção do fluxo de caixa para demandas futuras|

## Requisitos do Projeto



### Requisitos Funcionais



|ID    | Descrição                | Prioridade |
|-------|---------------------------------|----|
| RF-01 | Permitir um cadastro de uma receita                    | ALTA   | 
|  RF-02  | Cadastrar vendedor                    |ALTA   |
|RF-03|Informar o tipo de produto|ALTA|
|RF-04|Informar a quantidade de produto|ALTA|
|RF-05|Informar a data do pedido|ALTA|
|RF- 06|Informar a porcentagem do custo do produto sobre a receita|BAIXA|
|RF- 07|Selecionar a forma de pagamento|ALTA|
|RF-08|Cadastrar cliente consumidor do produto|MÉDIA|
|RF-09|Aplicar o desconto sobre o lançamento da receita|ALTA|
|RF-10|Informar o vendedor de cada receita gerada|MÉDIA|
|RF-11|Número da nota fiscal de origem da receita|ALTA|

### Requisitos não Funcionais

|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |Exportar as receitas geradas para excel                    |ALTA   | 
|RNF-02    |Gerar projeção de fluxo de caixa futuro                    |ALTA   | 
|RNF-03|Aplicar extrato de receita gerada em determinado período|ALTA|
|RNF-04|Verificar receitas por tipo de pagamento|MÉDIA|
|RNF-05|Aplicar  o  relatório  de  caixa  em  um  ambiente  virtual  para visualização em tempo real|ALTA|
|RNF-06|Imprimir relatórios em layouts padronizados|MÉDIA|
|RNF-07|Exibir relatório de vendas por tipo de produto|ALTA|
|RNF-08|Exibir relatório de receita por cadastro de vendedor|ALTA|

