# Plano de Testes

## Estratégia

Serão realizados testes unitários e funcionais. O objetivo dos testes é assegurar que todas as componentes críticas do sistema, isto é, aquelas que dependem e interagem com a camada de dados e aquelas que realizam e implementam requisitos do sistema funcionem como o previsto.

* Teste Unitário
    
    Teste dos componentes básicos utilizados pelo sistema. Se tratam de testes básicos, que devem garantir apenas que os componentes e métodos fundamentais do sistema estão se comportando da maneira prevista.

    1. Cronograma: Testes unitários serão realizados durante todas as etapas de validação dos componentes do sistema. Toda versão estável e de desenvolvimento deverá passar pelos testes unitários.
    2. Recursos: Esse tipo de teste depende do ambiente de desenvolvimento. Os testes são realizados automaticamente pelo framework de desenvolvimento.


* Teste Funcional

    Teste dos componentes responsáveis por regras e requisitos do sistema.

    1. Cronograma: Testes funcionais serão realizados durante as etapas finais de validação dos componentes do sistema. Toda versão estável deverá passar pelos testes funcionais.
    2. Recursos: Esse tipo de teste depende do ambiente de desenvolvimento e do desenvolvedor do componente a ser testado. Os testes são realizados automaticamente pelo framework de desenvolvimento, mas podem requerer validação humana.
   
   
## Casos de Teste

   Definicão de casos a serem implementados e executados nas rodadas de teste.
   
   * Template de Caso de Teste:
        * Cenário  de teste: verificacão da funcionalidade a ser testada
        * Caso de teste: Caso de uso contemplado
        * Pré-condicoões: requisitos para execucão do teste
        * Etapas de teste: passo a passo da execucão do teste
        * Dados de teste: Dados a serem utilizados nas execucoes dos testes
        * Resultado esperado: deficicão de sucesso do teste
        * Pós-condicões: Estado esperado do sistema
