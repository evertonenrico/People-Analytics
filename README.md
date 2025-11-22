
# People Analytics

Dashboard desenvolvido para People Analytics em Power BI consultando diretamente um banco de dados SQL Server.


## Sobre
Um dashboard de People Analytics é uma ferramenta poderosa que fornece insights valiosos sobre o capital humano de uma organização. 

Esses dashboards são projetados para transformar dados de recursos humanos em visualizações claras e acionáveis, permitindo que as empresas tomem decisões informadas sobre sua força de trabalho. Geralmente, eles incluem métricas relacionadas ao recrutamento, desempenho, engajamento e desenvolvimento dos colaboradores.
## Objetivo
 A proposta é desenvolver um dashboard utilizando a ferramenta Power BI da Microsoft®, onde será feita a coleta dos dados do sistema ERP e inserir em um banco de dados Data Warehouse na linguagem MySQL®.

 O objetivo a princípio é ter as informações básicas dos colaboradores da empresa em um dashboard atualizado mensalmente, tais como: idade, sexo, quantidade de colaboradores ativos no total e por departamento, contratações no mês, demissões no mês, demissões inferiores a 90 dias, contratos ativos e headcount.

## 🛠 Ferramentas utilizadas
Power BI, MySQL, Pentaho Data Integration, Excel

## Telas do projeto

Contratações Gerais
![App Screenshot](https://i.ibb.co/qRWKnRQ/tela-001.png)

Má Contratações
![App Screenshot](https://i.ibb.co/714rWFf/tela-002.png)

Afastamentos
![App Screenshot](https://i.ibb.co/HT3yM9V/tela-003.png)

Saúde Profissional
![App Screenshot](https://i.ibb.co/fH3HC5N/tela-004.png)



## Medidas utilizadas

- Contratações ativas: Qtde de funcionários ativos na empresa;
- Contratações distintas: Total de contratações realizadas por CPF;
- Demissões distintas: Total de demissões realizadas por CPF;
- Má contratações: Demissões realizadas em até 90 dias após contratação;
- Headcount por contratos: Evolução de contratações por contratos(Um CPF pode ser contratado em mais de uma empresa)
- Total de Contratos Ativos: Total de contratações por contratos, um CPF pode ter mais de um contrato;
- Total de Contratos Inativos: Total de demissões por contratos, um CPF pode ter mais de um contrato;



## Autor

- [@evertonenrico](https://www.github.com/evertonenrico)
