<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import viteLogo from "/vite.svg";
  import Navbar from "./lib/components/Navbar.svelte";
  import Footer from "./lib/components/Footer.svelte";
</script>

<header>
  <Navbar />
</header>
<main>
  <div class="card">
    <p>Main</p>
  </div>
</main>
<footer>
  <Footer />
</footer>

<style>
  header {
    background-color: var(--sectionColor);
    color: var(--descriptionTextColor);
    padding: 1.25rem 2rem;
  }

  footer {
    background-color: var(--sectionColor);
    color: var(--descriptionTextColor);
    padding: 2rem 0rem;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
</style>
