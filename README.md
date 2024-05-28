# github-actions
 <br> <br>

#### diferentes shells
// utilizar um runner com um shell diferente

| S.O. suportado | valor | 
|----------------|-------|
| Todos | bash |
| Todos | pwsh |
| Todos | python |
| Linux/macOS | sh |
| windows | powershell |


<br> <br>

#### marketplace de actions
utilizadas
https://github.com/marketplace/actions/upload-a-build-artifact
https://github.com/marketplace/actions/download-a-build-artifact 

<br> <br>
introdução ao github actions

/older
github-actions-demo.yml // arquivo inicial demonstração github
![image](https://github.com/a-lloma/github-actions/assets/35180706/65c1bf1c-8eb9-4997-bfd6-f7729092789e)

primeiro.yml // criando a primeira action
![image](https://github.com/a-lloma/github-actions/assets/35180706/6fa580f6-3998-4491-8f4c-350fa7a6794f)

shell.yml // testando diferentes terminais 
![image](https://github.com/a-lloma/github-actions/assets/35180706/113bf68f-6499-46ec-b8fe-7b996a7a8378)


./
upload-download.yml // final: conexão entre jobs e compartilhamento de informações com o uso de actions do marketplace4
![image](https://github.com/a-lloma/github-actions/assets/35180706/f7e2a56f-cd6e-4507-a192-afd4cf9ff34e)



<br>
<br>

#### events
link referência: https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows 
<br>
exemplo de PR https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#pull_request

<br>
ON - schedule
evento agendado permite acionar um workflow em um horário agendado


*****
12345
1-minutos (0-59)
2- horas (0-23)
3 dias do mes (1-31)
mês (1-12 ou JAN-DEC)
dias da semana (0-6 ou SUN-SAT)

<pre><code class="hljs language-text">┌───────────── minute (0 - 59)
│ ┌───────────── hour (0 - 23)
│ │ ┌───────────── day of the month (1 - 31)
│ │ │ ┌───────────── month (1 - 12 or JAN-DEC)
│ │ │ │ ┌───────────── day of the week (0 - 6 or SUN-SAT)
│ │ │ │ │
│ │ │ │ │
│ │ │ │ │
* * * * *
</code></pre>

https://crontab.guru/every-5-minutes
<br>
*/5 * * * *