
# Dicionário de Dados: Meios de Pagamentos Trimestrais - Banco Central do Brasil

Este documento descreve os campos de dados que fazem parte do **ETL** referente ao **Banco Central do Brasil**, especificamente sobre o **Volume e Quantidade de Meios de Pagamento Trimestrais**. As informações detalhadas abaixo indicam os valores e as quantidades de transações realizadas trimestralmente com diferentes meios de pagamento no país. 

## Campos e Descrições

| Nome do Campo                     | Tipo      | Título                                | Descrição                                                                 |
|------------------------------------|-----------|---------------------------------------|---------------------------------------------------------------------------|
| **datatrimestre**                  | Texto     | Trimestre                             | Trimestre de referência da coleta de dados.                              |
| **valorPix**                       | Decimal   | Valor Pix                             | Volume financeiro (em milhões de R$) de transações Pix realizadas, tanto no SPI quanto fora do SPI, incluindo ordens de pagamento e devoluções. Note que os dados sobre transações fora do SPI podem ser alterados retroativamente conforme as informações dos participantes. |
| **valorTED**                       | Decimal   | Valor TED                             | Volume financeiro (em milhões de R$) referente às transferências realizadas via TED. TED (Transferência Eletrônica Direta) permite transferências financeiras entre diferentes instituições em tempo real. |
| **valorTEC**                       | Decimal   | Valor TEC                             | Volume financeiro (em milhões de R$) referente às transferências realizadas via TEC. TEC (Transferência Especial de Crédito) é usada principalmente para pagamentos de benefícios aos empregados. |
| **valorCheque**                    | Decimal   | Valor Cheque                          | Volume financeiro (em milhões de R$) referente a cheques interbancários e intrabancários compensados. |
| **valorBoleto**                    | Decimal   | Valor Boleto                          | Volume financeiro (em milhões de R$) referente aos boletos interbancários e intrabancários compensados. |
| **valorDOC**                        | Decimal   | Valor DOC                             | Volume financeiro (em milhões de R$) referente às transferências realizadas via DOC (Documento de Ordem de Crédito). |
| **valorCartaoCredito**             | Decimal   | Valor Cartão de Crédito               | Volume financeiro (em milhões de R$) referente às transações realizadas com cartões de crédito. |
| **valorCartaoDebito**              | Decimal   | Valor Cartão de Débito                | Volume financeiro (em milhões de R$) referente às transações realizadas com cartões de débito. |
| **valorCartaoPrePago**             | Decimal   | Valor Cartão Pré-pago                 | Volume financeiro (em milhões de R$) referente às transações realizadas com cartões pré-pagos. |
| **valorTransIntrabancaria**        | Decimal   | Valor Transferência Intrabancária     | Volume financeiro (em milhões de R$) referente a transferências realizadas entre contas do mesmo banco, incluindo aplicações e resgates de fundos de investimento. |
| **valorConvenios**                 | Decimal   | Valor Convênios                       | Volume financeiro (em milhões de R$) referente à arrecadação de tributos ou encargos sociais através de convênios firmados, tanto com entidades governamentais quanto não-governamentais. |
| **valorDebitoDireto**              | Decimal   | Valor Débito Direto                   | Volume financeiro (em milhões de R$) referente a débitos autorizados pelo cliente em sua conta, incluindo pagamentos de contas recorrentes e tarifas de serviços bancários. |
| **valorSaques**                    | Decimal   | Valor Saque                           | Volume financeiro (em milhões de R$) referente a saques realizados em caixas eletrônicos. |
| **quantidadePix**                  | Decimal   | Quantidade Pix                        | Quantidade (em milhares) de transações Pix realizadas, tanto no SPI quanto fora dele, incluindo ordens de pagamento e devoluções. |
| **quantidadeTED**                  | Decimal   | Quantidade TED                        | Quantidade (em milhares) de transações TED realizadas trimestralmente. |
| **quantidadeTEC**                  | Decimal   | Quantidade TEC                        | Quantidade (em milhares) de transações TEC realizadas trimestralmente. |
| **quantidadeCheque**               | Decimal   | Quantidade Cheque                     | Quantidade (em milhares) de cheques compensados, tanto interbancários quanto intrabancários. |
| **quantidadeBoleto**               | Decimal   | Quantidade Boleto                     | Quantidade (em milhares) de boletos compensados, tanto interbancários quanto intrabancários. |
| **quantidadeDOC**                  | Decimal   | Quantidade DOC                        | Quantidade (em milhares) de transações realizadas via DOC. |
| **quantidadeCartaoCredito**        | Decimal   | Quantidade Cartão de Crédito          | Quantidade (em milhares) de transações realizadas com cartões de crédito. |
| **quantidadeCartaoDebito**         | Decimal   | Quantidade Cartão de Débito           | Quantidade (em milhares) de transações realizadas com cartões de débito. |
| **quantidadeCartaoPrePago**        | Decimal   | Quantidade Cartão Pré-pago            | Quantidade (em milhares) de transações realizadas com cartões pré-pagos. |
| **quantidadeTransIntrabancaria**   | Decimal   | Quantidade Transferência Intrabancária | Quantidade (em milhares) de transferências realizadas entre contas do mesmo banco. |
| **quantidadeConvenios**            | Decimal   | Quantidade Convênios                  | Quantidade (em milhares) de transações realizadas no âmbito de convênios governamentais ou privados. |
| **quantidadeDebitoDireto**         | Decimal   | Quantidade Débito Direto              | Quantidade (em milhares) de débitos autorizados pelo cliente para pagamento de contas ou tarifas. |
| **quantidadeSaques**               | Decimal   | Quantidade de Saque                   | Quantidade (em milhares) de saques realizados em caixas eletrônicos. |

---

### Detalhes Importantes
- As informações relativas a transações realizadas fora do **SPI** (Sistema de Pagamentos Instantâneos) podem ser alteradas retroativamente, pois dependem da comunicação dos dados pelos participantes do sistema.
- Os valores e quantidades referem-se ao montante ou à quantidade de transações realizadas durante o **trimestre** de referência.

### Fonte dos Dados
Os dados são coletados e fornecidos pelo **Banco Central do Brasil** e podem ser acessados através da plataforma oficial de dados abertos.

---

Este README apresenta uma visão geral dos campos disponíveis sobre os meios de pagamento no Brasil, com base nos dados trimestrais divulgados pelo Banco Central. Fique à vontade para entrar em contato caso precise de mais informações ou explicações sobre esses dados!
