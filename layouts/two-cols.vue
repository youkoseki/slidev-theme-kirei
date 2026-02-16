<template>
  <div class="slidev-layout two-cols flex flex-col h-full">
    <slot name="header" />
    <div class="flex-1 grid grid-cols-2 gap-8">
      <div>
        <slot name="default" />
      </div>
      <div>
        <slot name="right" />
      </div>
    </div>
  </div>
</template>
