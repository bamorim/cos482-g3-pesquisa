# Casos de Uso #

## Visão geral dos casos de uso ##

```plantuml format="png" classes="uml" alt="Diagrama de Casos de Uso" title="Diagrama de Casos de Uso"
@startuml
left to right direction
skinparam packageStyle rect

!define CREATE(actor,model) actor -down- (Cadastrar model) 
!define READ(actor,model) actor -down- (Visualizar model) 
!define UPDATE(actor,model) actor -down- (Atualizar model) 
!define DESTROY(actor,model) actor -down- (Remover model) 
!definelong CRUD(actor, model)
  CREATE(actor,model)
  READ(actor,model)
  UPDATE(actor,model)
  DESTROY(actor,model)
!enddefinelong

:Membro da Banca: as B
:Professor: as P
:Orientador: as O
:Aluno: as A
:Secretaria: as S

CRUD(S, aluno)
CRUD(S, professor)

A -down- (Escolher professor orientador)
A -down- (Agendar reunião com orientador)
A -down- (Submeter texto para defesa)
A -down- (Agendar seminário)
CRUD(A,publicação)

O -down- (Agendar defesa)
O -down- (Modificar banca da defesa)

P -down- (Confirmar participação na banca)

B -down- (Aprovar defesa)
B -down- (Rejeitar defesa)
@enduml
```
