<script lang="ts">
  export let title: string;
  export let content: string;
  export let isActive: boolean;
</script>

<div class={`accordion-item ${isActive ? 'active' : ''}`}>
  <button class="accordion-toggle inline-flex items-center gap-x-4 text-start">
    <span class="icon-[tabler--plus] accordion-item-active:hidden text-base-content size-4.5 block shrink-0"></span>
    <span class="icon-[tabler--minus] accordion-item-active:block text-base-content size-4.5 hidden shrink-0"></span>
    {title}
  </button>
  <div class={`accordion-content w-full overflow-hidden transition-[height] duration-300 ${isActive ? '' : 'hidden'}`} role="region">
    <div class="px-5 pb-4">
      <p class="text-base-content/80 font-normal">{content}</p>
    </div>
  </div>
</div>

