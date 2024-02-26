<template>
  <div class="container mx-auto max-w-4xl font-family-roboto">
    <header class="flex space-x-16">
      <div class="font">
        <NuxtLink to="/">
          hoang
        </NuxtLink>
      </div>
      <div>
        <Menu />
      </div>
      <ClientOnly>
        <ColorModeSelector />
      </ClientOnly>
    </header>
    <main>
      <div></div>
    </main>
  </div>
</template>

<style>
body {
  @apply font-mono bg-stone-200 dark:bg-gray-900 text-stone-800 dark:text-gray-300
}
</style>