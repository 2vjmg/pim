# Guia GitHub
<h1>Baixando Git</h1>
<p>Primeiro devemos baixar e instalar o Git no computador <br>
Link para download: https://git-scm.com/downloads
</p>

<h1>Configurando o ambiente</h1>
<p>Abra o terminal Git que foi instalado junto ao Git
*Caso nao ache, va em Iniciar e pesquise por <strong>git</strong>, abra o <strong>git bash</strong>
</p>

<h2>Clonar repositorio</h2>
<p>git clone < https://github.com/2vjmg/pim.git ></p>

<h2>Fazer um branch(membro)</h2>
<p>git checkout -b < nomebranch > </p>

<h2>Enviar mudancas para o seu branch</h2>
<p><strong>Apos realizar mudancas no codigo e querer mandar para o repositorio remoto(GitHub), realizar os seguintes comandos no terminal do Git</strong></p>

<p>git add < arquivo > (<i>--all (caso deseje enviar todos os arquivos)</i>)</p>
<p>git commit -m "Escreva uma mensagem de acordo com as mudancas"</p>

<p><strong>Apos isso as mudancas ja estao no seu repositorio local, basta agora enviar para o repositorio remoto(GitHub)</strong></p>

<h2>Enviando para o repositorio remoto(GitHub)</h2>
<p>git push origin < branch ></p>
