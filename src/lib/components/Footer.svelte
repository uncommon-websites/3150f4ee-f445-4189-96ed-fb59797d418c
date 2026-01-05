<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<div class="bg-black text-white py-24 px-4 md:px-8 max-w-[1400px] mx-auto relative">
    <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-between gap-8">
        <h2 class="font-serif text-3xl md:text-4xl">
            Transform your operations
        </h2>
        
        <a href="#contact" class="inline-flex items-center px-6 py-3 bg-white text-black font-medium rounded hover:bg-gray-100 transition-colors">
            Book a Demo <span class="ml-2">→</span>
        </a>
    </div>
</div>

<SectionWrapper withBorderBottom={false} className="py-12">
    <div class="px-4 md:px-12">
        <!-- Top Row -->
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center border-b border-gray-200 border-dashed pb-12 mb-12">
            <div class="text-xs text-gray-500 mb-4 md:mb-0">
                hello@synthex.ai
            </div>
            
            <div class="flex space-x-6 text-xs text-gray-500 font-medium">
                <a href="#solutions" class="hover:text-gray-900">Solutions</a>
                <a href="#security" class="hover:text-gray-900">Security</a>
                <a href="#customers" class="hover:text-gray-900">Customers</a>
                <a href="#about" class="hover:text-gray-900">About</a>
            </div>
        </div>

        <!-- Bottom Row -->
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center text-[10px] text-gray-400">
            <div class="mb-4 md:mb-0">
                ©2025 Synthex. All rights reserved.
            </div>
            
            <div class="mb-4 md:mb-0">
                Synthex Ltd, London, United Kingdom
            </div>
            
            <div class="flex space-x-4">
                <a href="#" class="hover:text-gray-600">Privacy Policy</a>
                <span>•</span>
                <a href="#" class="hover:text-gray-600">Terms of Service</a>
            </div>
        </div>
    </div>
</SectionWrapper>

<!-- Cookie Banner -->
<div class="fixed bottom-4 right-4 bg-white border border-gray-200 shadow-lg p-4 rounded-lg max-w-sm z-50 flex items-center gap-4">
    <p class="text-xs text-gray-600">
        We use cookies to enhance your experience and analyze site usage.
    </p>
    <button class="text-xs font-medium bg-gray-900 hover:bg-gray-800 text-white px-3 py-1 rounded transition-colors">
        Accept
    </button>
</div>
