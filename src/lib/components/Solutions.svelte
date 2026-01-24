<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">Proven use cases</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="Document Intelligence"
      title="Document Processing & Extraction"
      description="Transform unstructured data from documents, emails, video, and audio into structured, actionable workflows. Our AI agents extract, validate, and route information with human-in-the-loop controls, delivering compliance-grade automation at scale."
    >
      <!-- Visual for Block 1: Document Processing -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central AI Agent -->
        <div class="w-20 h-20 bg-gray-900 shadow-lg rounded-lg flex items-center justify-center z-10 border border-gray-800">
           <div class="text-white text-xs font-bold">AI Agent</div>
        </div>
        
        <!-- Connected Document Sources -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-200">
            <div class="w-10 h-10 bg-gray-100 rounded flex items-center justify-center text-[10px] font-bold text-gray-700">PDF</div>
            <div class="mt-1 text-[10px] text-center">Documents</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-200">
            <div class="w-10 h-10 bg-gray-900 rounded flex items-center justify-center text-[10px] font-bold text-white">Email</div>
            <div class="mt-1 text-[10px] text-center">Extraction</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-200">
            <div class="w-10 h-10 bg-gray-100 rounded flex items-center justify-center text-[10px] font-bold text-gray-700">Audio</div>
            <div class="mt-1 text-[10px] text-center">Processing</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-200">
            <div class="w-10 h-10 bg-gray-900 rounded flex items-center justify-center text-[10px] font-bold text-white">Video</div>
            <div class="mt-1 text-[10px] text-center">Analysis</div>
        </div>
        
        <!-- Connecting Lines -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Workflow Orchestration"
      title="Asset Transfer Automation"
      description="Eliminate 2,000+ working days of manual processing with intelligent workflow orchestration. Our AI agents coordinate asset transfers across legacy systems, delivering 9 FTE savings and £280K annual cost reduction."
      reversed={true}
    >
      <!-- Visual for Block 2: Workflow Card -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-gray-900 flex items-center justify-center text-white text-xs font-bold">
                AI
            </div>
            <div class="text-xs text-gray-500">Asset Transfer • In Progress</div>
        </div>
        <h4 class="font-serif text-xl mb-4">Portfolio Transfer</h4>
        <div class="space-y-2 mb-6">
            <div class="flex items-center gap-2">
              <div class="w-3 h-3 bg-green-500 rounded-full"></div>
              <div class="text-xs text-gray-600">Validation Complete</div>
            </div>
            <div class="flex items-center gap-2">
              <div class="w-3 h-3 bg-green-500 rounded-full"></div>
              <div class="text-xs text-gray-600">Legacy System Sync</div>
            </div>
            <div class="flex items-center gap-2">
              <div class="w-3 h-3 bg-gray-900 rounded-full animate-pulse"></div>
              <div class="text-xs text-gray-600">Compliance Check</div>
            </div>
        </div>
        <button class="w-full bg-gray-900 text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2">
            <span>View Audit Trail</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Quality Assurance"
      title="Contact Centre Intelligence"
      description="Achieve 100% coverage across 250K+ calls and 650K+ emails with AI-powered quality assurance. Replace <1% manual sampling with comprehensive monitoring, saving £500K annually while improving compliance oversight."
    >
       <!-- Visual for Block 3: QA Report -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">QA Dashboard</div>
              <div class="w-4 h-4 bg-gray-900 rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Call Analysis</h5>
              <div class="text-[10px] text-gray-400">8,000 calls monitored this month</div>
          </div>
          <div class="space-y-3 text-[10px] text-gray-600">
              <div class="flex justify-between items-center">
                <span>Compliance Score</span>
                <span class="font-bold text-green-600">98.5%</span>
              </div>
              <div class="flex justify-between items-center">
                <span>Risk Flags</span>
                <span class="font-bold text-gray-900">3</span>
              </div>
              <div class="flex justify-between items-center">
                <span>Coverage</span>
                <span class="font-bold text-gray-900">100%</span>
              </div>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
