Neste projeto desenvolvi um formulário de cadastro de aluno utilizando HTML. O formulário coleta informações básicas como nome, e-mail, CPF, data de nascimento, curso e turno.

Para organizar melhor os campos utilizei a tag <fieldset> com <legend>, separando o formulário em seções como dados de cadastro, turno, termos de envio e envio do formulário.

Também associei todas as <label> aos respectivos <input> utilizando os atributos for e id, o que melhora a acessibilidade e a usabilidade da página.

Alguns campos possuem validação diretamente no HTML. Utilizei required para tornar campos obrigatórios, type="email" para validar o formato do e-mail e pattern para exigir que o CPF seja digitado no formato correto (000.000.000-00). Além disso, usei placeholder e inputmode="numeric" para facilitar o preenchimento.

O campo de curso foi implementado com <select> para evitar erros de digitação, e o turno foi feito com radio para permitir apenas uma escolha. Também adicionei um checkbox obrigatório para garantir que o usuário aceite os termos antes de enviar o formulário.

Por fim, incluí botões para enviar os dados ou limpar o formulário.
