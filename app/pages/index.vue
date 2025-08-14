<script setup lang="ts">

</script>

<template>
  <main class="max-w-[75rem] w-full mx-auto">
    <div class="grid grid-cols-[1fr_20.5rem] gap-10 pb-10">
      <div>
        <header class="flex items-center justify-between w-full h-16 gap-4">
          <NuxtLink to="/">
            <NuxtImg src="/images/RRlogo.png" alt="RoxRadarHQ" class="object-contain" />
          </NuxtLink>
          <div class="flex items-center gap-2">
            <OrganizationSwitcher
              :appearance="{
                elements: {
                  organizationPreviewAvatarBox: 'size-6',
                },
              }" />
            <UserButton
              :appearance="{
                elements: {
                  userButtonAvatarBox: 'size-6',
                },
              }" />
          </div>
        </header>
      </div>
    </div>
  </main>
</template>
