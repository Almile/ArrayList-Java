# ArrayList

## Instruções
Atualize o sistema de cadastro de alunos para incluir funcionalidades de atualização e exclusão de registros no JFrame2.

Objetivo
Adicionar funcionalidades para que o usuário possa atualizar as informações de um aluno existente ou removê-lo da lista de registros diretamente na Tela de Visualização (JFrame2).


Requisitos do Exercício

### Funcionalidade de Atualização de Aluno:


No JFrame2, ao selecionar um aluno no JComboBox, seus dados (nome e telefone) devem ser exibidos nos campos correspondentes.

O usuário deve poder editar o nome ou telefone nos campos exibidos.

Adicione um botão "Atualizar" que, ao ser clicado, salva as alterações feitas no nome ou telefone do aluno selecionado.

Exiba uma mensagem de confirmação informando que o aluno foi atualizado com sucesso.


### 2. Funcionalidade de Exclusão de Aluno:


No JFrame2, adicione um botão "Excluir" que permita remover o aluno selecionado da lista.

Antes de excluir, exiba uma mensagem de confirmação (usando JOptionPane) para que o usuário confirme a exclusão do aluno.

Caso o usuário confirme, remova o aluno da lista e atualize o JComboBox para refletir a mudança.



### 3. Validações e Feedback:

Certifique-se de que o botão "Atualizar" só está ativo se um aluno estiver selecionado e se houver alterações nos campos.

Após uma exclusão ou atualização, os campos nomeField e telefoneField devem ser limpos automaticamente.

Exiba mensagens de feedback apropriadas para cada operação (sucesso na atualização ou exclusão).


### 4. Considerações

Utilize JOptionPane para exibir mensagens de confirmação e feedback.

Certifique-se de que as operações não gerem inconsistências na lista e que o JComboBox seja atualizado corretamente após cada exclusão ou atualização.
