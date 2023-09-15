# Verificação do Rich Picture

## Introdução

O presente documento apresentará a verificação do artefato [Léxicos](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/lexicos), desenvolvidos pela equipe 3, VLC. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido, na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

A tabela 1 a seguir representa os dados do artefato Léxicos.

<center>

| Versão avaliada | Autor(es)   | Revisor           |
| --------------- | ----------- | ----------------- |
| 1.0             | Rafael Bosi | Giovanni Alvissus |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Léxicos. (Fonte: Henrique e Chaydson, 2023). </p>
</div>

| ID  |                                 Questão                                  | Inspeção | Observações |
| :-: | :----------------------------------------------------------------------: | :------: | ----------- |
|  1  |                 As legendas estão no padrão do projeto?                  |    🟢    |             |
|  2  |                  Possui links para os outros artefatos?                  |   N/A    |             |
|  3  |                    Existe uma introdução no artefato?                    |    🟢    |             |
|  4  |               Existe tabela de versionamento padronizado?                |    🟢    |             |
|  5  | Há referências bibliográficas, bibliografia ou referências no artefato?  |    🟢    |             |
|  6  | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟢    |             |
|  7  |                         O artefato possui autor?                         |    🟢    |             |
|  8  |                        O artefato possui revisor?                        |    🟢    |             |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Henrique e Chaydson, 2023). </p>
</div>

| ID  |                                               Questão                                                | Inspeção | Obersevação                                            |
| :-: | :--------------------------------------------------------------------------------------------------: | :------: | ------------------------------------------------------ |
|  9  |              As referências para outros termos dentro do LAL são feitas com hyperlinks?              |    🔴    | Não possui hyperlinks funcionais para os outros termos |
| 10  |                         Os termos são relevantes para o domínio em questão?                          |    🟢    |                                                        |
| 11  |                         Os termos foram definidos de forma clara e concisa?                          |    🟢    |                                                        |
| 12  |                            Os símbolos são descritos com noção e impacto?                            |    🟢    |                                                        |
| 13  |                                Os símbolos tem pelo menos uma noção?                                 |    🟢    |                                                        |
| 14  |                                Os símbolos tem pelo menos um impacto?                                |    🟢    |                                                        |
| 15  |                 Se existir símbolos com sinônimos, isso foi devidamente documentado?                 |    🟡    | LE02 possui um erro na escrita no campo de sinônimo    |
| 16  |                                      Os símbolos possuem tipo?                                       |    🟡    | LE02 está sem o tipo/classificação                     |
| 17  |                  Os símbolos pertencem a somente um tipo(VERBO, OBJETO ou ESTADO)?                   |    🟢    |                                                        |
| 18  |    O campo noção dos símbolos do tipo VERBO seguem o modelo "Quem? Quando? Quais procedimento?"?     |    🔴    | Explicação nos comentários                             |
| 19  |               O campo impacto dos símbolos do tipo VERBO explicam os reflexos da ação?               |    🟢    |                                                        |
| 20  |               O campo noção dos símbolos do tipo OBJETO contém uma definição do mesmo?               |    🟢    |                                                        |
| 21  |      O campo impacto dos símbolos do tipo OBJETO descrevem as ações que aquele objeto realiza?       |    🟢    |                                                        |
| 22  |        O campo noção dos símbolos do tipo ESTADO o significado e quando aquele estado ocorre?        |    🟢    |                                                        |
| 23  | O campo impacto dos símbolos do tipo ESTADO mostram quais são os estado decorrentes do estado atual? |    🟢    |                                                        |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Henrique e Chaydson, 2023). </p>
</div>

## Comentários

### ID 18 - O campo noção dos símbolos do tipo VERBO seguem o modelo "Quem? Quando? Quais procedimento?"?

Não foi possível identificar isso na contrução das noções dos símbolos do tipo verbo. No artefato, esses símbolos estão descritos de uma forma extremamente resumida, que dificilmente aborda os 3Qs juntos na mesma noção.

## Resultados

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão:

((100/QntExigencias) _ Acertos) + (((100/QntExigencias) _ Incompletos)/2)

Através dos checklists realizados podemos observar que:

- 19/23 exigências são atendidas;
- 2/23 exigências estão incompletas;
- 2/23 exigências estão erradas ou não foram realizadas.

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 86,94%.

## Bibliografia

SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 14 de junho de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                           | Autor(es)           |
| ------ | ---------- | ----------------------------------- | ------------------- |
| 1.0    | 14/06/2023 | Criação do documento de verificação | Henrique e Chaydson |
