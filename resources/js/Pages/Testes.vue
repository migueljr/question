<template>
    <div class="flex justify-center items-center rounded mt-3">
        <img class="w-44" src="https://files.adventistas.org/institucional/pt/sites/8/2013/12/31153537/guia-biblia-facil.jpg" alt="">
    </div>
    <div class="container mt-3">
        <p>Olá, sejá bem vindo a nossa plataforma da classe Bíblica Daniel IASD Bairro Novo. Segue abaixo os temas do estudo.</p>

        <div class="mt-3">
            <div @click="showQuestions=true" class="w-full border border-gray-600 bg-gray-100 rounded px-2 py-2 hover:bg-gray-200 mb-2">
                <p>1 - O Livro de Daniel - <span class="font-bold text-green-600">Liberado</span> </p>
                <span v-if="showQuestions" @click="showQuestions=false" class="text-xs"> - Fechar</span>
                <div v-if="showQuestions">
                    <hr>
                    <div>
                        <p class="text-xs mt-2 font-bold">Questão 1 - Quem escreveu o livro de Daniel?</p>
                        <div class="mt-2">
                            <input type="radio"> Daniel <br>
                            <input type="radio"> Ezequiel <br>
                            <input type="radio"> Ananias <br>
                            <input type="radio"> Mizael <br>
                            <input type="radio"> Azarias <br>
                        </div>
                    </div>
                    <div>
                        <p class="text-xs mt-2 font-bold">Questão 2 - Quem escreveu o livro de Daniel?</p>
                        <div class="mt-2">
                            <input type="radio"> Daniel <br>
                            <input type="radio"> Ezequiel <br>
                            <input type="radio"> Ananias <br>
                            <input type="radio"> Mizael <br>
                            <input type="radio"> Azarias <br>
                        </div>
                    </div>
                </div>
            </div>
            <div class="w-full border border-gray-600 bg-gray-100 rounded px-2 py-2 mb-2 opacity-50">
                <p>2 - O Livro de Daniel - <span class="font-bold">Em breve</span></p>
            </div>
        </div>
    </div>
</template>
<script>


export default {
    data(){
        return{
            showQuestions:false
        }
    }
}
</script>
