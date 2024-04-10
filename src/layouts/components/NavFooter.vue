<template>
  <!-- footer -->
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Made&nbsp;
      <img src="../../assets/images/heart.svg" />&nbsp;
      By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://kafiirr.com"
        target="_blank"
        rel="noopener noreferrer"
        >Kafir Website</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline mr-4"
        href="https://x.com/Bacchetta0"
        target="noopener noreferrer"
        >X</a
      >
      <a
        class="link link-primary no-underline"
        href="https://github.com/Kafiirr"
        target="noopener noreferrer"
        >Github</a
      >
    </div>
  </footer>
</template>