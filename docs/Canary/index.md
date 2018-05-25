### Canary

##### a.k.a A/B

O Deploy da nova versão é feito em metade dos recursos, sem que eles estejam disponíveis para os usuários.
A nova versão é testada e se estiver tudo ok, é feito o chaveamento dos usuários gradual ou de apenas parte deles.
Muito comum para testes de aceitação e liberação de mudanças criticas tanto de usabilidade quanto novos recursos para atendimento de RNF.

É a estratégia mais segura, mas também é uma das mais caras. 

#### Concorrência de versão
Há 2 (ou mais) versões do código em produção e a decisão de quando será feito o chaveamento total dos usuários para a nova versão depende de métricas e avaliação de objetivo.
É feito um roteamento inteligente dos usuários, dado critérios estebelecidos juntamente com as metas dos testes. 
    
#### Roll Back

O Rollback, em geral, é apenas desligar a condição de roteamento dos usuários, fazendo com que todos voltem para a "versão estável".
    
 
