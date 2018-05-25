### Rolling Up

##### a.k.a Gradual Deployment

Gradualmente, máquina a máquina, fazer o upgrade dos servidores.

#### Concorrência de versão
* Há um momento de transição em que 2 versões ficam disponíveis ao mesmo tempo
    * Dados precisam se manter consistentes (Retrocompatibilidade);
    * Usuário não deve(ria) acessar hora uma versão, hora outra versão.
    
#### Roll Back

* Se um dos nós sofrer algum problema durante a atualização, é possível que seja feito o rollback das máquinas atualizadas e assim poder investigar os problemas. Como os dados são consistentes e retro-compatíveis, não há problema em voltar as máquinas para a última versão estável.
    
 
