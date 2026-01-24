<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} withBorderTop={true} className="py-6">
  <nav class="flex items-center justify-between px-4 md:px-12">
    <!-- Logo -->
    <div class="flex items-center">
      <svg width="97" height="105" viewBox="0 0 97 105" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-8 w-auto">
        <path opacity="0.5" d="M0.84375 29.5892V75.3785L43.791 45.7896V0L0.84375 29.5892Z" fill="black"/>
        <path opacity="0.5" d="M0.84375 75.3787V29.5891L43.791 59.1783V104.968L0.84375 75.3787Z" fill="black"/>
        <path opacity="0.5" d="M96.8438 29.5891V75.3787L53.8965 45.7895V0L96.8438 29.5891Z" fill="black"/>
        <path opacity="0.5" d="M96.8438 75.3787V29.5891L53.8965 59.1783V104.968L96.8438 75.3787Z" fill="black"/>
      </svg>
    </div>

    <!-- Links -->
    <div class="hidden md:flex items-center space-x-8 text-sm text-gray-600 font-medium">
      <a href="#solutions" class="hover:text-gray-900">Solutions</a>
      <a href="#security" class="hover:text-gray-900">Security</a>
      <a href="#customers" class="hover:text-gray-900">Customers</a>
      <a href="#about" class="hover:text-gray-900">About</a>
    </div>

    <!-- Action -->
    <div>
      <a href="#contact" class="inline-block px-6 py-2 bg-gray-900 hover:bg-gray-800 text-white text-sm font-medium rounded transition-colors">
        Get Started
      </a>
    </div>
  </nav>
</SectionWrapper>
