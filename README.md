# facerec


Projeto de identificação de faces e também de outros objetos usando técnica das eigenfaces.

## As pricinpais issues do projeto ou subprojetos são:

 1. Estudar o processo e códigos para treinamento do identificador de face, e treinar um sistema que implemente verificação de uma única pessoa famosa, tal como governador Jatene. Avaliar sistematicamente o verificador, usando conjunto de teste disjunto do de treino. Dar suporte para que o usuário "sintonize" o sistema a partir de um limiar que controle probabilidades de falso-positivo e falso-negativo.
 2. Estudar o processo e códigos para treinamento do identificador de face, e treinar um sistema que implemente identificação dentre um conjunto de 6 pessoas da própria UFPA. Avaliar sistematicamente o identificador, usando conjunto de teste disjunto do de treino. Dar suporte para que o usuário "sintonize" o sistema a partir de um limiar que controle probabilidades de falso-positivo e falso-negativo.
 3. Avaliar e reduzir o custo computacional da etapa de execução do identificador de faces no Matlab/Octave. Para isso, fazer "profiling" do código, identificar funções críticas, avaliar seu custo, otimizar o código para reduzir esforço. Daí comparar a versão inicial com o código otimizado para reportar de preferência ganho significativo
 4. Fazer uma avaliação sistemática de um identificador de faces a partir de conjuntos de imagens relativamente grandes obtidos na Web. Usar conjunto de teste disjunto do de treino. Inserir ruído de forma controlada nas imagens (pode-se usar PSNR por exemplo) ou rotacionar levemente as imagens. Estudar principais fatores afetando o desempenho
 5. Usando os algoritmos eigenfaces para identificação de face do Viola&Jones, treinar e avaliar um identificador para um outro problema (por exemplo, identificar gatos e cachorros). Pode-se usar conjunto de imagens já disponível na Internet, mas não se pode simplesmente usar um sistema já treinado. A equipe precisa aprender a treinar e gerar um identificador.

## Materiais de auxílio

###### Artigos

[RECONHECIMENTO FACIAL UTILIZANDO EIGENFACES](http://www.lcg.ufrj.br/~marroquim/courses/cos756/trabalhos/2013/abel-nascimento/abel-nascimento-report.pdf)

[Eigenface Tutorial](hhttp://www.pages.drexel.edu/~sis26/Eigenface%20Tutorial.htm)

[Face Recognition with GNU Octave/MATLAB](http://www.bytefish.de/pdf/facerec_octave.pdf)


###### Video Aulas

[Eigenfaces](https://www.youtube.com/watch?v=_lY74pXWlS8)

###### Exemplos

[Mathworks](https://www.mathworks.com/matlabcentral/fileexchange/45915-eigenfaces-algorithm)

[Bytefish](https://github.com/bytefish/facerec/tree/master/m)

###### Extras

Cada equipe da turma de projetos 2 e também o grupo do PETi deve eleger alguém que fique responsável pelo código da equipe. O responsável elegido deve dar fork neste repositório e criar uma pasta nele com um nome que identifique a equipe, nesta pasta ficaram os códigos de denvolvidos pelo grupo.

Os outros membros da equipe devem contribuir dando fork no repositório do repositório "forcado" pela pessoa que deu fork nesse repositório ou sendo adicionado como colaborador no repositório principal da equipe.

Além das pastas com os materiais de cada grupo, também existiram pastas com exemplos e materiais de apoio que poderão ser copiados para as pastas do grupos. caso algum grupo precise de um algo desenvolvido por outro grupo também poderão copiar os arquivos de uma pasta para outra.

Conforme o projeto for sendo desenvolvido as equipes devem dar pull request para este repositório para que todos possam acompanhar o que vem sendo desenvolvido.

Na parte das issues aqui no GitHub também existem alguns materiais interessantes.

