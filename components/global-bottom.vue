<template>
  <!-- ページ番号（右下） -->
  <footer class="absolute bottom-0 right-0 p-2 text-xs text-gray-500">
    {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
  </footer>
  
  <!-- コピーライト透かし（左下） -->
  <footer class="absolute bottom-0 left-0 p-2 text-xs text-gray-400 opacity-70">
    © 2025 Kenta Kuzuhara
  </footer>
</template>