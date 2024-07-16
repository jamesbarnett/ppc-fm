<button class="button" data-icon="shopping-cart">Add to Cart</button>
<style>
  button {
    cursor: pointer;
    background-color: var(--clr-primary-400);
    color: var(--clr-neutral-100);
    border-radius: 0.5rem;
    font-weight: var(--fw-bold);
    font-size: 0.925rem;
    border: 0;
    text-decoration: none;
    justify-content: center;
    align-items: center;
    gap: 0.75rem;
    display: inline-flex;
    padding: 0.75em 1.5em
  }

  button[data-icon="shopping-cart"]::before {
    content: ""; 
    width: 15px;
    height: 16px;
    background-image: url("images/icon-cart.svg");
  }

  button:is(:hover, :focus) {
    background-color: var(--clr-primary-500);
  }
</style>
