# **GTA SA Dubbing**
 Dubbing GTA San Andreas with pedestrian voicelines from other games
 
 
 
 
 
 * [Ferramentas de Trabalho](https://drive.google.com/file/d/1WT_4IkQdQznxmS3nxMEQZ7IoTtWnw-DC/view?usp=sharing)
 * [Vozes 1](https://drive.google.com/file/d/1-0etIGLhm7OEVZB4wCXdiTqNJMipqUYs)
 * [Vozes 2](http://drive.google.com/file/d/1ut3zmpCanYMjA3I-qRBSkQptywAaP_xP)
 * [Lista de Diálogos do GTA SA](https://gta.fandom.com/wiki/Dialogues_in_GTA_San_Andreas#Police)



# **Tarefas**

- [ ] Organizar os áudios em pastas

- [ ] Implementar os áudios correspondentes no jogo

- [ ] Eliminar sons que não houve possibilidade de encontrar correspondente


# **Quem pode contribuir?**

Qualquer um.




# **Tarefa 1** — Como organizar as pastas?

A organização deve ser feita de acordo com o mod Testar Sons incluido nas ferramentas, criando pastas para cada contexto e dentro delas separar as vozes dos mesmos dubladores.




# **Tarefa 2** — Como implementar os áudios correspondentes no jogo?

Após a organização correta, abra o _Referência SAAT.txt_. Você verá uma lista dos arquivos de áudio de jogo indicando o que contém em cada um. Com o programa **SAAT/SAAT FrontEnd** (Cabe a você escolher qual usar, tanto faz) você irá trabalhar com esses arquivos.

### Exemplo com o SAAT FrontEnd

Vamos trocar os áudios do helicóptero da polícia, apenas de exemplo.

1. Ao abrir o programa você terá que indicar a pasta de trabalho (Onde serão extraídos os áudios originais do jogo) e a pasta do GTA San Andreas;

2. Indicando e entrando na pasta audio, você terá que indicar qual arquivo extrair. A lista de referência é uma boa base para saber o que há dentro de cada um;

3. Neste pequeno exemplo iremos editar o helicoptero da polícia, que está no "SPC_FA";

4. Expanda o SPC_FA para assim extraí-lo e busque o Bank_011 que é onde estão os áudios da Guarda Costeira e do Suporte Aéreo do Helicoptero da Polícia;

5. Você terá que escutar os áudios para saber discernir quais são os áudios do Suporte Aéreo já que são semelhantes com os da Guarda Costeira, [clique aqui]
(https://gta.fandom.com/wiki/Dialogues_in_GTA_San_Andreas#Police) para ser redirecionado a uma lista de diálogos do GTA San Andreas;

6. Imaginando que você já tenha todos arquivos de áudios organizados, encontre uma frase dublada que esteja no mesmo/semelhante contexto da frase original do jogo e substitua através do SAAT;

7. Vá até o local onde você definiu para o SAAT extrair os áudios originais do jogo, busque nele os arquivos que você substituiu no SAAT e escute-os para ter certeza que foram modificados corretamente;

8. Tudo ok? Então crie uma pasta no modloader, dentro desta pasta crie uma outra pasta chamada "SPC_FA" e jogue os arquivos modificados lá dentro;

9. Teste in-game, a maioria dos áudios poderão ser testados com o mod "Testar Sons" incluso nas ferramentas, mas neste caso como são falas do Suporte Aéreo do Helicóptero da Polícia você terá que estar próximo de um para realizar o teste. Simplesmente certifique-se que você está apto a ter níveis de procurado no seu jogo (Nenhum código/mod que bloqueie ativo) e digite o cheat "BRINGITON", [teleporte-se](https://www.mixmods.com.br/2019/06/super-fast-teleporter.html) para um local alto isolado de outros sons, e de fácil acesso pelo ar para que o Suporte Aéreo consiga alcançar (Recomendo o topo do Maze Bank).

10. Parabéns, se estiver tudo ok envie para nós através de uma PR e você entrará na lista de créditos.

