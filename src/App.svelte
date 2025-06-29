<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";
  import Navbar from "./lib/components/Navbar.svelte";
  import Footer from "./lib/components/Footer.svelte";
  import Counter from "./lib/components/Counter.svelte";
</script>

<header>
  <Navbar />
</header>
<main>
  <div class="card">
    <Counter />
  </div>
</main>
<footer>
  <Footer />
</footer>

<style>
  footer {
    background-color: gainsboro;
  }
</style>
