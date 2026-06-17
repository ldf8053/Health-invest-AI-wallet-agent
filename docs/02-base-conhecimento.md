# Base de Conhecimento

## Dados Utilizados

Descreva se usou os arquivos da pasta `data`, por exemplo:

| Arquivo | Formato | Para que serve a Mari? |
|---------|---------|---------------------|
| `historico_atendimento.csv` | CSV | Contextualizar interações anteriores, dar contintuidade ao atendimento de forma mais pessoal |
| `perfil_investidor.json` | JSON | Personalizar explicações sobre as dúvidas e necessidades de aprendizado do usuário |
| `produtos_financeiros.json` | JSON | Sugerir produtos adequados ao perfil do usuário, para que possam ser explicados ao usuário |
| `transacoes.csv` | CSV | Analisar padrão de gastos em saúde do usuário e usar essas informações de forma didática |

> [!TIP]
> **Quer um dataset mais robusto?** Você pode utilizar datasets públicos do [Hugging Face](https://huggingface.co/datasets) relacionados a finanças, desde que sejam adequados ao contexto do desafio.

---

## Adaptações nos Dados

> Você modificou ou expandiu os dados mockados? Descreva aqui.

Os produtos de saúde, o perfil do usuário e o as transações mensais foram alimentados: lista de academias, dados pessoais e transações de 3 meses foram adicionadas a esses 3 arquivos respectivamente.

---

## Estratégia de Integração

### Como os dados são carregados?
> Descreva como seu agente acessa a base de conhecimento.

[ex: Os JSON/CSV são carregados no início da sessão e incluídos no contexto do prompt]

### Como os dados são usados no prompt?
> Os dados vão no system prompt? São consultados dinamicamente?

[Sua descrição aqui]

---

## Exemplo de Contexto Montado

> Mostre um exemplo de como os dados são formatados para o agente.

```
Dados do Cliente:
- Nome: João Silva
- Perfil: Moderado
- Saldo disponível: R$ 5.000

Últimas transações:
- 01/11: Supermercado - R$ 450
- 03/11: Streaming - R$ 55
...
```
