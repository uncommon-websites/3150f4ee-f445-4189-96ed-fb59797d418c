<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Logos -->
    <div class="flex flex-wrap items-center gap-8 md:gap-12 grayscale opacity-70">
        <!-- FNZ -->
        <div class="h-6 font-bold text-xl tracking-tight">FNZ</div>
        <!-- Wealth Manager -->
        <div class="h-8 flex flex-col leading-none text-xs font-serif uppercase tracking-widest">
            <span>Wealth</span>
            <span>Partners</span>
        </div>
        <!-- Asset Management -->
        <div class="h-6 font-bold text-lg tracking-tight font-serif">AssetCo</div>
        <!-- Private Bank -->
        <div class="h-6 font-medium text-lg flex items-center gap-1">
            <span class="font-bold">◆</span>
            <span class="font-serif">Private Bank</span>
        </div>
    </div>

    <!-- Trust Text -->
    <div class="text-gray-400 text-sm font-light text-right md:text-left">
      Trusted by leading wealth managers
    </div>
  </div>
</SectionWrapper>
