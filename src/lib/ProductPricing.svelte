<div class="flex-group">
  <p class="product__price">
    <span class="visually-hidden">Current price:</span>
    $149.99
  </p>
  <p class="product__original-price">
    <span class="visually-hidden">Original price:</span>
    <s>$169.99</s>
  </p>
</div>
<style>

  .visually-hidden:not(:focus):not(:active) {
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px;
  }

  .flex-group {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    align-items: center;
  }

  .product__price {
    font-size: 2rem;
    font-family: var(--ff-accent);
    font-weight: var(--fw-bold);
    color: var(--clr-primary-400)
  }

  .product__original-price {
    text-transform: strikethrough;
  }
</style>
