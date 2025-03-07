<template>
  <div>
    <footer class="bg-zinc-950 py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-lg font-bold mb-4">Contáctanos</h3>
                    <ul class="space-y-2 text-zinc-400">
                        <li>info@puressence.com</li>
                        <li>+1 (800) 555-1234</li>
                        <li>123 Fragrance Blvd, Suite 100</li>
                        <li>New York, NY 10001</li>
                    </ul>
                </div>

                <div>
                    <h3 class="text-lg font-bold mb-4">Información</h3>
                    <ul class="space-y-2 text-zinc-400">
                        <li><a href="#" class="hover:text-amber-300">Sobre nosotros</a></li>
                        <li><a href="#" class="hover:text-amber-300">Política de privacidad</a></li>
                        <li><a href="#" class="hover:text-amber-300">Términos y condiciones</a></li>
                        <li><a href="#" class="hover:text-amber-300">Preguntas frecuentes</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="text-lg font-bold mb-4">Mi cuenta</h3>
                    <ul class="space-y-2 text-zinc-400">
                        <li><a href="#" class="hover:text-amber-300">Iniciar sesión</a></li>
                        <li><a href="#" class="hover:text-amber-300">Registrarse</a></li>
                        <li><a href="#" class="hover:text-amber-300">Mis pedidos</a></li>
                        <li><a href="#" class="hover:text-amber-300">Lista de deseos</a></li>
                    </ul>
                </div>

                <div>
                    <h3 class="text-lg font-bold mb-4">Síguenos</h3>
                    <div class="flex gap-4 mb-6">
                        <a href="#" class="bg-zinc-900 p-2 rounded-full hover:bg-amber-700 transition">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5">
                                <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                                <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                                <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                            </svg>
                        </a>
                        <a href="#" class="bg-zinc-900 p-2 rounded-full hover:bg-amber-700 transition">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5">
                                <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path>
                            </svg>
                        </a>
                        <a href="#" class="bg-zinc-900 p-2 rounded-full hover:bg-amber-700 transition">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5">
                                <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                            </svg>
                        </a>
                        <a href="#" class="bg-zinc-900 p-2 rounded-full hover:bg-amber-700 transition">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5">
                                <path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path>
                                <polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon>
                            </svg>
                        </a>
                    </div>
                    <p class="text-zinc-500 text-sm">
                        Suscríbete a nuestro newsletter para recibir noticias y ofertas exclusivas.
                    </p>
                </div>
            </div>

            <div class="border-t border-zinc-800 mt-12 pt-6 flex flex-col md:flex-row justify-between items-center">
                <p class="text-zinc-500 text-sm">Copyright © 2025 PURE ESSENCE. All Rights Reserved.</p>
                <div class="flex gap-4 mt-4 md:mt-0">
                    <span class="text-zinc-500">Visa</span>
                    <span class="text-zinc-500">Mastercard</span>
                    <span class="text-zinc-500">PayPal</span>
                    <span class="text-zinc-500">American Express</span>
                </div>
            </div>
        </div>
    </footer>
  </div>
</template>

<script>
export default {
name:'FooterComponent'
}
</script>

<style>

</style>