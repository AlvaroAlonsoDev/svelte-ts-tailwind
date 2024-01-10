<script>
  import Footer from "$lib/components/Footer.svelte";
  import Header from "$lib/components/Header.svelte";
  import "./styles.css";
</script>

<Header />

<div class="h-lvh">
  <!-- Delete style if you want -->
  <main style="min-height: calc(100vh - 76px);">
    <slot />
  </main>
  <Footer />
</div>
