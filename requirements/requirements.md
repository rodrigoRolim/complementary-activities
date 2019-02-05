Módulo de Professor
===
###Requisitos funcionais 
|ID|NOME|DESCRIÇÃO|
|--|----|---------|
|RF001|Cadastrar Professor|O professor responsável pela disciplina de Atividade Complementares será cadastrado no sistema pelo administrador do sistema.|
|RF002|Excluir Professor|O sistema deve fornecer a opção de exclusão de um professor cadastrado. Somente o usuário administrador poderá fazer a exclusão|
|RF003|Alterar dados do Professor| O sistema deve permitir que o professor possa alterar seus dados cadastrados no sistema quando quiser|
|RF004|Avaliar Documentos|O professor responsável deve avaliar o documento aprovando-o ou não, conforme as regras de negócio|
|RF005|Receber documentos enviados por alunos|O Professor responsável recebe os documentos enviados pelos alunos|

###Regras de negócio
|ID|NOME|DESCRIÇÃO|
|--|--|--|
|RN001|Verificação de validade de documento enviado pelo aluno|Ao avaliar um documento enviado por um aluno, o professor deve fazê-lo conforme as normas que regulamentam as atividades complementares da UTFPR. O professor deve verificar se o documento atende aos critérios estabelecidos neste regulamento. Se atender, o documento é aprovado, senão, é reprovado.|
|RN002|Validação de professor que solicitar login no sistema|Somente um professor já pre-cadastrado pelo administrador poderá acessar o sistema. Após entrar no sistema, o professor poderá completar o seu cadastro, preenchendo adequadamente os seus dados|
|RN003|
