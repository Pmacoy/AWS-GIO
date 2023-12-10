# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 09/10/2023
Empresa: Abstergo Industries
Responsável: Paulo A Julio

# Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsável pelo projeto]. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

# Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: - Gerenciamento de identidade e acesso- O AWS Identity Services ajuda você a gerenciar com segurança identidades, recursos e permissões em grande escala. Com a AWS, você tem serviços de identidade para sua força de trabalho e aplicações voltadas para o cliente para começar rapidamente e gerenciar o acesso às suas workloads e aplicações. 

Medida 2: - CloudTrail - Log e o monitoramento são partes importantes de um plano de segurança robusto. Ser capaz de investigar alterações inesperadas em seu ambiente ou realizar análises para iterar sua postura de segurança depende de ter acesso aos dados. A AWS recomenda que você grave logs, especialmente do AWS CloudTrail, em um bucket do S3 em uma conta da AWS designada para registro em log (Log Archive). As permissões no bucket devem impedir a exclusão dos logs e também devem ser criptografadas em repouso. Depois que os logs estiverem centralizados, você poderá se integrar com soluções SIEM ou usar os serviços da AWS para analisá-los.

Medida 3: - IAM Roles - À medida que você opera suas contas da AWS para criar recursos, você pode acabar criando várias IAM Roles que você descobre mais tarde que não precisa. Use o AWS IAM Access Analyzer  para analisar o acesso aos recursos internos da AWS e determinar onde você tem acesso compartilhado fora de suas contas da AWS. A reavaliação rotineira das roles e permissões do AWS IAM com o Security Hub ou produtos de código aberto, como Prowler, lhe dará a visibilidade necessária para validar a conformidade com suas políticas de governança, risco e conformidade (GRC). Se você já ultrapassou esse ponto e já criou várias funções, você pode pesquisar funções do IAM não utilizadas e removê-las.

# Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado gerenciar com segurança identidades, investigar e analisar alterações inesperadas em seu ambiente . analisar e alterar o acesso aos recursos internos da AWS o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

# Anexos

https://aws.amazon.com/pt/iam/?gclid=Cj0KCQiA4NWrBhD-ARIsAFCKwWtOfqRu3Se8AIocZf_4rBUw7MYdw0lfZzoWW3dK3RxEo9n9iRWiFCkaAp_YEALw_wcB&trk=6c16af2d-a3a1-477e-8969-4ba28eb8be90&sc_channel=ps&ef_id=Cj0KCQiA4NWrBhD-ARIsAFCKwWtOfqRu3Se8AIocZf_4rBUw7MYdw0lfZzoWW3dK3RxEo9n9iRWiFCkaAp_YEALw_wcB:G:s&s_kwcid=AL!4422!3!651612452798!p!!g!!iam!19835790863!149589220720

https://aws.amazon.com/pt/iam/?gclid=Cj0KCQiA4NWrBhD-ARIsAFCKwWtx_81bPh7bREr4dX5Ex_9u-Soflh3hEQpCHOHA7To8Mkbfa0MwPoUaAq6NEALw_wcB&trk=6c16af2d-a3a1-477e-8969-4ba28eb8be90&sc_channel=ps&ef_id=Cj0KCQiA4NWrBhD-ARIsAFCKwWtx_81bPh7bREr4dX5Ex_9u-Soflh3hEQpCHOHA7To8Mkbfa0MwPoUaAq6NEALw_wcB:G:s&s_kwcid=AL!4422!3!651612452795!e!!g!!amazon%20iam!19835790863!149589220680

https://aws.amazon.com/pt/cloudtrail/

Assinatura do Responsável pelo Projeto:

Paulo A Julio