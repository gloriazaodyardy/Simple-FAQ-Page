<script setup>
</script>

<template>
  <header class="bg-white">
    <h1>Frequently Asked Questions</h1>
    <p>Browse through the most frequently asked questions</p>
  </header>
  <main class="flex bg-light">
    <div class="FAQSections flex">
      <section class="FAQSection flex">
        <h2>How can I track my order?</h2>
        <p>You can track your order using the following steps:</p>
        <ol>
          <li>Go to the Order <a href="#">Tracking page</a>.</li>
          <li>Enter your order number and email address.</li>
          <li>Click on the Track Order button to view the current status of your shipment.</li>
        </ol>
        <p>If you encounter any issues, please visit our <a href="#">Help Center</a>.</p>
      </section>
      <section class="FAQSection flex">
        <h2>What is your return policy?</h2>
        <p>We offer a 30-day return policy on most items. Here are some key points:</p>
        <ul>
          <li><b>Items must be in original condition</b>: Unworn, unused, and unwashed.</li>
          <li><b>Include original packaging and tags</b>: All items should be returned with their original packaging
            and tags.</li>
          <li><b>Proof of purchase</b>: A receipt or proof of purchase is required.</li>
        </ul>
        <p>For more detailed information, read our full <a href="#">Return Policy</a>.</p>
      </section>
    </div>
  </main>
  <footer class="bg-light">
    <p>
      Coded by <a href="#">Gloriaza</a> | Challenge by
      <a href="https://www.devchallenges.io?ref=challenge" target="_blank">devChallenges.io</a>.
    </p>
  </footer>
</template>

<style scoped>
@import url(./assets/base.css);

.FAQSections {
  gap: 1rem;
  max-width: 38rem;
  margin-inline: 1rem;
  flex-direction: column;
  justify-content: center;
}

section.FAQSection:first-of-type {
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--gray-medium);
}

.FAQSection {
  gap: 1rem;
  flex-direction: column;
}

@media (min-width>768px) {
  .FAQSections {
    margin-inline: 0;
  }
}
</style>