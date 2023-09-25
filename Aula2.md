# Aula 2

## Investigação de vulnerabilidades
É o processo de encontrar e analisar novas vulnerabilidades através da análise da arquitetura, código ou comportamentos do sistema.

### Auditoria
Determina a conformidade de um standard

### Avaliação
Determina o quão mau/bom algo se encontra

### Teste de penetração
Semelhante à avaliação, mas o o seu foco é analisar a infraestrutura a partir de fora (emula o atacante)

## Defesa de vulnerabilidades

### WAF (Web Application Firewall)
Filtra pedidos HTTP e impede que a execução de pedidos indevidos.

### IDS (Sistema de deteção de intrusão)
Conjunto de ferramentas que monitorizam a rede e alertam sobre possíveis ataques (e.g. Windows Defender).

### Firewall
Dispositivo que controla o tráfego de dados definindo regras de acesso e filtragem de pacotes.

## Tipos de Ataques
Estes são alguns dos tipos de ataques que podem ser feitos a um sistema:
 - Ativos : corre software para descobrir/testar a rede e o sistema
 - Passivos : corre software para monitorizar o tráfego da rede
 - Externos: foca-se em exposições públicas
 - Internos: foca-se em exposições internas
 - Baseados no Host : foca-se nas más configurações/permissões existentes no software
 - Rede: foca-se em comunições das infraestruturas da rede
 - Aplicação: foca-se em explorar vulnerabilidades de aplicações (erros lógicos, autenticação, bases de dados, etc.)
 - Wireless: foca-se em atacar comunições de redes sem fios


## Ciclo de vida de vulnerabilidades
1. Estabelecer as bases: definir os assets e definir prioridades
2. Avaliar vulnerabilidades: procurar vulnerabilidades dentro do scope, contruir um relatório detalhado (responde às perguntas: O que foi encontrado? Quais são as entidades afetadas? Quais são as recomendações para tradar do mesmo?) sem necessariamente explorar essa vulnerabilidade num todo (não é um teste de penetração)
3. Avaliar risco: quantificar o impacto que um determinado risco tem, para melhor decidir qual vulnerabilidade priorizar.
4. Remedição: corrigir ou minimizar o impacto das vulnerabilidades que encontram-se no software
5. Verificação: verificação da eficácia das correções feitas
6. Monitorização: analisar algumas falhas que não foram ou foram corrigidas (pode envolver configuração de firewalls, IDS/NIDS/HIDS)