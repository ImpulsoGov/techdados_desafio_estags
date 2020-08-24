# Desafio ImpulsoGov | Estágio Tech & Dados 🎲

## Instruções gerais
Este arquivo contém as instruções para os desafios das vagas de estágio em **Desenvolvimento** e **Modelagem e Análise de Dados** - escolha uma das vagas para entregar seu desafio. Ambos os desafios são compostos de 2 questões, uma descritiva e outra na qual você .

### Avisos importantes ‼️
- A ImpulsoGov repudia qualquer forma de cópia de código sem as devidas referências à fonte - esperamos bom senso quanto à utilização de trechos de códigos de outrem;
- Os dados fornecidos aqui são de propriedade da ImpulsoGov;
- Esta é uma fase eliminatória do processo seletivo;
- **Seu desafio deve ser implementado num repositório *privado* e enviado no [formulário](https://docs.google.com/forms/d/e/1FAIpQLSczTlU6Nz6oLHazaYSGAViEwabRaNEwSViYv3T7UBh61Qjvrw/viewform) até domingo (30/08/2020), às 23:59**. Uma vez preenchido o formulário, nós enviaremos um email com a confirmação do recebimento.
- O repositório deve estar compartilhado com os emails: 
  - anapaula@impulsogov.org
  - dandara@impulsogov.org
  - fernanda@impulsogov.org


---

## Desafio Dev ⚙️

Responda **ambas** as perguntas abaixo em seu repositório - a primeira somente descritiva (*responder em seu README*), a segunda deve ser implementada num *script em Python*.

#### 1. Como comparar municípios? (descritiva)

Imagine que um gestor público entra hoje no Farol e quer ter a possibilidade de comparar seu município com outros municípios de seu interesse. Com base no que implementamos até hoje no [código do Farol](https://github.com/ImpulsoGov/farolcovid), o que você faria para adicionar essa comparação na ferramenta? Nos descreva o passo a passo e a lógica por trás do código: Como apresentaria essa informação? Quais elementos e funções que já temos hoje você usaria? Quais novas funções você criaria?

- Responda esta pergunta de forma descritiva em seu *README*.


#### 2. Que tal coletar dados de testagem da Covid-19? (Python script)

O Ministério da Saúde disponibiliza hoje em sua [Plataforma Integrada de Vigilância em Saúde](http://plataforma.saude.gov.br/coronavirus/virus-respiratorios/) os dados de testagem dos estados brasileiros. O nível de testagem de um estado é uma variável improtante para determinar o quanto de controle ele tem sobre como a doença está disseminada em sua população. Esta plataforma contém os dados sobre testes RT-PCR realizados em todos os estados até hoje. Você deve criar um script que realiza a raspagem dos dados de exames por estado. 

- Implemente este desafio num script chamado `app.py` em seu repositório.
- **Seu script `app.py` deve ter uma função principal que recebe a URL e retornar uma série com o percentual de resultados Posivito/Detectável por estados.** Esta função deve já ser chamada no próprio script para testarmos.
- Para avaliação final iremos rodar seu código em https://repl.it/, sugerimos que teste previamente a plataforma.
- O código deve rodar em Python 3.8.2.


Para conhecer:
- GAL: Sistema Gerenciador de Ambiente Laboratorial (mais sobre o [GAL](http://gal.datasus.gov.br/GALL/index.php)).
- RT-PCR: teste que identifica a presença do RNA do vírus SARS-Cov-2 no organismo no momento de realização do exame (mais sobre [testes](https://coronacidades.org/como-fazer-o-melhor-uso-de-testes-para-covid-19-sugestoes-para-a-gestao-municipal/)).


### O que estamos avaliando

- Familiaridade com GitHub e Python
- Entendimento de fluxo e processos
- Estrutura e qualidade do código
- Limpeza e tratamento dos dados
- Criatividade

---

## Desafio Modelagem & Análise 📊

Responda **ambas** as perguntas abaixo em seu repositório - a primeira somente descritiva (*responder em seu README*), a segunda deve ser implementada num *Jupyter notebook em Python*.

#### 1. Como comparar municípios? (descritiva)

Imagine que um gestor público entra hoje no Farol e quer ter a possibilidade de comparar seu município com outros municípios de seu interesse. (a) Como você selecionaria municípios para comparação? Descreva quais caracaterísticas você selecionaria para definir municípios semelhantes. (b) Descreva 2 (duas) análises ou visualizações que você montaria para comparar a situação entre esses municípios.

- Responda esta pergunta de forma descritiva em seu *README*.


#### 2. Como você montaria um dashboard para a gestão municipal? (Jupyter notebook)
Um(a) gestor(a) público(a) conta com você para construir um dashboard de monitoramento que mostre a situação de seu município. Quais informações devem ser acompanhadas, e como você as apresentaria? Elabore um conjunto análises e visualizações com as principais informações para esse(a) gestor(a) de 1 (um) município a sua escolha, utilizando os dados do FarolCovid e Saúde em Ordem (ambos em nossa [ferramenta](https://farolcovid.coronacidades.org/) ou use nossa [API](https://github.com/ImpulsoGov/coronacidades-datasource) se preferir).

- Implemente este desafio num Jupyter notebook em seu repositório.
- **Seu notebook deve conter no máximo 5 visualizações.**
- **Todos os gráficos devem conter legenda e título. Junto a ele deve conter uma breve explicação da análise apresentada em Markdown**.

Para conhecer:
- O FarolCovid reúne indicadores com base em dados abertos para monitoramento da situação da Covid-19 em municípios e estados.
- O Saúde em Ordem é uma ferramenta inserida no FarolCovid que possibilita ao(à) gestor(a) público(a) a visualização de quais setores reabrir primeiro em seu estado.
- Você tem total liberdade para enriquecer suas análises com dados de outras fontes - citando suas devidas referências.

Esperamos um código bem documentado, com a descrição da análise realizada e tópicos principais encontrados. Queremos entender o passo-a-passo do seu raciocínio, não apenas os resultados.


### O que estamos avaliando

- Familiaridade com GitHub e Python
- Capacidade analítca
- Tratamento e visualização de dados
- Estrutura e qualidade do código
- Criatividade