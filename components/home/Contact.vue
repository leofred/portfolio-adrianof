<template>
  <div id="contact" class="relative bg-white">
    <div class="absolute inset-0">
      <div class="absolute inset-y-0 left-0 w-1/2 bg-gray-100" />
    </div>
    <div class="relative mx-auto max-w-7xl lg:grid lg:grid-cols-5">
      <div class="bg-gray-100 py-16 px-4 sm:px-6 lg:col-span-2 lg:px-8 lg:py-24 xl:pr-12">
        <div class="mx-auto max-w-lg h-full flex flex-col">
          <h2 class="text-2xl font-bold tracking-tight text-gray-900 sm:text-3xl">Contato</h2>
          <p class="mt-3 text-lg h-full leading-6 text-gray-500">Entre em contato através do email ou WhatsApp, mande suas dúvidas, solicite um orçamento, responderei o mais breve possível.</p>
          <dl class="mt-8 text-base text-gray-500">
            <div class="mt-6">
              <dt class="sr-only">Phone number</dt>
              <dd>
                <a href="https://wa.me/5511984282844" class="flex" target="_blank">
                  <Icon name="fa-brands:whatsapp" class="h-6 w-6 flex-shrink-0 text-green-400" aria-hidden="true" />
                  <span class="ml-3">+55 (11) 98428-2844</span>
                </a>
              </dd>
            </div>
            <div class="mt-3">
              <dt class="sr-only">Email</dt>
              <dd>
                <a href="mailto:adriano.frederico@gmail.com" class="flex" target="_blank">
                  <Icon name="heroicons-outline:envelope" class="h-6 w-6 flex-shrink-0 text-gray-400"
                    aria-hidden="true" />
                  <span class="ml-3">adriano.frederico@gmail.com</span>
                </a>
              </dd>
            </div>
          </dl>
        </div>
      </div>
      <div class="bg-white py-16 px-4 sm:px-6 lg:col-span-3 lg:py-24 lg:px-8 xl:pl-12">
        <div class="mx-auto max-w-lg lg:max-w-none">
          <form action="#" method="POST" class="grid grid-cols-1 gap-y-6">
            <div>
              <label for="full-name" class="sr-only">Nome completo</label>
              <input type="text" name="full-name" id="full-name" autocomplete="name"
                class="block w-full rounded-md border-gray-300 py-3 px-4 placeholder-gray-500 shadow-sm focus:border-indigo-500 focus:ring-indigo-500"
                placeholder="Nome completo" />
            </div>
            <div>
              <label for="email" class="sr-only">Email</label>
              <input id="email" name="email" type="email" autocomplete="email"
                class="block w-full rounded-md border-gray-300 py-3 px-4 placeholder-gray-500 shadow-sm focus:border-indigo-500 focus:ring-indigo-500"
                placeholder="Email" />
            </div>
            <div>
              <label for="phone" class="sr-only">Telefone</label>
              <input type="text" name="phone" id="phone" autocomplete="tel"
                class="block w-full rounded-md border-gray-300 py-3 px-4 placeholder-gray-500 shadow-sm focus:border-indigo-500 focus:ring-indigo-500"
                placeholder="Telefone" />
            </div>
            <div>
              <label for="message" class="sr-only">Message</label>
              <textarea id="message" name="message" rows="4"
                class="block w-full rounded-md border-gray-300 py-3 px-4 placeholder-gray-500 shadow-sm focus:border-indigo-500 focus:ring-indigo-500"
                placeholder="Mensagem" />
            </div>
            <div>
              <button type="submit"
                class="inline-flex justify-center rounded-md border border-transparent bg-indigo-600 py-3 px-6 text-base font-medium text-white shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">Submit</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// import { EnvelopeIcon, PhoneIcon } from '@heroicons/vue/24/outline'
</script>