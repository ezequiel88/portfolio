<template>
    <div class="overflow-hidden bg-gray-900 min-h-screen">
        <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
            <div class="flex flex-col items-center justify-between xl:flex-row">
                <div class="w-full max-w-xl mb-12 xl:pr-16 xl:mb-0 xl:w-7/12">
                    <h2
                        class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-white sm:text-4xl sm:leading-none">
                        Estamos a um clique de distância. <span class="text-teal-accent-400 font-bolder">Deixe-me</span> transformar suas ideias em soluções inovadoras
                    </h2>

                    <div class="w-full gap-8 mt-20 grid grid-cols-2">
                        
                        <div class="flex flex-col max-w-md sm:flex-row">
                            <div class="mb-4 mr-4">
                                <div class="flex items-center justify-center w-12 h-12 rounded-full bg-indigo-50">
                                    <i class="fab fa-linkedin text-deep-purple-accent-400 text-2xl"></i>
                                </div>
                            </div>
                            <div>
                                <h6 class="mb-1 text-xl font-bold leading-5">LinkedIn</h6>
                                <p class="text-sm">
                                    @ezequiel_tav
                                </p>
                            </div>
                        </div>
                        <div class="flex flex-col max-w-md sm:flex-row">
                            <div class="mb-4 mr-4">
                                <div class="flex items-center justify-center w-12 h-12 rounded-full bg-indigo-50">
                                    <i class="fab fa-whatsapp text-deep-purple-accent-400 text-2xl"></i>
                                </div>
                            </div>
                            <div>
                                <h6 class="mb-1 text-xl font-bold leading-5">WhatsApp</h6>
                                <p class="text-sm">
                                    +55 54 984010108
                                </p>
                            </div>
                        </div>
                        <div class="flex flex-col max-w-md sm:flex-row">
                            <div class="mb-4 mr-4">
                                <div class="flex items-center justify-center w-12 h-12 rounded-full bg-indigo-50">
                                    <i class="fab fa-github text-deep-purple-accent-400 text-2xl"></i>
                                </div>
                            </div>
                            <div>
                                <h6 class="mb-1 text-xl font-bold leading-5">GitHub</h6>
                                <p class="text-sm">
                                    ezequiel88 </p>
                            </div>
                        </div>
                        <div class="flex flex-col max-w-md sm:flex-row">
                            <div class="mb-4 mr-4">
                                <div class="flex items-center justify-center w-12 h-12 rounded-full bg-indigo-50">
                                    <i class="fa fa-envelope text-deep-purple-accent-400 text-2xl"></i>
                                </div>
                            </div>
                            <div>
                                <h6 class="mb-1 text-xl font-bold leading-5">Email</h6>
                                <p class="text-sm">
                                    reacaosistemas@gmail.com
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w-full max-w-xl xl:px-8 xl:w-5/12">
                    <div class="relative">
                        <svg viewBox="0 0 52 24" fill="currentColor"
                            class="absolute bottom-0 right-0 z-0 hidden w-32 -mb-8 -mr-20 text-teal-accent-400 lg:w-32 lg:-mr-16 sm:block">
                            <defs>
                                <pattern id="766323e1-e594-4ffd-a688-e7275079d540" x="0" y="0" width=".135" height=".30">
                                    <circle cx="1" cy="1" r=".7"></circle>
                                </pattern>
                            </defs>
                            <rect fill="url(#766323e1-e594-4ffd-a688-e7275079d540)" width="52" height="24"></rect>
                        </svg>
                        <div class="relative bg-white rounded shadow-2xl p-7 sm:p-10">
                            <h3 class="mb-4 text-xl font-semibold sm:text-center sm:mb-6 sm:text-2xl">
                                Entre em contato
                            </h3>
                            <form>
                                <div class="mb-1 sm:mb-2">
                                    <label for="name" class="inline-block mb-1 font-medium">Seu nome</label>
                                    <input required type="text"
                                        class="flex-grow w-full h-10 px-3 mb-2 transition duration-200 bg-white border border-gray-300 rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
                                        id="name" name="name" />
                                </div>
                                <div class="mb-1 sm:mb-2">
                                    <label for="email" class="inline-block mb-1 font-medium">Seu melhor email</label>
                                    <input required type="text"
                                        class="flex-grow w-full h-10 px-3 mb-2 transition duration-200 bg-white border border-gray-300 rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
                                        id="email" name="email" />
                                </div>
                                <div class="mb-1 sm:mb-2">
                                    <label for="message" class="inline-block mb-1 font-medium">Sua mensagem</label>
                                    <textarea required rows="4"
                                        class="flex-grow w-full p-3 mb-2 transition duration-200 bg-white border border-gray-300 rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline resize-none"
                                        id="message" name="message"></textarea>
                                </div>
                                <div class="mt-4">
                                    <button type="submit"
                                        class="inline-flex items-center justify-center w-full h-10 px-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none">
                                        Enviar
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>