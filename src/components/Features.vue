<template>
     <section class="abyga-body  py-20 mt-20 pb-60 lg:mt-60" id="features">
        <!-- Heading-->
        <div class="sm:w-3/4  mx-auto px-2">
            <h1 class="text-4xl text-center text-bookmark-white">Características</h1>
            <p class="text-center text-bookmark-grey mt-4">La aplicación asegura la privacidad de los datos del usuario con un sistema de inicio de sesión seguro. Además, el calendario financiero y las herramientas de seguimiento de gastos integradas ayudan a mantener controlado los gastos</p>
        </div>
        <!-- Feature #1-->
        <div class="relative mt-20 lg:mt-24">
            <div class="container flex flex-col lg:flex-row items-center justify-center gap-x-24">
                <!-- Feature #1-->
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img src="../assets/images/login.png" alt="" class="w-5/6 h-5/6 sm:w-3/4 sm:3/4 md:w-full md:h-full rounded-md">
                </div>
                <!-- Content-->
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-white">Inicio de sesión seguro</h1>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">La aplicación cuenta con un sistema de inicio de sesión seguro que protege los datos personales y financieros del usuario. Para acceder a la información, el usuario debe proporcionar credenciales de inicio de sesión, como una contraseña o un código de acceso, lo que garantiza la privacidad de la información.</p>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">Adicionalmente nuestra aplicación se adapta a la edad del usuario para brindar una experiencia más amigable y sencilla.</p>
                    <button type="button" class="btn abyga-background text-white hover:bg-bookmark-white hover:text-black">Mas información</button>
                </div>
            </div>
            <!-- Rounded rectangle -->
            <div class="
                    hidden 
                    lg:block 
                    overflow-hidden 
                    abyga-background
                    rounded-r-full 
                    absolute 
                    h-80 
                    w-2/4 
                    -bottom-5
                    -left-28
                ">
            </div>
        </div>

        <!-- Feature #2-->
        <div class="relative mt-20 lg:mt-52">
            <div class="container flex flex-col lg:flex-row-reverse items-center justify-center gap-x-24">
                <!-- Feature #1-->
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img src="../assets/images/finanzas.png" alt="" class="w-5/6 h-5/6 sm:w-3/4 sm:3/4 md:w-full md:h-full rounded-md">
                </div>
                <!-- Content-->
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-white">Calendario de gastos</h1>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">La aplicación cuenta con un calendario financiero que permite al usuario realizar un seguimiento de las fechas de vencimiento de las facturas y los pagos. El calendario también puede mostrar eventos financieros importantes, como el inicio de un nuevo período de facturación</p>
                    <button type="button" class="btn abyga-background text-white hover:bg-bookmark-white hover:text-black">Mas información</button>
                </div>
            </div>
            <!-- Rounded rectangle -->
            <div class="
                    hidden 
                    lg:block 
                    overflow-hidden 
                    abyga-background
                    rounded-l-full 
                    absolute 
                    h-80 
                    w-2/4 
                    -bottom-24 
                    -right-0
                ">
            </div>
        </div>

           <!-- Feature #3-->
        <div class="relative mt-20 lg:mt-52">
            <div class="container flex flex-col lg:flex-row items-center justify-center gap-x-24">
                <!-- Feature #1-->
                <div class="flex flex-1 justify-center z-10 mb-10 lg:mb-0">
                    <img src="../assets/images/cursos.png" alt="" class="w-5/6 h-5/6 sm:w-3/4 sm:3/4 md:w-full md:h-full rounded-md">
                </div>
                <!-- Content-->
                <div class="flex flex-1 flex-col items-center lg:items-start">
                    <h1 class="text-3xl text-bookmark-white">Cursos de finanzas</h1>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">La aplicación ofrece cursos online de finanzas diseñados para mejorar el conocimiento financiero del usuario y su capacidad para administrar su dinero de manera efectiva. </p>
                    <p class="text-bookmark-grey my-4 text-center lg:text-left sm:w-3/4 lg:w-full">Estos cursos están diseñados para ser accesibles y útiles para cualquier nivel de experiencia financiera, y se pueden completar a través de la aplicación en cualquier momento y lugar que sea conveniente para el usuario..</p>
                    <button type="button" class="btn abyga-background text-white hover:bg-bookmark-white hover:text-black">Mas información</button>
                </div>
            </div>
            <!-- Rounded rectangle -->
            <div class="
                    hidden 
                    lg:block 
                    overflow-hidden 
                    abyga-background
                    rounded-r-full 
                    absolute 
                    h-80 
                    w-2/4 
                    -bottom-24 
                    -left-36
                ">
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.abyga-background {
    background-color: #3e823b;
}

.abyga-body {
    background-color: #2a2a29;
}
</style>
