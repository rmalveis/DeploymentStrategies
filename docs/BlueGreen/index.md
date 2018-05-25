### Blue / Green

##### a.k.a Red/Black, Staged deployment

O Deploy da nova versão é feito em metade dos recursos, sem que eles estejam disponíveis para os usuários.
A nova versão é testada e se estiver tudo ok, é feito o chaveamento dos usuários.

É a estratégia mais segura, mas também é uma das mais caras. 

#### Concorrência de versão
* Draining:
    * Usuários são migrados conforme seus requests são respondidos. 
    
#### Roll Back

A Metade dos recursos que não foi atualizada é mantida intacta por algum tempo para eventual rollback. Neste caso, sendo necessário, é feito o roteamento dos usuários novamente e eles voltam pra versão anterior.
    
 
