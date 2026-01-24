<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-20 md:py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center">
    <h1 class="font-serif text-5xl md:text-7xl text-gray-900 mb-6 leading-tight">
      AI agents that automate <br/> financial workflows
    </h1>
    <p class="text-gray-500 text-lg md:text-xl max-w-2xl mx-auto mb-10 leading-relaxed font-light">
      Synthex handles the most complex regulated workflows with agentic processes, human-in-the-loop controls, and intelligent orchestration. Extract data from documents, emails, video, audio, and any unstructured source to automate end-to-end operations across your legacy systems.
    </p>
    <a href="#contact" class="inline-flex items-center px-6 py-3 bg-gray-900 text-white font-medium rounded hover:bg-gray-800 transition-colors">
      Book a Demo <span class="ml-2">→</span>
    </a>
  </div>

  <div class="mt-16 md:mt-20 px-4 md:px-12">
    <div class="relative w-full aspect-[16/9] md:aspect-[21/9] rounded-lg overflow-hidden bg-gray-200">
      <img 
        src="/generated/image-modern-financial-operations-center-with--1767611531379-0.webp" 
        alt="Financial operations center with AI-powered workflow automation" 
        class="w-full h-full object-cover"
      />
    </div>
  </div>
</SectionWrapper>
