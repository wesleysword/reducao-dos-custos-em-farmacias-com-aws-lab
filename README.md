# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 19/07/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Wesley Oliveira  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos. A escolha dos serviços foi baseada na documentação oficial da AWS, priorizando soluções que otimizam recursos, reduzem despesas operacionais e aumentam a eficiência dos processos da empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:**  
- **Nome da ferramenta:** AWS Cost Explorer  
- **Foco da ferramenta:** Gerenciamento e otimização de custos  
- **Descrição de caso de uso:**  
  O AWS Cost Explorer foi implementado para permitir a visualização detalhada dos custos e uso dos serviços AWS em tempo real. A ferramenta foi utilizada para identificar áreas de gastos excessivos, como instâncias subutilizadas do Amazon EC2 e armazenamento não otimizado no Amazon S3. Relatórios personalizados foram gerados para monitorar despesas mensais, resultando em uma redução de 15% nos custos operacionais após a identificação e eliminação de recursos ociosos.

**Etapa 2:**  
- **Nome da ferramenta:** Amazon EC2 Auto Scaling  
- **Foco da ferramenta:** Escalabilidade e eficiência de recursos computacionais  
- **Descrição de caso de uso:**  
  O Amazon EC2 Auto Scaling foi configurado para ajustar automaticamente a quantidade de instâncias EC2 com base na demanda das aplicações da Abstergo Industries. Durante picos de tráfego, o serviço adiciona instâncias para garantir desempenho, enquanto em períodos de baixa demanda, reduz o número de instâncias para minimizar custos. Essa implementação reduziu os gastos com computação em 20%, mantendo a disponibilidade das aplicações críticas da empresa.

**Etapa 3:**  
- **Nome da ferramenta:** AWS Trusted Advisor  
- **Foco da ferramenta:** Recomendações de melhores práticas e economia  
- **Descrição de caso de uso:**  
  O AWS Trusted Advisor foi adotado para fornecer recomendações em tempo real sobre otimização de custos, segurança e desempenho. A ferramenta identificou configurações ineficientes, como políticas de acesso excessivamente permissivas no IAM e snapshots antigos no EBS, que foram corrigidos. Com base nas sugestões do Trusted Advisor, a empresa conseguiu economizar 10% adicionais nos custos de armazenamento e melhorar a conformidade com as melhores práticas da AWS.

## Anexos
- Manual de Configuração do AWS Cost Explorer (PDF)  
- Relatório de Escalabilidade do Amazon EC2 Auto Scaling (Planilha Excel)  
- Checklist de Recomendações do AWS Trusted Advisor (Documento Word)  
- Documentação Oficial AWS: [AWS Cost Explorer](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html), [Amazon EC2 Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html), [AWS Trusted Advisor](https://docs.aws.amazon.com/awssupport/latest/user/trusted-advisor.html)  

**Assinatura do Responsável pelo projeto:**  
Wesley Oliveira
