<script>
  import Picture from './lib/Picture.svelte'
  import ProductContent from './lib/ProductContent.svelte'
</script>

<main>
  <article class="product">
    <Picture />
    <ProductContent />
  </article>
</main>

<style>
  .product {
    --content-padding: 1.5rem;
    --content-spacing: 1rem;
    --title-line-height: 1;

    display: grid;
    background-color: var(--clr-neutral-100);
    border-radius: 0.5rem;
    overflow: hidden;
    max-width: 600px;
  }

  @media (min-width: 600px) {
    .product {
      --content-padding: 2rem;
      grid-template-columns: 1fr 1fr;
    }
  }

</style>
