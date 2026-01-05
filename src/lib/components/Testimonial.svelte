<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 mb-16 text-center">
    <h2 class="font-serif text-4xl text-gray-900">Trusted by operations leaders</h2>
  </div>

  <div class="px-4 md:px-12 max-w-5xl mx-auto">
    <div class="flex flex-col md:flex-row gap-12 items-center">
      <!-- Image -->
      <div class="w-full md:w-1/3">
        <div class="aspect-[3/4] bg-gray-200 rounded-lg overflow-hidden relative">
          <img 
            src="/generated/image-confident-coo-or-operations-leader-in-a--1767611535346-1.webp" 
            alt="Operations Leader" 
            class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
          <div class="absolute bottom-4 left-4 text-white text-xs font-bold uppercase tracking-widest opacity-80">
            Wealth Manager
          </div>
        </div>
      </div>

      <!-- Quote -->
      <div class="w-full md:w-2/3">
        <blockquote class="font-light text-xl md:text-2xl text-gray-500 leading-relaxed mb-8">
          "We were wasting thousands of hours on manual compliance workflows. <span class="text-gray-900">Synthex delivered ROI in weeks, not months, and sits perfectly on our legacy systems without any migration headaches.</span>"
        </blockquote>
        
        <div class="border-t border-gray-200 border-dashed pt-6">
          <div class="font-serif text-lg font-bold text-gray-900">Sarah Mitchell</div>
          <div class="text-sm text-gray-500">Chief Operating Officer</div>
          <div class="text-sm text-gray-500">Mid-Market Wealth Management</div>
        </div>
      </div>
    </div>
  </div>
</SectionWrapper>
