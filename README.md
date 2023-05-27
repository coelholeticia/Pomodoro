# Pomodoro ⭐

Um site para técnica de estudo pomodoro.
* O que pomodoro?
A Técnica Pomodoro é um método de gerenciamento de tempo desenvolvido por Francesco Cirillo no final dos anos 1980. A técnica consiste na utilização de um cronômetro para dividir o trabalho em períodos de 25 minutos, separados por breves intervalos.
* O intuito do site ?
O intuito além de você ter seu próprio site para gerência seu tempo, permite você praticar e se aprofundar bastante em JAVASRIPT. 
* Tecnologias usadas?
HTML, CSS, E JAVASCRIPT - nível de conhecimento intermediário 

* Sobre o projeto, explicação do código implementado:

 > O código começa selecionando elementos HTML relevantes usando document.querySelector e atribuindo-os a variáveis para uso posterior. Esses elementos incluem o progresso circular, os botões de tipo de Pomodoro e intervalo curto, e um elemento de áudio para reproduzir o alarme.

> Em seguida, o código define constantes e variáveis iniciais. As constantes pomodoroTimerInSeconds e shortBreakTimerInSeconds representam a duração em segundos do Pomodoro e do intervalo curto, respectivamente. As variáveis progressInterval, pomodoroType, timerValue e multiplierFactor são usadas para controlar o funcionamento do contador.

> O código inclui duas funções auxiliares: formatNumberInStringMinute e setInfoCircularProgressBar. A primeira converte um número em segundos para uma string formatada no formato "mm:ss". A segunda função atualiza a exibição do progresso no elemento de progresso circular e verifica se o contador atingiu zero para reproduzir o áudio do alarme.

> O código inclui três funções principais: startTimer, stopTimer e resetTimer. A função startTimer inicia o cronômetro, decrementando o valor do timerValue a cada segundo e chamando setInfoCircularProgressBar para atualizar a exibição do progresso. A função stopTimer para o cronômetro, limpando o intervalo definido anteriormente. A função resetTimer reinicia o contador, definindo o valor do timerValue com base no tipo de contador ativo, recalculando o multiplierFactor e chamando setInfoCircularProgressBar.

> Por fim, a função setPomodoroType é responsável por definir o tipo de contador Pomodoro (Pomodoro ou intervalo curto). Ela atualiza a aparência dos botões correspondentes no HTML, remove a classe "active" do botão não selecionado e adiciona a classe "active" ao botão selecionado. Em seguida, chama resetTimer para reiniciar o contador com base no novo tipo selecionado.

> No geral, o código implementa a lógica para controlar o contador Pomodoro, atualizando a exibição do progresso, reproduzindo o alarme quando o contador atinge zero e permitindo iniciar, parar e reiniciar o cronômetro.

* Esse projeto é um projeto Open Source quer contribuir?
 1. Faça um fork do projeto 
 2. Clone o projeto na sua maquina
 3.  Crie uma nova branch
 4.  Faça/modifique o código
 5.  Realizar Stage - Commit do seu trabalho
 6.  Open a pull request
 
 <img src="https://media.tenor.com/P5DB2iGAecsAAAAj/peach-cat.gif" /> 
