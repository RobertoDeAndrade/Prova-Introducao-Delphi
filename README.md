# Prova de introdução ao Delphi
Prova do módulo de introdução ao Delphi do curso Tech4me.  

Projeto Delphi – Windows VCL: Calculadora de Média Escolar  

Crie um aplicativo VCL que receba três notas, calcule a média aritmética ao clicar em um botão e exiba a situação do aluno: Aprovado, Recuperação ou Reprovado.  

Critérios de avaliação por média
Média ≥ 7,0: Aprovado  
Média entre 5,0 e 6,9: Recuperação  
Média < 5,0: Reprovado  

Interface do formulário (VCL)  
Campos para o usuário digitar três notas (ex.: TEdit)  
Um botão para Calcular Média (ex.: TButton)  
Área para exibir a média e o resultado (ex.: TLabel)  

Funcionalidade esperada  
Ler as três notas inseridas pelo usuário  
Calcular a média aritmética  
Exibir a média e a situação (Aprovado, Recuperação ou Reprovado)  

Validações mínimas  
Aceitar apenas valores numéricos entre 0 e 10  
Exibir mensagens de erro para campos vazios ou valores inválidos  
Sugestão: usar TryStrToFloat e checar faixa (0..10) antes do cálculo.  

Dicas de implementação (evento do botão)  
Converter texto das notas para número; validar cada uma  
Média: (n1 + n2 + n3) / 3 com duas casas decimais  
Decidir situação com if/else nos intervalos informados  
Exibir média e situação nos TLabel da tela  
