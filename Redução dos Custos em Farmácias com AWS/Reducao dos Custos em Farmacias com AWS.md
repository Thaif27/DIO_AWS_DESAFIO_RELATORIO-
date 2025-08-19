### *Desafio de Projeto DIO.ME: Redução dos Custos em Farmácias com AWS.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data:  19 de Agosto de 2025. <br>
Empresa: Abstergo Pharmaceutical Industries <br>
Responsável: Thaif Ramon <br>

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa  Abstergo Pharmaceutical Industries, realizado por Thaif Ramon. O objetivo do projeto foi *elencar 3 serviços AWS, com a finalidade de *realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon Lightsail
- É a maneira mais fácil de iniciar e gerenciar um servidor Web usando a AWS por um preço baixo e previsível
- *Descrição de caso de uso*: Ideal para sites criados em pilhas de desenvolvimento como LAMP, LEMP, MEAN, Node.Js e que provavelmente não escalarão além de cinco servidores e para clientes que desejam gerenciar seu próprio servidor Web em um console para gerenciar seu servidor Web, DNS e rede. 

Etapa 2: 
- AWS Cost Explorer + AWS Trusted Advisor
- Monitoramento e análise de gastos em tempo real, com recomendações automatizadas para identificar excessos e recursos ociosos.
- *Descrição de caso de uso*:Indicada para lugares com múltiplos sistemas internos (PDV, ERP, estoque) que somam vários custos mensais na nuvem sem controle. Com o Cost Explorer e o Trusted Advisor, conseguimos identificar gastos desnecessários (como instâncias ligadas após o horário de funcionamento) e gerar alertas automáticos para evitar surpresas na conta. Também é ideal para farmácias que estão migrando para nuvem e precisam acompanhar os gastos progressivamente.
*Como reduz custos*: A farmácia passa a eliminar automaticamente instâncias subutilizadas, desligar servidores fora do horário comercial e receber alertas de gastos inesperados. Isso gera redução imediata nas faturas mensais e cria cultura de otimização.
*Principais ganhos*:
Visibilidade total dos custos por serviço e por setor.
Relatórios automatizados de consumo diário da infraestrutura.
Recomendações práticas como troca de instâncias por versões mais baratas — tudo com poucos cliques.

Etapa 3: 
- Amazon RDS (Aurora Serverless)
-  Banco de dados serverless escalável automaticamente, pagando somente quando há consultas. Ideal para farmácias que têm picos apenas em determinados horários, como fechos de caixa ou sincronização de estoque.
- *Descrição de caso de uso*:Recomendado para lugares com banco de dados que só é acessado com intensidade em horários específicos (ex: vendas em horário comercial, consultas de estoque no fechamento do dia). O Aurora Serverless ativa somente quando há consultas, e entra em modo econômico automaticamente. Elimina a necessidade de manter servidores ligados durante a madrugada ou em horários de baixo movimento.
*Como reduz custos*: Dispensa a necessidade de manter um banco de dados ligado 24h consumindo recursos. O Aurora Serverless cresce e reduz sozinho conforme o uso. Reduz custos com licenças de banco tradicional e com manutenção de servidores físicos.
*Principais ganhos*:
Alta disponibilidade sem precisar configurar infraestrutura complexa.
Banco de dados que “hiberna” quando não está em uso, economizando até 80% do valor mensal.
Backup automatizado, segurança em nível bancário e zero manutenção manual.

ADICIONADA POR MIM - Thaif Ramon (Não sei se poderia ter feito isso.)
Etapa 4:
- Amazon S3 com políticas de ciclo de vida (Lifecycle Policies)
- Armazenamento econômico de imagens de receitas, relatórios médicos, notas fiscais e documentos, com transição automática para camadas mais baratas conforme o tempo.
- *Descrição de caso de uso*:Ideal para farmácias que armazenam digitalmente milhares de receitas médicas digitalizadas, notas fiscais eletrônicas e comprovantes que precisam ficar guardados por anos para fins legais. Ao invés de manter tudo em HD local ou nuvem cara, o S3 permite jogar arquivos recentes na camada padrão e arquivos antigos automaticamente em camadas de arquivamento mais baratas.
*Como reduz custos*: Arquivos mais antigos podem ir automaticamente para S3 Glacier, reduzindo drasticamente o valor de armazenamento a longo prazo. Isso elimina gastos com armazenamento local, HD externo ou servidores internos para arquivos antigos.
*Principais ganhos*:
Armazenamento seguro e criptografado.
Conformidade com LGPD e proteção de dados de clientes.
Economia de até 70% usando regras automáticas de arquivamento.


## Conclusão
A implementação de ferramentas na empresa *Abstergo Pharmaceutical Industries* tem como esperado, no geral, as ferramentas AWS adotadas começam a gerar economia logo nos primeiros meses, principalmente na parte de banco de dados, armazenamento e controle de gastos. A farmácia consegue manter os sistemas rodando com segurança e sem desperdiçar recursos, pagando só pelo que realmente está usando. O mais interessante é que conseguimos reduzir custos sem perder desempenho, e ainda abrimos espaço para crescer facilmente no futuro com o que já está implementado. Com isso, a Abstergo sai na frente na parte tecnológica, com ganhos práticos no dia a dia, menos desperdício e uma infraestrutura pronta para qualquer demanda maior.

## Anexos
[lista de anexos, como manuais, documentos, planilhas, entre outros] <br>
1: https://aws.amazon.com/pt/websites/?nc2=h_ql_sol_use_web <br>
2: https://aws.amazon.com/pt/ec2/?nc2=h_ql_prod_fs_ec2 <br>
3: https://aws.amazon.com/pt/dynamodb/?nc2=h_ql_prod_fs_ddb <br>
4: https://aws.amazon.com/pt/rds/aurora/serverless/ <br>
5: https://aws.amazon.com/pt/aws-cost-management/aws-cost-explorer/ <br>
6: https://aws.amazon.com/pt/aws-cost-management/trusted-advisor/ <br>
7: https://aws.amazon.com/pt/s3/?nc2=h_ql_prod_fs_s3 <br>
8: https://aws.amazon.com/pt/glacier/ <br>
9: https://aws.amazon.com/pt/whitepapers/ (documentação técnica oficial atualizada) <br>
10:https://aws.amazon.com/pt/architecture/ (modelos de arquitetura AWS para farmácias e healthcare) <br>
<br>


#### Assinatura do Responsável pelo Projeto: 
Thaif Ramon 