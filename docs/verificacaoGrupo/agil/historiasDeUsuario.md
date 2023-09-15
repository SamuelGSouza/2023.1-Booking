# Verificação das Histórias de Usuário

## Introdução

O presente documento apresentará a verificação do artefato [Histórias de Usuário](../../modelagem/modelo-agil/historiasDeUsuario.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Histórias de Usuário.

<center>

| Versão avaliada | Autor           | Revisor |
| ---------------- | --------------- | ------- |
| 1.1              | Pedro e Gabriel | Samuel  |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Histórias de usuário. (Fonte: Henrique, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |
| 2 |                    Possui links para os outros artefatos?                    |     🟢     |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟢     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟡     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Henrique, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :--------------------------------------------------------------------------: | :--------: |
| 9 |     Possui rastreabilidade no requisito origem da história de usuário?     |     🟢     |
| 10 |   As histórias de usuário possuem os 3Ws? (quem? / o quê? / por quê?)   |     🟢     |
| 11 | As histórias de usuário estão escritas na perspectiva do usuário final? |     🟢     |
| 12 |              As história de usuário estão claras e concisas?              |     🟢     |
| 13 |         As história de usuário possuem critérios de aceitação?         |     🟢     |
| 14 |       As história de usuário foram validadas com um usuário final?       |     🟡     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Henrique, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                     |
| ------------- | ---------------------------------------------------------- |
| IDC1          | Adicionar gravação da reunião com usuário.             |
| IDC2          | Arrumar numeração das tabelas (existem duas "Tabela 1"). |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Henrique, 2023). </p>
</div>

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Henrique, 2023). </p>
</div>

<center>

| Acrônimo | Descrição                     |
| --------- | ------------------------------- |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Henrique, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 12/14 exigências são atendidas;
- 2/14 exigências estão incompletas;
- 0/14 exigências estão erradas ou não foram realizadas;

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 12},
      {"legenda": "Incompleto", "value": 2},
      {"legenda": "Errado", "value": 0}
    ]
  },
  "mark": {"type": "arc", "innerRadius": 50, "tooltip": true},
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {
      "field": "legenda",
      "type": "nominal",
      "scale": {
        "domain": ["Completo", "Incompleto", "Errado"],
        "range": ["green", "yellow", "red"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Gabriel e Pedro, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 85,71% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                                 |
| ------------- | -------------------------------------- |
| IDC1          | Foi ajustado x realizando...           |
| IDC2          | Foi arrumado a numeração das tabelas |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Pedro e Gabriel, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

Backlog de produto 101: Principais conselhos de especialistas ágeis. Smartsheet. Disponível em: [https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog](https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog). Acesso em: 20 jun. 2023.

Atlassian. Histórias de usuários | Exemplos e template. Disponível em: [https://www.atlassian.com/br/agile/project-management/user-stories](https://www.atlassian.com/br/agile/project-management/user-stories). Acesso em: 20 jun. 2023.

Caroli, P. Histórias do usuário e a construção de produtos de sucesso. Disponível em: [https://caroli.org/historias-do-usuario-e-a-construcao-de-produtos-de-sucesso/](https://caroli.org/historias-do-usuario-e-a-construcao-de-produtos-de-sucesso/). Acesso em: 20 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)         |
| ------- | ---------- | --------------------------------------- | ----------------- |
| 1.0     | 20/06/2023 | Criação do documento de verificação | Henrique e Samuel |

‌
