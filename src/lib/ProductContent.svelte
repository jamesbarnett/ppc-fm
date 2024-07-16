<script>
  import ProductPricing from './ProductPricing.svelte'
  import Button from './Button.svelte'
</script>
<div class="product__content">
  <div class="product__category">Perfume</div>
  <h1 class="product__title">Gabrielle Essence Eau De Parfum</h1>
  <p>A floral, solar and voluptuous interpretation composed by Olivier Polge,
    Perfumer-Creator for the House of CHANEL.
  </p>
  <ProductPricing />
  <Button />
</div>
<style>
  .product__content {
    display: grid;
    gap: var(--content-spacing);
    padding: var(--content-padding);
  }

  .product__category {
    font-size: 0.8125rem;
    letter-spacing: 6px;
    text-transform: uppercase;
  }

  .product__title {
    font-size: 2em;
    font-family: var(--ff-accent);
    color: var(--clr-neutral-900);
    line-height: var(--title-line-height);
  }
</style>
