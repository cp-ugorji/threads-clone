<script setup></script>

<template>
  <div id="MainLayout" class="h-screen">
    <!-- Top menu -->
    <LayoutsTopMenu />

    <!-- main content area -->
    <div class="flex w-full max-w-[500px] mx-auto h-screen">
      <slot />
    </div>

    <!-- Bottom menu -->
    <LayoutsBottomMenu />
  </div>
</template>
