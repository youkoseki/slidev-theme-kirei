<template>
  <div class="slidev-layout center flex flex-col h-full">
    <slot name="header" />
    <div class="flex-1 flex items-center justify-center">
      <div class="text-center max-w-4/5">
        <slot />
      </div>
    </div>
  </div>
</template>
