<script lang="ts">
  interface BookingButtonProps {
    buttonSize: "regular" | "large";
  }

  let { buttonSize }: BookingButtonProps = $props();

  const bookingAction = (text: string) => {
    console.log(text);
  };
</script>

<button
  class={`bookingBtn ${buttonSize}`}
  onclick={() => bookingAction("Booking clicked")}>Book Now</button
>

<style>
  .bookingBtn {
    background-color: transparent;
    border: 1px solid var(--accentColor);
    border-radius: 2px;
    color: var(--accentColor);
  }

  .bookingBtn.regular {
    font-size: 1.25rem;
    padding: 0.5rem 1.25rem;
  }

  .bookingBtn.large {
    font-size: 1.75rem;
    padding: 0.75rem 1.5rem;
  }

  .bookingBtn:hover {
    background-color: var(--accentColor);
    color: var(--descriptionTextAltColor);
  }
</style>
