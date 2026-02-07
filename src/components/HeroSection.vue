<template>
  <section class="max-w-7xl mx-auto px-6 py-16 md:py-24">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-20 items-center">
      <div class="flex flex-col gap-8 order-2 lg:order-1">
        <div class="inline-flex items-center gap-2 bg-blue-50 dark:bg-blue-900/20 px-4 py-2 rounded-full w-fit">
          <span class="relative flex h-3 w-3">
            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-primary opacity-75"></span>
            <span class="relative inline-flex rounded-full h-3 w-3 bg-primary"></span>
          </span>
          <span class="text-sm font-bold text-primary tracking-wide uppercase">Citas Disponibles Hoy</span>
        </div>
        <h2 class="text-5xl lg:text-7xl font-black leading-[1.05] tracking-tight text-gray-900 dark:text-white">
          Cuidado médico integral a tu alcance
        </h2>
        <p class="text-xl text-gray-600 dark:text-gray-400 leading-relaxed max-w-xl">
          Accede a los mejores especialistas, laboratorios y servicios de salud urgentes directamente desde cualquier dispositivo, con la calidad que tú y tu familia merecen.
        </p>
        <div class="flex flex-row gap-4 pt-4">
          <button class="px-10 h-14 bg-primary text-white rounded-xl font-bold text-lg shadow-xl shadow-primary/25 hover:translate-y-[-2px] transition-all">
            Agendar Cita
          </button>
          <button class="px-10 h-14 bg-white dark:bg-gray-800 border border-gray-200 dark:border-gray-700 text-gray-900 dark:text-white rounded-xl font-bold text-lg hover:bg-gray-50 dark:hover:bg-gray-700 transition-all">
            Ver Seguros
          </button>
        </div>
        <div class="flex items-center gap-6 pt-4 border-t border-gray-100 dark:border-gray-800 mt-4">
          <div class="flex -space-x-3">
            <img alt="User" class="size-10 rounded-full border-2 border-white dark:border-gray-900 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBXb-9RcjhP7apG8LWCWkUBQo9HApDVvh-NDy15hwcW1GcpVwboh4CmUID_C1UW8wI1KhEI_ts2yvrnomJiGnmximqNAOtzuRmZncjCmg0dKcmziEDlBrlNXnMv75iXxs88OiSdBln4P4sVTaBA25SQ-JyIQThycejP1TAlsUBVoqtbN8NXUtTatqW9t48H09AN6O-uupP3hddkML9lrlklqP0WNzrqs-rKnXZJrAtt_E1RV6Z0kAMhWR95F2xtSZmSy8GeKKi4NeM"/>
            <img alt="User" class="size-10 rounded-full border-2 border-white dark:border-gray-900 object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCVK9p4nYKMyl49GUaRak3NOGYl5uwcDMH3XGAYzclDv4ohrco7h32Ga3lunmhRTalo-K-YAZjxI8AKvDC24zXEhWO3Z_AyTB1y26Omc0bdl1cXKBZ_n8Ju41NIYxPBTCdZHoCn-1Ci2CYYVY29cxdW0Fc9xeKijYzdpT4aJW7FQvel6lXAAsgLJ7KpWySmEdRi7tp5DD7aZH-xvkz139TSMNkdmrSG_WjeGE9GRElg9tWw0mYCPAX3J0qik83ZKsGNVucHCJ2KiIw"/>
            <div class="size-10 rounded-full border-2 border-white dark:border-gray-900 bg-gray-100 flex items-center justify-center text-xs font-bold">+2k</div>
          </div>
          <p class="text-sm text-gray-500 font-medium">Más de <span class="text-gray-900 dark:text-white font-bold">2,000 pacientes</span> confían en nosotros mensualmente.</p>
        </div>
      </div>
      <div class="relative order-1 lg:order-2">
        <div class="relative z-10 w-full aspect-[4/5] md:aspect-square rounded-[2rem] overflow-hidden shadow-2xl">
          <img alt="Doctor" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB9aEKAH4rovsQG09JOqZ5kO5XwOe673dNfjdmT_RurECeqOWUJPWrbMyPm1myhv9G4IG1_i2NXZWbsI_1wiCvVyGAMuHQ3TNX9HsOxdTEZ8zClt6LLPuZWHxyelFtiJ4V4zaYlCvWE039A-15btb-demlz8T6-RQKR9JJ1A57Gm9xRZMaTPzXXM3Elc0wMEIQYcAcQlpwtJMS74nCCYssx3HAAB8P3oWyKoMnJSH0B-oOcmxE5B44xycXT5JjmDFfyuYzLQWRfncw"/>
          <div class="absolute inset-0 bg-gradient-to-t from-primary/30 to-transparent"></div>
        </div>
        <div class="absolute -bottom-6 -left-6 md:-left-12 z-20 bg-white dark:bg-gray-800 p-6 rounded-2xl shadow-2xl border border-gray-100 dark:border-gray-700 max-w-[240px]">
          <div class="flex items-center gap-3 mb-2">
            <div class="size-10 rounded-full bg-green-100 flex items-center justify-center text-green-600">
              <span class="material-symbols-outlined">verified</span>
            </div>
            <span class="text-sm font-bold">Médicos Verificados</span>
          </div>
          <p class="text-xs text-gray-500 leading-normal">Todos nuestros especialistas cuentan con certificaciones internacionales actualizadas.</p>
        </div>
        <div class="absolute -top-10 -right-10 size-40 bg-blue-100/50 dark:bg-blue-900/10 rounded-full blur-3xl -z-10"></div>
        <div class="absolute -bottom-10 -left-10 size-60 bg-blue-50 dark:bg-blue-900/10 rounded-full blur-3xl -z-10"></div>
      </div>
    </div>
  </section>
</template>
