# O que é o LSRV?

A Virtual Reality Substation Laboratory (VRSL) é um software desenvolvido utilizando da Unity Engine pelo Grupo de Redes Elétricas Inteligentes (GREI) para melhorar o processo de ensino-aprendizagem em cursos de Engenharia Elétrica no que tange ao conteúdo de subestações.

## Seção 1 - Qual é a principal função do Virtual Reality Substation Laboratory (VRSL)?

O software recria, de forma fiel, a subestação de distribuição de energia elétrica que alimenta o Campus Professor Prisco Bezerra da Universidade Federal do Ceará (UFC).

O software possui dois ambientes para exploração discente, sendo eles o Pátio da Subestação e a Casa de Comando. No pátio é possível visualizar os equipamentos de uma subestação de distribuição, tais como Transformador de Corrente (TC), Transformador de Potencial (TP), transformadores de potência, chave seccionadora, religadores e estruturas de concreto, conforme ilustrado nas Figuras abaixo que comparam o real com o virtual.


Subestação Real            |  Subestação RV
:-------------------------:|:-------------------------:
![image](https://github.com/grei-ufc/vrslab/assets/172390778/861434b1-303c-47e3-8c01-34edb6328b4e)  |  ![image](https://github.com/grei-ufc/vrslab/assets/172390778/6a34490a-4d1c-4fe5-82e9-4da2bcaed8b6)

Além disso, no ambiente do pátio também há um drone no qual os alunos podem sobrevoar a subestação com a finalidade de visualizar os equipamentos por um ângulo melhor, conforme mostrado abaixo.

<div align="center">

<img width="850" alt="foto-3" src="https://github.com/grei-ufc/vrslab/assets/172390778/7c95dd27-2c3e-44e1-a5fc-1578cfb9b5b6">
</div>

O ambiente da Casa de Comando possui os quadros de proteção e automação com seus respectivos equipamentos, como relés, computadores industriais e Switches. Neles, é possível interação para criar simulações completas de eventos de falta que ocorreram na subestação real, com supervisório, oscilógrafias e diagrama de atuação das proteções, conforme exibido nas Figuras abaixo.

Subestação Real            |  Subestação RV
:-------------------------:|:-------------------------:
![image](https://github.com/grei-ufc/vrslab/assets/172390778/e9279ba0-270a-4e9e-b0b4-4e9844b26745)  |  ![image](https://github.com/grei-ufc/vrslab/assets/172390778/0bd3cbfa-0357-4a83-850d-4f7473ff3a0d)

<div align="center">

<img width="850" alt="foto-7" src="https://github.com/grei-ufc/vrslab/assets/172390778/030fa06b-a32d-4e3d-b9f2-346de63eff38">
</div>

## Seção 2 - Como usar o VRSL?
Para apenas utilizar o software, na Seção 3 está disponibilizado um link com um arquivo .zip para o download dos arquivos necessários para executar o VRSL em qualquer computador. Após baixar os arquivos, é indicado a leitura do arquivo read_me.txt que contém as instruções para a instalação apropriada. Para executar o software, os requisitos mínimos são:

+ Memória RAM 8 Gb DDR4;
+ Placa de vídeo de 2GB;
+ Processador i5 8ª Geração, cache de 12 MB, até 4.40 GHz;
+ Utilização do SSD mínimo 256 GB.

Importante salientar que os requisitos mínimos não oferecem a melhor solução para o ensino, haja vista que o software possui muitos equipamentos pesados. Portanto, os requisitos recomendados para a utilização fluida do software são:

+ Memória RAM 16 Gb DDR4;
+ Placa de vídeo de 4GB;
+ AMD Ryzen 5000 Series 7 ou 13ª geração Intel® Core™ i5-13450HX (10-core, cache de 20MB, até 4.6GHz);
+ Utilização do SSD mínimo 256 GB.

Após a instalação apropriada do software, o usuário será levado para o ambiente da subestação e as instruções para utilização do software estão descrito abaixo:


<div align="center">

<img width="850" alt="teclado" src="https://github.com/grei-ufc/vrslab/assets/172390778/0ce614c7-40c4-4b4f-be8d-cd50d76a953d">
</div>

+ Tecla W – Movimentação para frente;
+ Tecla A – Movimentação para direita;
+ Tecla S – Movimentação para trás
+ Tecla D – Movimentação para esquerda
+ Tecla Shift – Corre rápido
+ Tecla Ctrl esquerdo - Agachar
+ Tecla Ctrl direito – Ponta dos pés
+ Tecla I – Movimentação pra frente no drone;
+ Tecla K – Movimentação para trás no drone;
+ Tecla J – Movimentação para direita no drone;
+ Tecla L – Movimentação para esquerda no drone;
+ Tecla O – Sair do drone
+ Tecla T – Parar o drone no ar;
+ Tecla E – Interagir com componentes, como portas, drones etc;
+ Tecla M – Habilitar/Desabilitar minimapa;
+ Tecla Barra de espaço – Pular;
+ Tecla Esc – Opções do jogo.

Dentro do VRSL o usuário tem liberdade para se movimentar e visualizar qualquer equipamento em qualquer ângulo. É recomendável que o usuário acesso o computador, na casa de comando, para utilizar todas as funcionalidades do software, como visualizar e interagir com o diagrama unifilar da subestação e visualizar simulações.

## Seção 3 – Indicação de aula utilizando o VRSL?

Para guiar o(a) professor(a) que tenha a intenção de utilizar o VRSL em sala de aula, foi criado um plano de aula para servir de modelo e de exemplo para replicação. A disciplina em questão chama-se Geração, Transmissão e Distribuição e tem o objetivo de introduzir, ao discente, os conteúdos da área de Sistemas Elétricos de Potência. Aconselha-se utilizar do plano de aula sugerido, que se encontra no drive com link abaixo, após as aulas teóricas de subestação com a finalidade de mostrar um ambiente em 3D do conteúdo abordado em sala de aula.

[Plano de aula proposto](https://github.com/user-attachments/files/15992491/Plano.de.aula.GTD_VRSL_V1.pdf)


## Seção 4 – Prémios e publicações envolvendo o VRSL.

O presente projeto é fruto da parceria com CNPq, oriunda da chamada universal de 2023, intitulada “Plataforma Multidomínio em Realidade Virtual aplicada ao processo de Ensino-Aprendizagem.” Além disso, o presente projeto adquiriu, no CINASE 2023 – Edição Fortaleza, o prêmio de **Melhor Projeto P&D** e o prêmio **O Setor Elétrico (OSE) de Melhor Projeto Geral**. Além disso, seu desenvolvimento e aplicação gerou os seguintes trabalhos:

[Trabalho de Conclusão de Curso](https://repositorio.ufc.br/handle/riufc/67639)

[Artigo no XIX ERIAC na seção C2 D2](https://www.xixeriac.com.br/artigos-apresentacoes)

## Seção 5 – Pesquisadores envolvidos no projeto

[Daniel Rebouças Jaguaribe](http://lattes.cnpq.br/8807139438765241)

[Raimundo Furtado Sampaio](http://lattes.cnpq.br/9936530790182581)

[Giovanni Cordeiro Barroso](http://lattes.cnpq.br/1218783106447217)

[Antônio Melo Júnior](http://lattes.cnpq.br/2610619567290943)

[Ruth Pastôra Saraiva Leão](http://lattes.cnpq.br/8551048513174462)

[Milena Teixeira](http://lattes.cnpq.br/3425826858113947)

Gustavo Alves

[Rômulo Moura](http://lattes.cnpq.br/2440007243254830)

[Richarles Cândido](http://lattes.cnpq.br/6055212132306536)

[Gabriel Pinheiro](http://lattes.cnpq.br/2361451480162580)


