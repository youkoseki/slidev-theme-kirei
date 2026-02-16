<template>
  <div class="slidev-layout three-cols flex flex-col h-full">
    <slot name="header" />
    <div class="flex-1 grid grid-cols-3 gap-8">
      <div>
        <slot name="default" />
      </div>
      <div>
        <slot name="center" />
      </div>
      <div>
        <slot name="right" />
      </div>
    </div>
  </div>
</template>
