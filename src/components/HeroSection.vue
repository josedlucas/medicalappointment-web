<template>
  <main class="relative overflow-hidden">
            <div class="px-4 py-12 md:py-24 max-w-7xl mx-auto @container">
                <div class="flex flex-col gap-8 md:flex-row md:items-center">
                    <div class="flex flex-col gap-6 md:w-1/2">
                        <div
                            class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary/10 text-primary text-xs font-bold uppercase tracking-wider w-fit"
                        >
                            <span class="material-symbols-outlined text-sm">verified</span>
                            Salud Digital Confiable
                        </div>
                        <h1
                            class="text-4xl md:text-6xl font-black leading-[1.1] tracking-tight text-[#0e121b] dark:text-white"
                        >
                            Tu salud en buenas manos, <span class="text-primary">dondequiera que estés</span>
                        </h1>
                        <p
                            class="text-lg md:text-xl text-gray-600 dark:text-gray-400 font-normal leading-relaxed max-w-lg"
                        >
                            Accede a telemedicina, gestión de citas e historia clínica digital desde un solo lugar. La
                            revolución médica en tu bolsillo.
                        </p>
                        <div class="flex flex-col sm:flex-row gap-4 mt-2">
                            <button
                                class="flex items-center justify-center gap-2 bg-primary text-white px-8 py-4 rounded-xl font-bold text-lg shadow-lg shadow-primary/25 hover:bg-primary/90 transition-all active:scale-95"
                            >
                                <span class="material-symbols-outlined">download</span>
                                Descargar App
                            </button>
                            <button
                                class="flex items-center justify-center gap-2 bg-white dark:bg-gray-800 border border-gray-200 dark:border-gray-700 text-[#0e121b] dark:text-white px-8 py-4 rounded-xl font-bold text-lg hover:bg-gray-50 dark:hover:bg-gray-700 transition-all active:scale-95"
                            >
                                <span class="material-symbols-outlined">medical_services</span>
                                Soy Médico
                            </button>
                        </div>
                    </div>
                    <div class="md:w-1/2 relative">
                        <div
                            class="w-full aspect-square md:aspect-video rounded-3xl bg-cover bg-center shadow-2xl overflow-hidden border-8 border-white dark:border-gray-800"
                            data-alt="Doctor holding a smartphone showing medical app interface"
                            style="
                                background-image: url(&quot;https://lh3.googleusercontent.com/aida-public/AB6AXuDoHVUQbFLj7IlU5pF5qUHdlaPTGqpQcOgiF1u4ApIxP8I_GSGcf82bHqFVK0xq4xmvPQmnMsQUl803OkWK2upkgL5EfBPd9ADOB3G5RA4q95vKv5__CvAr_P6nIanzYyFrrBqZ1mWrYl3M8hvPBbD5lPkbxY21OaIgeuQmBrs6XfCP_SyfpNdcP1XtnoFPOF6LvQbYeDG-3BURTQuy0pOlODFPVw5WdsR_cr8cs33QeaJK5uDBlGFY9fLsW0XMoPtk162mqy-py2M&quot;);
                            "
                        ></div>
                        <!-- Decorative Elements -->
                        <div
                            class="absolute -bottom-6 -left-6 bg-white dark:bg-gray-800 p-4 rounded-2xl shadow-xl flex items-center gap-4 border border-gray-100 dark:border-gray-700"
                        >
                            <div class="bg-green-100 p-2 rounded-full">
                                <span class="material-symbols-outlined text-green-600">check_circle</span>
                            </div>
                            <div>
                                <p class="text-xs text-gray-500">Médicos Activos</p>
                                <p class="font-bold text-[#0e121b] dark:text-white">+2,500 Profesionales</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </main>
</template>
