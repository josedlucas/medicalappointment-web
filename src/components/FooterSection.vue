<template>
   <footer class="bg-white dark:bg-gray-900 border-t border-gray-200 dark:border-gray-800 py-12 px-4">
            <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-12">
                <div class="col-span-1 md:col-span-1">
                    <div class="flex items-center gap-2 mb-6">
                        <div class="text-white rounded-xl">
                            <img src="/public/logo.png" alt="VitaRecord" class="h-16 w-auto" />
                        </div>
                        <span class="text-2xl font-black text-primary">VitaRecord</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-400 mb-6">
                        El sistema médico integral que pone al paciente en el centro de todo.
                    </p>
                    <div class="flex gap-4">
                        <a class="text-gray-400 hover:text-primary transition-colors" href="#"
                            ><span class="material-symbols-outlined">public</span></a
                        >
                        <a class="text-gray-400 hover:text-primary transition-colors" href="#"
                            ><span class="material-symbols-outlined">alternate_email</span></a
                        >
                        <a class="text-gray-400 hover:text-primary transition-colors" href="#"
                            ><span class="material-symbols-outlined">share</span></a
                        >
                    </div>
                </div>
                <div>
                    <h4 class="font-bold mb-6">Empresa</h4>
                    <ul class="space-y-4 text-gray-600 dark:text-gray-400">
                        <li><a class="hover:text-primary" href="#">Sobre Nosotros</a></li>
                        <li><a class="hover:text-primary" href="#">Carreras</a></li>
                        <li><a class="hover:text-primary" href="#">Prensa</a></li>
                        <li><a class="hover:text-primary" href="#">Blog</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-6">Legal</h4>
                    <ul class="space-y-4 text-gray-600 dark:text-gray-400">
                        <li><a class="hover:text-primary" href="#">Términos de Uso</a></li>
                        <li><a class="hover:text-primary" href="#">Política de Privacidad</a></li>
                        <li><a class="hover:text-primary" href="#">Cookies</a></li>
                        <li><a class="hover:text-primary" href="#">Seguridad</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-6">Newsletter</h4>
                    <p class="text-sm text-gray-600 dark:text-gray-400 mb-4">
                        Suscríbete para recibir noticias sobre salud y actualizaciones.
                    </p>
                    <div class="flex gap-2">
                        <input
                            class="bg-gray-100 dark:bg-gray-800 border-none rounded-lg px-4 py-2 w-full focus:ring-2 focus:ring-primary"
                            placeholder="Email"
                            type="email"
                        />
                        <button class="bg-primary text-white p-2 rounded-lg">
                            <span class="material-symbols-outlined">send</span>
                        </button>
                    </div>
                </div>
            </div>
            <div
                class="max-w-7xl mx-auto mt-12 pt-8 border-t border-gray-200 dark:border-gray-800 text-center text-sm text-gray-500"
            >
                © 2024 Sanas Healthcare System. Todos los derechos reservados.
            </div>
        </footer>
</template>
