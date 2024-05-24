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