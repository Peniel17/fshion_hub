<template>
    <div class="product-page">
      <div class="image-section">
        <div class="product-image" style="background-color: #f4e7da;"></div>
      </div>
      <div class="details-section">
        <h2>Embrace Sideboard</h2>
        <p class="subtitle">Teixeira Design Studio</p>
        <div class="pricing">
          <span class="current-price">$71.56</span>
          <span class="original-price">$71.56</span>
        </div>
        <div class="reviews">
          <span>⭐ 4.8</span>
          <span>67 Reviews</span>
          <span>93% of buyers recommended this</span>
        </div>
        <div class="options">
          <h3>Choose a Color</h3>
          <div class="colors">
            <span class="color" style="background-color: #f4e7da;"></span>
            <span class="color" style="background-color: #b5e7a0;"></span>
            <span class="color" style="background-color: #d9b8f1;"></span>
            <span class="color" style="background-color: #f7c8da;"></span>
          </div>
          <h3>Choose a Size</h3>
          <div class="sizes">
            <button>Small</button>
            <button>Medium</button>
            <button>Large</button>
            <button>Extra Large</button>
            <button>XXL</button>
          </div>
          <div class="quantity">
            <button>-</button>
            <span>1</span>
            <button>+</button>
          </div>
          <button class="add-to-cart">Add to Cart</button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ProductPage',
  };
  </script>
  
  <style>
  .product-page {
    display: flex;
    padding: 20px;
    gap: 30px;
  }
  .image-section {
    flex: 1;
  }
  .product-image {
    width: 100%;
    height: 300px;
    border-radius: 10px;
  }
  .details-section {
    flex: 2;
  }
  .pricing {
    display: flex;
    gap: 10px;
    font-size: 18px;
  }
  .reviews {
    margin: 10px 0;
    font-size: 14px;
  }
  .colors {
    display: flex;
    gap: 10px;
  }
  .color {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    cursor: pointer;
    border: 2px solid #ddd;
  }
  .sizes {
    display: flex;
    gap: 10px;
    margin-top: 10px;
  }
  .sizes button {
    padding: 5px 10px;
    cursor: pointer;
  }
  .quantity {
    display: flex;
    align-items: center;
    gap: 10px;
    margin: 10px 0;
  }
  .quantity button {
    padding: 5px 10px;
  }
  .add-to-cart {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
  }
  </style>
  