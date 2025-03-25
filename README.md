# Projeto_WBK
 
A WBK  **é uma empresa fictícia** especializada em empréstimos, com foco na facilidade e agilidade para seus clientes. Todo o processo de solicitação e gestão de empréstimos é otimizado para ser realizado de forma rápida e prática via dispositivos móveis, oferecendo a melhor experiência ao usuário.

O objetivo da empresa é fornecer o maior número possível de informações sobre os empréstimos, garantindo total transparência para seus clientes. No entanto, a inadimplência tem sido uma grande preocupação para a WBK. Atualmente, a taxa de inadimplência está em 35%, e a empresa busca implementar técnicas de análise para reduzir esse percentual para 25% ou menos.

Para isso, fui responsável pela análise dos dados históricos de empréstimos, fornecidos pela empresa. O banco de dados contém informações detalhadas sobre os últimos empréstimos concedidos, e com base nesses dados, a análise de inadimplência será realizada, utilizando técnicas de modelagem preditiva e análise estatística.

Dicionário dos dados
1. ID : Identificador Único do cliente
2. Duracao : Duração do empréstimo (Em meses)
3. HistoricoCredito : Não foi definido no banco de dados
4. Proposito : Não foi definido no banco de dados
5. Valor : Valor em reais do Empréstimo
6. Investimentos : Quantidade de investimentos do cliente
7. Emprego : Não foi definido no banco de dados
8. TempoParcelamento : O tempo do parcelamento do empréstimo (Em anos)
9. EstadoCivil : Estado Civil do cliente: Solteiro (1), Viúvo (2), Divorciado (3) ou Casado (4)
10. FiadorTerceiros : Bancos e Instituições Financeiras (1), Seguradora (2), Pessoa Física (3) ou Pessoa Jurídica (4)
11. ResidenciaDesde : Quantidade de anos que o cliente mora em sua residência
12. Idade : A idade do cliente
13. OutrosFinanciamentos : Não foi definido no banco de dados
14. Habitacao : Quantidade de habitações do cliente
15. EmprestimoExistente : Quantidade de Empréstimos atuais do cliente
16. Profissao : Profissão do cliente (O tipo é numérico por conta do modelo de ML só identificar tipos numéricos)
17. Dependentes : Quantidade de dependentes do cliente
18. SocioEmpresa : Cliente sócio de empresa? Sim (1) ou Não (0)
19.Estrangeiro : Cliente estrangeiro? Sim (1) ou Não (0)
20. Status : Adimplente (1) ou Inadimplente (0)
