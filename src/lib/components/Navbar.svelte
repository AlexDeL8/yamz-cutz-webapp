<script lang="ts">
  import BookingButton from "./BookingButton.svelte";
</script>

<nav>
  <ul class="navList">
    <li class="navListItem">Home</li>
    <li class="navListItem">Services & Work</li>
    <li class="navListItem">About</li>
  </ul>
  <div id="navBookingBtnContainer">
    <BookingButton buttonSize="regular" />
  </div>
</nav>

<style>
  nav {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
    column-gap: 4rem;
  }

  .navList {
    display: flex;
    flex-direction: row;
    column-gap: 3rem;
  }

  .navListItem {
    font-size: 1.25rem;
  }

  .navListItem:hover {
    cursor: pointer;
    text-decoration: underline;
  }

  #navBookingBtnContainer {
    align-self: flex-end;
    float: inline-end;
  }
</style>
