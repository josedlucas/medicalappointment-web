<template>
  <section class="bg-white dark:bg-gray-900/30 py-24">
    <div class="max-w-7xl mx-auto px-6">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-4">
        <div class="max-w-2xl">
          <h2 class="text-4xl font-black tracking-tight text-gray-900 dark:text-white mb-4">Servicios Médicos Especializados</h2>
          <p class="text-lg text-gray-500">Ofrecemos un ecosistema de salud completo diseñado para tu comodidad y bienestar.</p>
        </div>
        <button class="text-primary font-bold flex items-center gap-2 group">
          Ver todos los servicios 
          <span class="material-symbols-outlined group-hover:translate-x-1 transition-transform">arrow_forward</span>
        </button>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="group p-8 rounded-3xl border border-gray-100 dark:border-gray-800 bg-[#f8f9fc] dark:bg-gray-800/50 hover:bg-white dark:hover:bg-gray-800 hover:shadow-xl hover:border-primary/20 transition-all">
          <div class="size-14 rounded-2xl bg-blue-100 dark:bg-blue-900/40 text-primary flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
            <span class="material-symbols-outlined text-3xl">video_chat</span>
          </div>
          <h3 class="text-xl font-bold mb-3">Telemedicina</h3>
          <p class="text-gray-500 dark:text-gray-400 text-sm leading-relaxed mb-6">Consulta con especialistas desde cualquier lugar a través de nuestra plataforma segura.</p>
          <a class="text-primary font-bold text-sm inline-flex items-center gap-1" href="#">Saber más <span class="material-symbols-outlined text-sm">chevron_right</span></a>
        </div>
        <div class="group p-8 rounded-3xl border border-gray-100 dark:border-gray-800 bg-[#f8f9fc] dark:bg-gray-800/50 hover:bg-white dark:hover:bg-gray-800 hover:shadow-xl hover:border-primary/20 transition-all">
          <div class="size-14 rounded-2xl bg-green-100 dark:bg-green-900/40 text-green-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
            <span class="material-symbols-outlined text-3xl">stethoscope</span>
          </div>
          <h3 class="text-xl font-bold mb-3">Especialidades</h3>
          <p class="text-gray-500 dark:text-gray-400 text-sm leading-relaxed mb-6">Más de 30 especialidades médicas con los equipos tecnológicos más avanzados.</p>
          <a class="text-primary font-bold text-sm inline-flex items-center gap-1" href="#">Saber más <span class="material-symbols-outlined text-sm">chevron_right</span></a>
        </div>
        <div class="group p-8 rounded-3xl border border-gray-100 dark:border-gray-800 bg-[#f8f9fc] dark:bg-gray-800/50 hover:bg-white dark:hover:bg-gray-800 hover:shadow-xl hover:border-primary/20 transition-all">
          <div class="size-14 rounded-2xl bg-purple-100 dark:bg-purple-900/40 text-purple-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
            <span class="material-symbols-outlined text-3xl">biotech</span>
          </div>
          <h3 class="text-xl font-bold mb-3">Laboratorio</h3>
          <p class="text-gray-500 dark:text-gray-400 text-sm leading-relaxed mb-6">Resultados rápidos y precisos con entrega digital directamente en tu perfil.</p>
          <a class="text-primary font-bold text-sm inline-flex items-center gap-1" href="#">Saber más <span class="material-symbols-outlined text-sm">chevron_right</span></a>
        </div>
        <div class="group p-8 rounded-3xl border border-gray-100 dark:border-gray-800 bg-red-50/30 dark:bg-red-900/10 hover:bg-white dark:hover:bg-gray-800 hover:shadow-xl hover:border-red-200 transition-all">
          <div class="size-14 rounded-2xl bg-red-100 dark:bg-red-900/40 text-red-600 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
            <span class="material-symbols-outlined text-3xl">e911_emergency</span>
          </div>
          <h3 class="text-xl font-bold mb-3">Urgencias</h3>
          <p class="text-gray-500 dark:text-gray-400 text-sm leading-relaxed mb-6">Atención inmediata las 24 horas del día, los 7 días de la semana, sin cita previa.</p>
          <a class="text-red-600 font-bold text-sm inline-flex items-center gap-1" href="#">Ver sedes <span class="material-symbols-outlined text-sm">chevron_right</span></a>
        </div>
      </div>
    </div>
  </section>
</template>
