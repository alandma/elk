# ELK Stack: Elasticsearch, Logstash e Kibana

A stack é a ELK, Ela é composta das seguintes aplicações:

- ElasticSearch
  - O Elasticsearch é um mecanismo de busca e análise.
- Logstash
  - O Logstash é um pipeline de processamento de dados do lado do servidor que faz a ingestão de dados a partir de inúmeras fontes simultaneamente, transforma-os e envia-os para um "esconderijo" como o Elasticsearch.
- Kibana
  - O Kibana permite que os usuários visualizem dados com diagramas e gráficos no Elasticsearch.

## Variaveis do arquivo ".env"

O arquivo contem as variaveis utilizadas no `docker-compose.yml`.

_IP_ELASTICSEARCH_

Nessa variavel pode-se definir o IP do servidor que irá receber o elasticsearch.

_TAG_ELK_

Essa variavel define a versão da stack ELK, ela sempre deve ser a mesma versão para os três.

## Executando

```bash
docker-compose up -d --build
```
