<template>
  <footer class="bg-white dark:bg-background-dark border-t border-gray-100 dark:border-gray-800 pt-24 pb-12">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-12 mb-20">
        <div class="lg:col-span-2">
          <div class="flex items-center gap-3 mb-6">
            <div class="text-white rounded-xl">
              <img src="/public/logo.png" alt="VitaRecord" class="h-16 w-auto" />
            </div>
            <span class="text-2xl font-black text-primary">VitaRecord</span>
          </div>
          <p class="text-gray-500 dark:text-gray-400 text-lg leading-relaxed max-w-sm mb-8">
            Redefiniendo el cuidado médico a través de la tecnología y la empatía humana. Tu salud es nuestra prioridad número uno.
          </p>
          <div class="flex gap-4">
            <a class="size-11 rounded-full bg-gray-50 dark:bg-gray-800 flex items-center justify-center text-gray-400 hover:bg-primary hover:text-white transition-all" href="#">
              <span class="material-symbols-outlined text-xl">share</span>
            </a>
            <a class="size-11 rounded-full bg-gray-50 dark:bg-gray-800 flex items-center justify-center text-gray-400 hover:bg-primary hover:text-white transition-all" href="#">
              <span class="material-symbols-outlined text-xl">language</span>
            </a>
            <a class="size-11 rounded-full bg-gray-50 dark:bg-gray-800 flex items-center justify-center text-gray-400 hover:bg-primary hover:text-white transition-all" href="#">
              <span class="material-symbols-outlined text-xl">mail</span>
            </a>
          </div>
        </div>
        <div>
          <h4 class="font-black text-sm uppercase tracking-widest text-gray-900 dark:text-white mb-6">Servicios</h4>
          <ul class="flex flex-col gap-4">
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Telemedicina</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Citas Online</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Chequeos Médicos</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Seguros de Salud</a></li>
          </ul>
        </div>
        <div>
          <h4 class="font-black text-sm uppercase tracking-widest text-gray-900 dark:text-white mb-6">Compañía</h4>
          <ul class="flex flex-col gap-4">
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Sobre Nosotros</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Nuestros Médicos</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Sedes</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Carreras</a></li>
          </ul>
        </div>
        <div>
          <h4 class="font-black text-sm uppercase tracking-widest text-gray-900 dark:text-white mb-6">Soporte</h4>
          <ul class="flex flex-col gap-4">
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Centro de Ayuda</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Contacto</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Privacidad</a></li>
            <li><a class="text-gray-500 dark:text-gray-400 hover:text-primary transition-colors" href="#">Términos</a></li>
          </ul>
        </div>
      </div>
      <div class="pt-12 border-t border-gray-100 dark:border-gray-800 flex flex-col md:flex-row justify-between items-center gap-6">
        <p class="text-sm text-gray-400">
          © 2024 MediPlus Inc. Todos los derechos reservados. Diseñado para excelencia médica.
        </p>
        <div class="flex items-center gap-8">
          <span class="flex items-center gap-2 text-xs font-bold text-gray-400 uppercase tracking-widest">
            <span class="material-symbols-outlined text-sm">security</span> 100% Seguro
          </span>
          <span class="flex items-center gap-2 text-xs font-bold text-gray-400 uppercase tracking-widest">
            <span class="material-symbols-outlined text-sm">verified_user</span> Certificado GDPR
          </span>
        </div>
      </div>
    </div>
  </footer>
</template>
