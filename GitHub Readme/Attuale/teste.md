### O que você vai encontrar nesta análise? 👋

Vamos explorar os dados do *Sistema de Informação sobre Nascidos Vivos (SINASC)* relativos aos recém-nascidos nascidos no estado de Rondônia, Brasil, no ano de 2019. Assim que a análise exploratória for concluída, prosseguiremos para identificar insights e avaliar a saúde pública no estado.

Usaremos abordagens estatísticas e analíticas para identificar correlações, padrões e associações entre variáveis, além disso vamos criar um Modelo de Machine Learning para fazer inferências de dados faltantes.

### Os pilares da análise:

- Descobrir os fatores que influenciam a saúde dos bebês.
- Entender melhor as raças e o nível educacional das mães.
- Analisaremos as menores de idade, meninas que constroem família antes dos 18 anos.
- O que nos diz a escolha do parto entre cesariana ou parto vaginal?
- E finalmente melhor compreender a população do estado de Rondônia no Brasil em 2019 e construir a um pouco do que seria o 'Rosto da população'.

> Além disso, exploraremos o impacto das variáveis sociorraciais nas condições de nascimento e nos indivíduos
> 

---

### Contexto dos Dados do SINASC em Rondônia - 2019

O Sistema de Informação sobre Nascidos Vivos (SINASC) é uma base de dados administrada pelo Ministério da Saúde do Brasil, que tem como objetivo coletar e disponibilizar informações detalhadas sobre todos os nascimentos ocorridos no país. No âmbito do estado de Rondônia, o SINASC fornece dados abrangentes e específicos sobre os nascimentos ocorridos no ano de 2019, sendo uma fonte crucial para análises de saúde pública, planejamento e avaliação de políticas sociais.

### Origem dos Dados

Os dados utilizados neste projeto foram extraídos do portal do governo, mais precisamente do Departamento de Informática do SUS (DATASUS). Essa instituição é responsável pela coleta, armazenamento e divulgação das informações de saúde no Brasil, garantindo a integridade e a precisão dos dados disponibilizados.

O conjunto de dados pode ser encontrado no site do governo brasileiro e segue políticas de privacidade, o que significa que não há nomes de pessoas ou qualquer coisa que nos permita saber quem são os indivíduos.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/591dff13-5117-425d-a983-ca995144a283/8baffdca-38ad-4a15-b05f-21d40ba0d34f/image.png)

### Metodologia

A análise será conduzida utilizando técnicas estatísticas e de visualização de dados para identificar padrões e anomalias. Será empregado o Python como ferramentas de manipulação e análise dos dados, na limpeza e preparação dos dados para garantir a qualidade das análises e do modelo de Machine Learning.

### Importância do Projeto

A análise dos dados do SINASC para Rondônia em 2019 é vital para entender melhor as condições de nascimento e saúde materno-infantil no estado. As informações derivadas desse estudo podem auxiliar gestores públicos, pesquisadores e profissionais de saúde na tomada de decisões informadas, visando a melhoria contínua dos serviços de saúde e o bem-estar da população.

Ao fornecer uma visão detalhada sobre os nascimentos, este projeto contribui para um entendimento mais profundo das dinâmicas de saúde e demografia de Rondônia, promovendo ações mais eficazes e direcionadas no campo da saúde pública.

## 🔥 Vamos começar!!!

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/591dff13-5117-425d-a983-ca995144a283/1cc98863-8ff7-4a74-a2e6-611916771926/image.png)

## Como a análise será realizada:

https://media.licdn.com/dms/image/v2/D5612AQEyNedMIW7yaQ/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1721179457444?e=1735776000&v=beta&t=lX72CYo5yDTjJmgFN5Nj7aH7UcsKH9y-gIK87v4TLkE

## O rosto da sociedade

### Nascimentos no ano de 2019:

https://media.licdn.com/dms/image/v2/D5612AQEACiw9c_fGEw/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1721178996817?e=1735776000&v=beta&t=VINzROK-UnpHQz-y9qwmnIh5qViBVjT2GcynUUAXih8

