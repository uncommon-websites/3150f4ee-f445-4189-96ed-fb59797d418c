<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Zero-Migration Overlay
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      Works with your existing systems
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      Synthex sits on top of your legacy infrastructure. No data migration, no rip-and-replace. Deep integrations with CRMs, core systems, and APIs enable adoption in weeks, not months.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Logos Row -->
    <div class="flex flex-wrap md:flex-nowrap items-center justify-center md:justify-between gap-8 relative z-10">
      
      <!-- Logo 1 - Legacy CRM -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-600">Legacy<br/>CRM</div>
      </div>

       <!-- Logo 2 - Core Banking -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-600">Core<br/>System</div>
      </div>

       <!-- Center Logo (Synthex) -->
      <div class="w-24 h-24 bg-gray-900 rounded-full shadow-lg border-4 border-white flex items-center justify-center p-2 relative">
        <svg width="48" height="28" viewBox="0 0 116 68" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-auto">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M44.6215 56.0343C46.6079 53.651 49.5502 52.2726 52.6531 52.2726H94.8018C106.35 52.2726 115.711 42.9114 115.711 31.3637V20.909C115.711 9.36134 106.35 0 94.8018 0H86.6303C83.5277 0 80.5851 1.37818 78.599 3.76179L71.8003 11.9201C69.814 14.3037 66.8716 15.6818 63.7688 15.6818H21.62C10.0722 15.6818 0.710938 25.043 0.710938 36.5909V47.0454C0.710938 58.5933 10.0722 67.9546 21.62 67.9546H29.7916C32.8942 67.9546 35.8367 66.5765 37.8229 64.1929L44.6215 56.0343ZM100.029 20.909C100.029 18.022 97.6888 15.6818 94.8018 15.6818H78.7895C75.6866 15.6818 72.7443 17.0599 70.7579 19.4435L63.9593 27.602C61.9731 29.9854 59.0306 31.3637 55.9279 31.3637H21.62C18.7331 31.3637 16.3927 33.704 16.3927 36.5909V47.0454C16.3927 49.9324 18.7331 52.2726 21.62 52.2726H37.6324C40.7352 52.2726 43.6776 50.8945 45.664 48.5109L52.4626 40.3526C54.4488 37.969 57.3913 36.5909 60.4939 36.5909H94.8018C97.6888 36.5909 100.029 34.2507 100.029 31.3637V20.909Z" fill="white"/>
        </svg>
        <!-- Orbit ring visual -->
        <div class="absolute inset-0 rounded-full border border-gray-700 scale-110 opacity-50"></div>
      </div>

       <!-- Logo 3 - Document Management -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-600">Doc<br/>Mgmt</div>
      </div>

       <!-- Logo 4 - APIs -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-600">APIs</div>
      </div>

    </div>
  </div>
</SectionWrapper>
