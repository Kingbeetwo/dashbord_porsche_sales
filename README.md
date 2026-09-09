# Porsche Sales Dashboard

Dashboard interativo em HTML para análise de vendas de veículos Porsche, desenvolvido com uma identidade visual elegante inspirada no site oficial da Porsche Brasil.

## Funcionalidades

- Filtro por modelo Porsche;
- Filtro por ano do modelo;
- Filtro por cidade;
- Filtro por forma de pagamento;
- Filtro por período;
- Quantidade total de vendas;
- Receita total e ticket médio;
- Identificação do modelo e do ano mais vendidos;
- Ranking dos modelos;
- Cidades com maior volume de vendas;
- Forma de pagamento mais utilizada;
- Gráfico de evolução mensal das vendas;
- Insights automáticos atualizados conforme os filtros.

## Dados

O dashboard utiliza exclusivamente os campos tratados da planilha original. Registros com datas inválidas permanecem nos indicadores gerais, mas são desconsiderados no gráfico de evolução temporal.

Os valores monetários são apresentados em dólares americanos (USD), conforme a base fornecida.

## Como visualizar

Você pode abrir o arquivo [index.html](./index.html) diretamente em qualquer navegador moderno.

Também é possível publicar o dashboard gratuitamente pelo GitHub Pages:

1. Abra **Settings** no repositório;
2. Acesse **Pages**;
3. Em **Source**, selecione **Deploy from a branch**;
4. Escolha a branch **main** e a pasta **/root**;
5. Clique em **Save**.

Após o processamento, o GitHub apresentará o endereço público do dashboard.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- SVG para visualização do gráfico evolutivo

## Estrutura

```text
.
├── index.html
└── README.md
```

O projeto foi estruturado como um arquivo HTML independente, com os estilos, dados sumarizados e interações incorporados no próprio documento.
