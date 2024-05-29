<script setup></script>

<template>
    <header class="p-2 w-auto flex justify-between items-center">
        <!--Logo da Codexa-->
        <div class="w-auto">
            <h1 class="w-auto">
                <img class="w-60" src="../assets/codexa.svg" alt="Logo da Codexa">
            </h1>
        </div>
        

        <!--Menu-->
        <nav class="px-2 py-4 flex items-center gap-8 " >
            <a href="#">Página Inicial</a>
            <a href="/servicos">Serviços</a>
            <a href="#contato">Contato</a>
            <a href="/suporte">Suporte</a>
            <button class="w-auto p-2 bg-red-800 rounded hover:bg-red-600 transition botao"><a class="text-white" href="/agendamento">Faça seu agendamento</a></button>
        </nav>
    </header>
</template>



<style scoped>
.botao {
    transition: 0.5s;
}
</style>