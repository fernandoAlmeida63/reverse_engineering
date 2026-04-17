# Engenharia Reversa e Refatoração - Sistema de Pedidos

## Parte 01 - Reverse Engineering
A classe original possui a responsabilidade de processar pedidos, incluindo validações, cálculos financeiros e geração de mensagens.

Foram identificadas diversas regras de negócio, como:
- Cálculo de desconto por tipo de cliente
- Cálculo de frete nacional e internacional
- Aplicação de cupons
- Validação de dados do cliente
- Regras de alerta para pedidos suspeitos

## Problemas encontrados
- Método muito grande (God Method)
- Muitos parâmetros
- Uso de strings mágicas
- Alta complexidade e baixa coesão

## Parte 02 - Redocumentação
Foram adicionados comentários explicativos, melhoria de nomes de variáveis e criação de diagrama de classes.

## Parte 03 - Reestruturação
O sistema foi refatorado utilizando:
- Separação de responsabilidades
- Criação de classes específicas
- Retorno estruturado
- Código mais legível e manutenível

## Conclusão
A refatoração melhorou significativamente a clareza, manutenção e escalabilidade do sistema.