O gráfico mostra a quantidade de nascimentos ao longo do ano de 2019 em Rondônia. O gráfico apresenta flutuações ao longo do ano, com vários picos e vales. Isso sugere que a quantidade de nascimentos variou mês a mês. Os meses com os maiores picos podem indicar períodos de maior atividade de nascimentos, enquanto os vales podem representar momentos de menor atividade.

- **Padrões Sazonais:** Pode ser interessante investigar se existem padrões sazonais. Por exemplo, ***há mais nascimentos em determinadas estações do ano?*** Esses padrões podem estar relacionados a fatores como clima, feriados ou eventos culturais.
- **Eventos Específicos:** Podemos verificar se algum evento específico (como feriados ou datas comemorativas) está correlacionado com os picos de nascimentos.

**Impacto na Saúde Pública:** Essa análise pode ajudar a avaliar a demanda por serviços de saúde materna e neonatal em diferentes momentos do ano. Também pode fornecer insights sobre recursos necessários para atender a essas demandas.

### Nascimentos por sexo do bebê:

https://media.licdn.com/dms/image/v2/D5612AQFoVLVaFlSZpQ/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1721194112669?e=1735776000&v=beta&t=jcRi9eKZX1OPqC_VRxENsYW0QjTSoTPsU9c3-kVWNRQ

- **Comparação:** Comparando as duas linhas, podemos ver que, em geral, a quantidade de nascimentos de meninas parece ser ligeiramente maior do que a de meninos. Essa diferença pode ser explorada em análises mais detalhadas.

### Codições sociorraciais dos bebês:

https://media.licdn.com/dms/image/v2/D4D12AQESVFEcyXtZhA/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1721205453013?e=1735776000&v=beta&t=wM2QejL-7iM-ZpusetOoIfOARhVGDPJqq0hwKH1Ax_w

A população é um aspecto fundamental para entender a dinâmica de uma região. Com base no gráfico, podemos observar a composição racial dos bebês nascidos em Rondônia no ano de 2019.

1. **Parda (74%):** A maior parcela da população é classificada como “Parda”. Isso representa 74% dos bebês nascidos. A categoria “Parda” geralmente inclui pessoas com uma mistura de ascendência étnica, como mestiços.
2. **Branca (21%):** A segunda maior parcela é composta por bebês classificados como “Branca”, representando 21% da população. Essa categoria geralmente inclui bebês de ascendência europeia.
3. **Preta (3%):** A categoria “Preta” representa 3% dos bebês nascidos. Essa categoria inclui bebês de ascendência africana.
4. **Indígena (2%):** A menor parcela é a categoria “Indígena”, representando 2% dos bebês nascidos. Essa categoria inclui bebês de ascendência indígena.

Essa distribuição racial pode fornecer insights importantes para políticas públicas, planejamento de serviços de saúde e promoção da igualdade. É essencial considerar esses dados ao desenvolver estratégias para atender às necessidades específicas de cada grupo racial.

### Distribuição da escolaridade da mãe de acordo com o tom de pele do bebê:

https://media.licdn.com/dms/image/v2/D5612AQGmUBAx3l9JaQ/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1721179913605?e=1735776000&v=beta&t=x_euBmMa7x1an_SKTg-MnsEdO2UG1ZqiuJfvIFkIk1s

O gráfico mostra a distribuição da escolaridade das mães de acordo com o tom de pele dos bebês nascidos no estado.

A escolaridade da mãe é praticamente a mesma, sempre em 8 a 11 anos, mas é preciso ressaltar que as "Brancas" e "Amarelas" têm maior percentual de 12 anos ou mais, enquanto as "Indígenas" têm o menor percentual de 12 anos ou mais e alto percentual de 4 a 7 anos em relação a todos os outras raças

Esses dados são relevantes para entender as desigualdades educacionais e suas implicações nas condições de parto e raças. É importante considerar essas informações ao desenvolver políticas e programas de apoio às mães e bebês.