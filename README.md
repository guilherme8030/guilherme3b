.ativo{
    background-color: var(--botao-ativo);
    border-bottom: 4px solid var(--verde);
}
<button class="botao ativo">Cursos na Alura</button>
<button class="botao">Criar projetos em Javascript</button>
<button class="botao">Criar um portfolio</button>
<button class="botao">Atualizar meu currículo</button>
<script src="main.js"></script>
const botoes = document.querySelectorAll(".botao");
console.log(botoes)
for(let i=0; i <  botoes.length; i++){
    console.log(i);
}
botoes[i].onclick = function(){
    
    botoes[i].classList.add("ativo");
}
for(let j=0;j<botoes.length;j++){
            botoes[j].classList.remove("ativo");
 }
const botoes = document.querySelectorAll(".botao");

for(let i=0;i <botoes.length;i++){
    botoes[i].onclick = function(){

        for(let j=0;j<botoes.length;j++){
            botoes[j].classList.remove("ativo");
        }

        botoes[i].classList.add("ativo");
    
# guilherme3b