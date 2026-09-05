<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta content="width=device-width, initial-scale=1.0" name="viewport">
<title>Serve Up Udipi Cafe - 100% Vegetarian</title>
<style>
:root {
  --red: #C41E3A;
  --dark-red: #8B0000;
  --maroon: #5A0000;
  --yellow: #FFD700;
  --peach: #FFDAB9;
  --white: #FFFFFF;
  --light-gray: #F5F5F5;
  --text-dark: #1A1A1A;
  --shadow: 0 4px 12px rgba(0,0,0,0.15);
  --shadow-lg: 0 8px 24px rgba(0,0,0,0.2);
}
* { margin: 0; padding: 0; box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  background-color: #FFF8E1;
  color: #5D4037;
  line-height: 1.5;
  font-size: 17px;
  -webkit-tap-highlight-color: transparent;
}
h1, h2, h3 { color: #C62828; }

/* ULTRA-THIN STICKY HEADER */
.header {
  background: linear-gradient(135deg, var(--red) 0%, var(--dark-red) 100%);
  color: var(--white);
  padding: 0.2rem 0.75rem;
  box-shadow: var(--shadow-lg);
  position: sticky;
  top: 0;
  z-index: 100;
}
.logo-row {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 0.5rem;
}
.header-left  { font-size: 0.85rem; font-weight: 700; color: var(--white); white-space: nowrap; }
.header-center{ font-size: 0.85rem; font-weight: 700; color: var(--white); white-space: nowrap; }
.veg-badge    { background: var(--yellow); color: var(--dark-red); padding: 0.12rem 0.45rem; border-radius: 50px; font-weight: 700; font-size: 0.62rem; white-space: nowrap; }

/* FLOATING CART HUB */
.cart-hub-btn {
  position: fixed;
  top: 14px;
  right: 14px;
  z-index: 200;
  background: var(--maroon);
  color: var(--white);
  border: 2px solid var(--yellow);
  border-radius: 50px;
  padding: 0.5rem 0.9rem;
  display: flex;
  align-items: center;
  gap: 0.4rem;
  font-weight: 700;
  font-size: 0.9rem;
  cursor: pointer;
  box-shadow: var(--shadow-lg);
  font-family: inherit;
}
.cart-hub-icon { font-size: 1.2rem; line-height: 1; }
.cart-hub-badge { display: none !important; /* hidden per request */ 
  background: var(--yellow);
  color: var(--dark-red);
  border-radius: 50%;
  min-width: 22px;
  height: 22px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.78rem;
  font-weight: 800;
  padding: 0 4px;
}
.cart-overlay {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.5);
  z-index: 250;
}
.cart-overlay.open { display: block; }
.cart-drawer {
  position: fixed;
  top: 0;
  right: -100%;
  width: 92%;
  max-width: 420px;
  height: 100%;
  background: var(--peach);
  z-index: 260;
  overflow-y: auto;
  padding: 0.85rem;
  transition: right 0.25s ease;
  box-shadow: var(--shadow-lg);
}
.cart-drawer.open { right: 0; }
.cart-drawer-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.6rem; }
.cart-drawer-close {
  background: var(--maroon);
  color: var(--white);
  border: none;
  border-radius: 50%;
  width: 34px;
  height: 34px;
  font-size: 1.1rem;
  font-weight: 700;
  cursor: pointer;
}
.employee-note {
  background: var(--yellow);
  color: var(--dark-red);
  border: 2px dashed var(--dark-red);
  border-radius: 8px;
  padding: 0.55rem 0.7rem;
  font-size: 0.85rem;
  font-weight: 700;
  text-align: center;
  margin-bottom: 0.6rem;
}

/* BUTTONS */
.btn {
  padding: 0.35rem 0.75rem;
  border: none; border-radius: 6px;
  font-size: 0.8rem; font-weight: 600;
  cursor: pointer; transition: opacity 0.15s;
  font-family: inherit; touch-action: manipulation;
}
.btn:active { opacity: 0.75; }
.btn-empty { background: var(--yellow); color: var(--dark-red); }
.btn-print { background: var(--dark-red); color: var(--white); }
.btn-add   { background: var(--red); color: var(--white); width: 100%; font-size: 0.78rem; padding: 0.4rem 0.5rem; }

/* PAGE LAYOUT */
.main-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0.6rem;
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.75rem;
}

/* MENU */
.menu-section {
  display: flex; flex-direction: column; gap: 0.6rem;
  background-color: #FFF3E0; border: 1px solid #D7CCC8;
  padding: 6px; border-radius: 10px;
}
.category { background: var(--white); border-radius: 8px; overflow: hidden; box-shadow: 0 2px 6px rgba(0,0,0,0.1); border: 1px solid #D7CCC8; }
.category-header { background: linear-gradient(135deg, var(--dark-red) 0%, var(--maroon) 100%); color: var(--white); padding: 0.7rem 1rem; font-size: 1.15rem; font-weight: 700; }
.category-subtitle { padding: 0.35rem 0.85rem 0; font-size: 0.85rem; color: #6D4C41; font-style: italic; }
.category-items { padding: 0.4rem; display: flex; flex-direction: column; gap: 0.35rem; }
.menu-item { background: var(--white); border-radius: 10px; padding: 0.75rem; display: flex; justify-content: space-between; align-items: flex-start; gap: 0.75rem; box-shadow: 0 1px 5px rgba(0,0,0,0.08); }
.item-details  { flex: 1; min-width: 0; }
.item-name { font-size: 1.05rem; font-weight: 700; color: var(--text-dark); }
.item-desc { font-size: 0.85rem; color: #6D4C41; margin-top: 0.2rem; line-height: 1.45; }
.item-price { font-size: 1.05rem; font-weight: 700; color: #B71C1C; margin-top: 0.25rem; }
.item-action   { flex-shrink: 0; width: 92px; }

/* CART DRAWER CONTENTS */
.cart-sidebar {
  background: transparent;
  border-radius: 0;
  padding: 0;
  box-shadow: none;
  border: none;
}
.cart-sidebar h2 { font-size: 1.3rem; color: var(--maroon); margin-bottom: 0.6rem; }
.table-number-section { background: var(--white); border-radius: 7px; padding: 0.6rem; margin-bottom: 0.6rem; border: 2px solid var(--red); }
.table-number-label { display: block; font-weight: bold; font-size: 0.85rem; margin-bottom: 3px; }
.table-number-input { width: 100%; padding: 0.5rem; border: 2px solid var(--dark-red); border-radius: 7px; font-size: 1.2rem; font-weight: 700; text-align: center; }
.party-size-section { background: var(--white); border-radius: 7px; padding: 0.6rem; margin-bottom: 0.6rem; border: 2px solid var(--red); }
.party-size-label { display: block; font-weight: bold; font-size: 0.85rem; margin-bottom: 3px; }
.party-size-input { width: 100%; padding: 0.5rem; border: 2px solid var(--dark-red); border-radius: 7px; font-size: 1.2rem; font-weight: 700; text-align: center; }
.gratuity-note { font-size: 0.8rem; color: var(--dark-red); margin-top: 4px; font-weight: 700; text-align: center; }
.cart-empty { text-align: center; padding: 0.6rem; font-weight: bold; font-size: 1rem; }
.cart-items { display: flex; flex-direction: column; gap: 0.5rem; margin-bottom: 0.6rem; }
.cart-item { background: var(--white); border-radius: 7px; padding: 0.6rem; box-shadow: 0 1px 3px rgba(0,0,0,0.1); }
.cart-item-header { display: flex; justify-content: space-between; font-size: 0.95rem; font-weight: 700; }
.cart-item-controls { display: flex; justify-content: space-between; align-items: center; margin-top: 6px; }
.qty-controls { display: flex; align-items: center; gap: 0.25rem; background: var(--light-gray); border-radius: 7px; padding: 0.2rem; }
.qty-btn { background: var(--red); color: var(--white); border: none; width: 28px; height: 28px; border-radius: 5px; font-size: 1.1rem; font-weight: 700; cursor: pointer; }
.qty-display { font-size: 0.95rem; font-weight: 700; min-width: 24px; text-align: center; }
.btn-remove { background: var(--maroon); color: var(--white); border: none; padding: 0.3rem 0.6rem; border-radius: 5px; cursor: pointer; font-size: 0.8rem; }
.spice-section { margin-top: 0.5rem; }
.spice-label { font-size: 0.78rem; font-weight: 700; color: var(--maroon); display: block; margin-bottom: 3px; }
.spice-options { display: flex; gap: 0.3rem; flex-wrap: wrap; }
.spice-btn {
  flex: 1; min-width: 70px;
  background: var(--light-gray); color: var(--text-dark);
  border: 2px solid #ccc; border-radius: 6px;
  padding: 0.35rem 0.4rem; font-size: 0.78rem; font-weight: 700;
  cursor: pointer; font-family: inherit;
}
.spice-btn.selected { background: var(--red); color: var(--white); border-color: var(--dark-red); }
.spice-btn.selected[data-level="Super Spicy"] { background: var(--dark-red); }
.masala-side-section { margin-top: 0.45rem; }
.masala-side-btn {
  width: 100%;
  background: var(--light-gray); color: var(--text-dark);
  border: 2px solid #ccc; border-radius: 6px;
  padding: 0.35rem 0.4rem; font-size: 0.78rem; font-weight: 700;
  cursor: pointer; font-family: inherit;
}
.masala-side-btn.selected { background: var(--yellow); border-color: var(--dark-red); color: var(--dark-red); }
.cart-total { background: linear-gradient(135deg, var(--maroon) 0%, var(--dark-red) 100%); color: var(--white); padding: 0.7rem; border-radius: 7px; margin-bottom: 0.6rem; }
.total-row { display: flex; justify-content: space-between; font-size: 0.95rem; margin-bottom: 0.25rem; }
.total-row-final { font-size: 1.1rem; font-weight: 700; border-top: 2px solid rgba(255,255,255,0.3); padding-top: 0.35rem; display: flex; justify-content: space-between; }
.cart-sidebar-actions .btn { width: 100%; padding: 0.55rem; font-size: 0.9rem; margin-bottom: 6px; }
.section-alt { background: var(--yellow); }
.section-alt .category-header { background: linear-gradient(135deg, var(--dark-red) 0%, var(--maroon) 100%); color: var(--white); padding: 0.7rem 1rem; font-size: 1.15rem; font-weight: 700; }


/* PRINT */
#receipt-content { display: none; }
@media print {
  @page { size: portrait; margin: 0.3in 0.4in; }
  body, html { background: #fff !important; color: #000 !important; height: auto !important; overflow: visible !important; margin: 0 !important; padding: 0 !important; }
  .no-print, header, .header, .main-container, main, .menu-section, .cart-sidebar, .cart-hub-btn, .cart-overlay, .cart-drawer, button { display: none !important; }
  #receipt-content { display: block !important; width: 100% !important; }
  .single-receipt-copy { width: 100% !important; max-width: 4in; margin: 0 auto !important; font-family: 'Courier New', monospace !important; font-size: 12px !important; line-height: 1.4 !important; color: #000 !important; }
  .receipt-page-break { page-break-after: always; break-after: page; }
  .receipt-header { text-align: center; font-weight: bold; font-size: 18px; margin-bottom: 4px; }
  .receipt-copy-label { text-align: center; font-weight: bold; font-size: 13px; text-transform: uppercase; letter-spacing: 1px; margin: 4px 0; border: 1px dashed #000; padding: 3px; }
  .receipt-info { text-align: center; font-size: 11px; margin: 3px 0; }
  .receipt-table { margin: 8px 0; font-weight: bold; text-align: center; font-size: 17px; border: 2px solid #000; padding: 4px; }
  .receipt-divider { border: none; border-top: 1px dashed #000; margin: 6px 0; }
  .receipt-divider-solid { border: none; border-top: 2px solid #000; margin: 6px 0; }
  .receipt-item-row { display: flex; justify-content: space-between; margin: 4px 0; font-size: 12px; }
  .receipt-item-name { flex: 1; padding-right: 6px; }
  .receipt-item-detail { padding-left: 15px; font-size: 10px; font-style: italic; margin-bottom: 4px; color: #333; }
  .receipt-total-row { display: flex; justify-content: space-between; font-weight: bold; margin: 4px 0; font-size: 13px; }
  .receipt-grand-total { font-size: 17px; }
  .receipt-footer { text-align: center; margin-top: 12px; font-weight: bold; font-size: 13px; }
}

/* MOBILE / TABLET */
@media (max-width: 859px) {
  .menu-item { background: var(--white); border-radius: 10px; padding: 0.75rem; display: flex; justify-content: space-between; align-items: flex-start; gap: 0.75rem; box-shadow: 0 1px 5px rgba(0,0,0,0.08); }
  .item-action { width: 100%; margin-top: 0.35rem; }
}
@media (max-width: 480px) {
  .logo-row { flex-wrap: wrap; justify-content: space-between; }
  .header-left, .header-center { font-size: 0.78rem; }
  .cart-drawer { width: 100%; max-width: none; }
}
</style>
</head>
<body>

<header class="header no-print">
  <div class="logo-row">
    <div class="header-left">Serve Up</div>
    <div class="header-center">Udipi Cafe</div>
    <div class="veg-badge">100% VEGETARIAN</div>
  </div>
</header>

<button class="cart-hub-btn no-print" onclick="toggleCart(true)" type="button">
  <span class="cart-hub-icon">🛒</span>
  <span id="cartCount">0</span>
  
</button>

<div class="main-container no-print">
  <main class="menu-section">

    <!-- UDIPI MEALS -->
    <div class="category">
      <div class="category-header">Special Dishes</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Poori Sabzi (2 pcs) <small style="color:#888;font-size:0.8rem;">no Gluten free</small></div>
            <div class="item-desc">Whole Wheat Puffy Bread Served with Potato Curry.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Poori Sabzi (2)', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Poori Channa (2 pcs) <small style="color:#888;font-size:0.8rem;">no Gluten free</small></div>
            <div class="item-desc">Whole Wheat Puffy Bread Served with Chickpea Curry.</div>
            <div class="item-price">$12.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Poori Channa (2)', 12.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chana Bhatura <small style="color:#888;font-size:0.8rem;">no Gluten free</small></div>
            <div class="item-desc">Puffy Bread Served with Chickpea Curry.</div>
            <div class="item-price">$12.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chana Bhatura', 12.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Pongal Sambar <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Rice &amp; Lentil Cooked in Milk &amp; Spices.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Pongal Sambar', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Pesarat</div>
            <div class="item-desc">Thin Whole Moong Lentil Crepes Stuffed with Uppma &amp; Served with Sambhar/Coco Chutney.</div>
            <div class="item-price">$12.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Pesarat', 12.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Pav Bhajji <small style="color:#888;font-size:0.8rem;">no Vegan / no Gluten free</small></div>
            <div class="item-desc">Fresh Minced Vegetables Cooked &amp; Served with Bread (Pav).</div>
            <div class="item-price">$12.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Pav Bhajji', 12.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Uppma <small style="color:#888;font-size:0.8rem;">no Vegan / no Gluten free</small></div>
            <div class="item-desc">Cream of Wheat Cooked with Milk, Onions, Cashews &amp; Indian Spices.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Uppma', 11.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- RICE SPECIALS -->
    <div class="category section-alt">
      <div class="category-header">Rice Specials</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bisi Bele Bhath</div>
            <div class="item-desc">Basmati Rice Cooked with Lentils, Fresh Vegetables &amp; Peanuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bisi Bele Bhath', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bagala Bhath <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Yogurt Rice with Mustard Seeds &amp; Cucumbers.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bagala Bhath', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Pulav</div>
            <div class="item-desc">Fresh Vegetables Cooked with Basmati Rice, Indian Spices &amp; Nuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Pulav', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Lemon Rice</div>
            <div class="item-desc">Basmati Rice Cooked with Lemon Juice, Indian Spices &amp; Peanuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Lemon Rice', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Coconut Rice</div>
            <div class="item-desc">Basmati Rice Cooked with Grated Fresh Coconut, Indian Spices &amp; Peanuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Coconut Rice', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tomato Rice</div>
            <div class="item-desc">Basmati Rice Cooked with Fresh Tomatoes, Indian Spices &amp; Peanuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tomato Rice', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tamarind Rice</div>
            <div class="item-desc">Basmati Rice Cooked with Homemade Tamarind Sauce, Indian Spices &amp; Peanuts.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tamarind Rice', 11.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- APPETIZERS -->
    <div class="category">
      <div class="category-header">Appetizers</div>
      <div class="category-subtitle">Served with sauces. Any substitutes will be charged extra.</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Idli (2 pcs)</div>
            <div class="item-desc">Steamed Rice &amp; Lentil Patties Served with Sambhar &amp; Coconut Chutney.</div>
            <div class="item-price">$7.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Idli (2)', 7.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Idli Fry</div>
            <div class="item-desc">Cut pieces of idli fried to perfection.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Idli Fry', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sambhar Idli (2 pcs)</div>
            <div class="item-desc">Steamed Rice &amp; Lentil Patties Dipped in Sambhar.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sambhar Idli (2)', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rasam Idli (2 pcs)</div>
            <div class="item-desc">Steamed Rice &amp; Lentil Patties Dipped in Rasam.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rasam Idli (2)', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Idli/Vada Combo (1 pc each)</div>
            <div class="item-desc">Served with Sambhar &amp; Coconut Chutney.</div>
            <div class="item-price">$7.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Idli/Vada Combo', 7.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Medhu Vada (2 pcs)</div>
            <div class="item-desc">Fried Lentil Donuts Served with Sambhar &amp; Coconut Chutney.</div>
            <div class="item-price">$7.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Medhu Vada (2)', 7.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sambhar Vada (2 pcs)</div>
            <div class="item-desc">Fried Lentil Donuts Dipped in Sambhar.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sambhar Vada (2)', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rasam Vada (2 pcs)</div>
            <div class="item-desc">Fried Lentil Donuts Dipped in Rasam.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rasam Vada (2)', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Dahi Vada (2 pcs) <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Fried Lentil Donuts Dipped in Yogurt.</div>
            <div class="item-price">$8.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Dahi Vada (2)', 8.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Dal Vada / Masala Vada (4 pcs)</div>
            <div class="item-desc">Golden Brown Lentil Patties Served with Mint/Tamarind Chutney.</div>
            <div class="item-price">$8.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Dal Vada (Masala Vada)', 8.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Cutlet (2 pcs) <small style="color:#888;font-size:0.8rem;">Gluten</small></div>
            <div class="item-desc">Minced Vegetables with Spices, Crumbed &amp; Deep Fried.</div>
            <div class="item-price">$8.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Cutlet (2)', 8.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Samosa (2 pcs) <small style="color:#888;font-size:0.8rem;">Gluten</small></div>
            <div class="item-desc">Crispy &amp; Flaky Crust Stuffed with Potatoes, Peas &amp; Indian Spices.</div>
            <div class="item-price">$7.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Samosa (2)', 7.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Potato Bonda (2 pcs)</div>
            <div class="item-desc">Potatoes Dumplings Dipped in Chickpea Flour &amp; Deep Fried.</div>
            <div class="item-price">$7.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Potato Bonda (2)', 7.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sambhar Bonda (2 pcs)</div>
            <div class="item-desc">Potato Dumplings Dipped in Sambhar &amp; Served with Coconut Chutney.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sambhar Bonda (2)', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mix Vegetable Pakoda</div>
            <div class="item-desc">Potatoes, Onions &amp; Chilies Marinated in Chickpea Flour &amp; Deep Fried.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mix Vegetable Pakoda', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chili Pakoda (Mirchi Bajji)</div>
            <div class="item-desc">Spicy Hot Chilies Marinated in Chickpea Flour &amp; Deep Fried.</div>
            <div class="item-price">$10.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chili Pakoda (Mirchi Bajji)', 10.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paneer Pakoda <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Homemade Cottage Cheese Marinated in Chickpea Flour &amp; Deep Fried.</div>
            <div class="item-price">$10.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paneer Pakoda', 10.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Veg Spring Roll <small style="color:#888;font-size:0.8rem;">Gluten</small></div>
            <div class="item-desc">Crispy spring rolls filled with seasoned mixed vegetables, deep fried to golden perfection.</div>
            <div class="item-price">$8.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Veg Spring Roll', 8.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vada Pav</div>
            <div class="item-desc">Spiced potato fritter tucked inside a soft bread roll with chutneys. A beloved Mumbai street food classic.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vada Pav', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item" style="background: #FFF8E1; border: 2px solid var(--dark-red);">
          <div class="item-details">
            <div class="item-name" style="color: var(--dark-red);">Appetizer Sampler</div>
            <div class="item-desc">Vegetable Cutlet, Vegetable Samosa, Idli, Medhu Vada, Pakoda. Add $2.00 extra for any substitution.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Appetizer Sampler', 14.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- SOUPS -->
    <div class="category section-alt">
      <div class="category-header">Soups</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tomato Soup</div>
            <div class="item-desc">Made from Fresh Tomatoes &amp; Spices (8oz).</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tomato Soup', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rasam Soup</div>
            <div class="item-desc">Traditional South Indian Sour &amp; Spicy Soup (8oz).</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rasam Soup', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Soup <small style="color:#888;font-size:0.8rem;">not Gluten free / not Vegan</small></div>
            <div class="item-desc">Made from Fresh Vegetable &amp; Spices (8oz).</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Soup', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sambhar Soup</div>
            <div class="item-desc">Vegetables &amp; Lentils Blended with Exotic Spices (8oz).</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sambhar Soup', 2.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- UDIPI CHAT -->
    <div class="category">
      <div class="category-header">Udipi Chat</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Pani Puri</div>
            <div class="item-desc">Hollow crispy semolina shells filled with spiced chickpeas and potatoes, dunked in tangy tamarind-mint water.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Pani Puri', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Samosa Chat</div>
            <div class="item-desc">Crushed samosas layered with spiced chickpeas, yogurt, tamarind chutney, mint chutney, sev, and chaat masala.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Samosa Chat', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bhel Puri</div>
            <div class="item-desc">Puffed rice tossed with diced onions, tomatoes, potatoes, green chilies, sev, and chutneys. A Mumbai beach classic.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bhel Puri', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Papadi Chat</div>
            <div class="item-desc">Crispy flat wheat crackers topped with chickpeas, potatoes, yogurt, tamarind chutney, and a sprinkle of chaat masala and sev.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Papadi Chat', 9.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Dahi Batata Puri</div>
            <div class="item-desc">Crispy puris filled with spiced potatoes and chickpeas, smothered in cool yogurt, sweet tamarind chutney, and spicy green chutney.</div>
            <div class="item-price">$9.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Dahi Batata Puri', 9.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- UDIPI CHINESE -->
    <div class="category section-alt">
      <div class="category-header">Udipi Chinese</div>
      <div class="category-subtitle">No Gluten Free</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Gobi Manchurian (Dry)</div>
            <div class="item-desc">Fresh Cauliflower Florets Cooked with Chef Special Homemade Indo-Chinese Sauce.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Gobi Manchurian (Dry)', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Gobi Manchurian (Gravy)</div>
            <div class="item-desc">Fresh Cauliflower Florets Cooked with Chef Special Indo-Chinese Sauce. Served with Rice.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Gobi Manchurian (Gravy)', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chili Paneer (Dry) <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Homemade Paneer Cooked with Chef Special Indo-Chinese Sauce.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chili Paneer (Dry)', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chili Paneer (Gravy) <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Homemade Paneer Cooked with Chef Special Indo-Chinese Sauce. Served with Rice.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chili Paneer (Gravy)', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Fried Rice</div>
            <div class="item-desc">Wok-tossed basmati rice with fresh vegetables and Indo-Chinese seasonings.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Fried Rice', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Hakka Noodles</div>
            <div class="item-desc">Stir-fried noodles with fresh vegetables and Indo-Chinese sauces. Bold, savory, and satisfying.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Hakka Noodles', 14.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- DOSA -->
    <div class="category">
      <div class="category-header">Dosa</div>
      <div class="category-subtitle">Thin rice crepes served with Sambhar &amp; Coconut Chutney. Gluten free choices available.</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sada Dosa</div>
            <div class="item-desc">Authentic South Indian Thin Rice Crepe.</div>
            <div class="item-price">$10.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sada Dosa', 10.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Satt Dosa</div>
            <div class="item-desc">Traditional South Indian Homemade Dosa (2 pcs).</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Satt Dosa', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Masala Dosa</div>
            <div class="item-desc">Rice Crepe Filled with Potatoes &amp; Onion.</div>
            <div class="item-price">$11.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Masala Dosa', 11.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Butter Sada Dosa <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Rice Crepe Cooked with Butter.</div>
            <div class="item-price">$12.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Butter Sada Dosa', 12.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Butter Masala Dosa <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Rice Crepe Filled with Potatoes/Onion &amp; Cooked with Butter.</div>
            <div class="item-price">$13.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Butter Masala Dosa', 13.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mysore Sada Dosa</div>
            <div class="item-desc">Rice Crepe with a Layer of Spicy Mysore Chutney.</div>
            <div class="item-price">$12.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mysore Sada Dosa', 12.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mysore Masala Dosa</div>
            <div class="item-desc">Rice Crepe Filled with Potatoes &amp; Onion, Layer of Spicy Mysore Chutney.</div>
            <div class="item-price">$13.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mysore Masala Dosa', 13.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Onion Sada Dosa</div>
            <div class="item-desc">Rice Crepes Topped with Onions.</div>
            <div class="item-price">$12.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Onion Sada Dosa', 12.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Onion Masala Dosa</div>
            <div class="item-desc">Rice Crepe Filled with Potatoes &amp; Onion.</div>
            <div class="item-price">$13.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Onion Masala Dosa', 13.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paper Sada Dosa</div>
            <div class="item-desc">Crispy, Thin &amp; Long Rice Crepe.</div>
            <div class="item-price">$12.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paper Sada Dosa', 12.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paper Masala Dosa</div>
            <div class="item-desc">Crispy, Thin &amp; Long Rice Crepe Filled with Potatoes &amp; Onion.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paper Masala Dosa', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Sada Rava Dosa (Jain)</div>
            <div class="item-desc">Cream of Wheat &amp; Lentil Crepe.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Sada Rava Dosa (Jain)', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rava Dosa</div>
            <div class="item-desc">Cream of Wheat &amp; Lentil Crepe with Onion &amp; Chilies.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rava Dosa', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rava Masala Dosa</div>
            <div class="item-desc">Cream of Wheat &amp; Lentil Crepe Filled with Potatoes, Onion &amp; Chilies.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rava Masala Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Spring Dosa</div>
            <div class="item-desc">Thin Rice Crepe Filled with Minced Vegetables &amp; Potatoes.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Spring Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Spicy Andhra Sada Dosa</div>
            <div class="item-desc">Rice Crepe with a Layer of Spicy Andhra Chutney.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Spicy Andhra Sada Dosa', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Spicy Andhra Masala Dosa</div>
            <div class="item-desc">Rice Crepe with a Layer of Spicy Andhra Chutney &amp; Filled with Potatoes &amp; Onion.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Spicy Andhra Masala Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bhajji Dosa</div>
            <div class="item-desc">Rice Crepe Filled with Delicious Cooked Minced Vegetables.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bhajji Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Spicy Andhra Spring Dosa</div>
            <div class="item-desc">Thin Rice Crepe Filled with Minced Vegetables, Potatoes &amp; Spicy Andhra Chutney.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Spicy Andhra Spring Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paneer Dosa <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Rice Crepe Filled with Homemade Cottage Cheese Cooked with Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paneer Dosa', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Cheese Dosa <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Rice Crepe Filled with Mozzarella Cheese.</div>
            <div class="item-price">$12.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Cheese Dosa', 12.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- UTHAPPAM -->
    <div class="category section-alt">
      <div class="category-header">Uthappam</div>
      <div class="category-subtitle">Rice &amp; Lentil Pancakes Served with Sambhar &amp; Chutney. All Vegan.</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Plain Uthappam</div>
            <div class="item-desc">Classic thick rice and lentil pancake, soft and wholesome with a slightly tangy fermented flavor.</div>
            <div class="item-price">$10.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Plain Uthappam', 10.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Coconut Uthappam</div>
            <div class="item-desc">Topped with Fresh Shredded Coconut.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Coconut Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Coconut Chilli Uthappam</div>
            <div class="item-desc">Topped with Fresh Shredded Coconut &amp; Chilies.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Coconut Chilli Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tomatoes &amp; Peas Uthappam</div>
            <div class="item-desc">Topped with Tomatoes &amp; Peas.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tomatoes & Peas Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tomatoes &amp; Onion Uthappam</div>
            <div class="item-desc">Topped with Tomatoes &amp; Onions.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tomatoes & Onion Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Onion &amp; Peas Uthappam</div>
            <div class="item-desc">Topped with Onions &amp; Peas.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Onion & Peas Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Onion &amp; Chili Uthappam</div>
            <div class="item-desc">Topped with Onions &amp; Chilies.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Onion & Chili Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Tomatoes, Chili &amp; Onion Uthappam</div>
            <div class="item-desc">Topped with Tomatoes, Chilies &amp; Onions.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Tomatoes, Chili & Onion Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Uthappam</div>
            <div class="item-desc">Topped with Tomatoes, Peas, Onions, Carrots &amp; Spicy Hot Chilies.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Uthappam', 13.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- INDIAN CURRIES -->
    <div class="category">
      <div class="category-header">Indian Curries</div>
      <div class="category-subtitle">Served with Rice, Raita &amp; Pickle (no substitutes). Vegan &amp; Gluten Free choices available.</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Avial <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Fresh Vegetables Cooked in Coconut Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Avial', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Curry</div>
            <div class="item-desc">Fresh Vegetables Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Curry', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Korma</div>
            <div class="item-desc">Fresh Vegetables Cooked in Coconut Milk with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Korma', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Vegetable Makhani <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Fresh Vegetables Cooked in Creamy Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Vegetable Makhani', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paneer Makhani <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Homemade Cheese Cooked in Tomato/Onion Cream Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$15.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paneer Makhani', 15.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chana Masala</div>
            <div class="item-desc">Chickpeas Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chana Masala', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Palak Paneer <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Spinach &amp; Cheese Cooked with Tomatoes &amp; Fresh Indian Spices.</div>
            <div class="item-price">$15.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Palak Paneer', 15.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Malai Kofta <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Cheese &amp; Minced Vegetable Dumplings Cooked in Creamy Sauce.</div>
            <div class="item-price">$15.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Malai Kofta', 15.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Matar Paneer <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Green Peas &amp; Homemade Cheese Cooked with Onions &amp; Fresh Indian Spices.</div>
            <div class="item-price">$15.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Matar Paneer', 15.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bhindi Masala</div>
            <div class="item-desc">Tender Fresh Okra Cooked with Herbs &amp; Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bhindi Masala', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Aloo Matar</div>
            <div class="item-desc">Potatoes &amp; Green Peas Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Aloo Matar', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Aloo Palak</div>
            <div class="item-desc">Potatoes &amp; Spinach Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Aloo Palak', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Aloo Gobi</div>
            <div class="item-desc">Potatoes &amp; Cauliflower Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Aloo Gobi', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chana Palak</div>
            <div class="item-desc">Chickpeas &amp; Spinach Cooked in Tomato Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chana Palak', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Baigan Ka Bharta</div>
            <div class="item-desc">Mashed Eggplant Cooked with Tomatoes, Onion &amp; Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Baigan Ka Bharta', 14.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paneer Tikka Masala <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Homemade Cheese Cooked in Tomato &amp; Onion Sauce with Fresh Indian Spices.</div>
            <div class="item-price">$15.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paneer Tikka Masala', 15.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Dal Tadka</div>
            <div class="item-desc">Yellow Lentil Cooked with Tomato &amp; Fresh Indian Spices.</div>
            <div class="item-price">$13.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Dal Tadka', 13.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Dal Makhani <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Black Lentil Cooked with Tomato &amp; Fresh Indian Spices.</div>
            <div class="item-price">$14.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Dal Makhani', 14.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- INDIAN BREADS -->
    <div class="category section-alt">
      <div class="category-header">Indian Breads</div>
      <div class="category-subtitle">Not served with any side dishes. Not Gluten Free.</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Paratha</div>
            <div class="item-desc">Multi Layer Whole Wheat Bread.</div>
            <div class="item-price">$5.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Paratha', 5.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Chapati (2 pcs)</div>
            <div class="item-desc">Thin Whole Wheat Bread.</div>
            <div class="item-price">$3.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Chapati (2)', 3.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Poori (2 pcs)</div>
            <div class="item-desc">Whole Wheat Puffy Bread Deep Fried.</div>
            <div class="item-price">$3.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Poori (2)', 3.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Bhatura</div>
            <div class="item-desc">Large Puffy Bread Deep Fried.</div>
            <div class="item-price">$5.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Bhatura', 5.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Butter Naan</div>
            <div class="item-desc">Soft leavened flatbread baked in a tandoor oven, finished with butter.</div>
            <div class="item-price">$4.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Butter Naan', 4.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Garlic Naan</div>
            <div class="item-desc">Tandoor-baked naan topped with minced garlic, fresh cilantro, and butter.</div>
            <div class="item-price">$4.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Garlic Naan', 4.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Aloo Paratha</div>
            <div class="item-desc">Whole Wheat Stuffed with Potatoes &amp; Spices.</div>
            <div class="item-price">$7.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Aloo Paratha', 7.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- CONDIMENTS -->
    <div class="category">
      <div class="category-header">Condiments</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Milagai Podi</div>
            <div class="item-desc">Mixture of Spicy Grained Ingredients (gun powder).</div>
            <div class="item-price">$2.00</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Milagai Podi', 2.00)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Pachadi Raita <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Yogurt Mixed with Cucumber, Tomato, Carrots, Cilantro &amp; Indian Spices.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Pachadi Raita', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Papadam (5)</div>
            <div class="item-desc">Thin, Crisp Indian Cracker.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Papadam (5)', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Yogurt <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Fresh, thick, mildly tangy plain yogurt.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Yogurt', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Basmati Rice</div>
            <div class="item-desc">Plain steamed basmati rice.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Basmati Rice', 2.99)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- DRINKS -->
    <div class="category section-alt">
      <div class="category-header">Drinks</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mango Milk Shake <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Creamy blended mango milkshake made with fresh mango and milk.</div>
            <div class="item-price">$3.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mango Milk Shake', 3.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rose Milk <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Chilled milk sweetened with rose syrup. Fragrant, cooling, and refreshing.</div>
            <div class="item-price">$3.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rose Milk', 3.50)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mango Lassi <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Thick, blended yogurt drink with sweet mango. Creamy, tropical, and cooling.</div>
            <div class="item-price">$3.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mango Lassi', 3.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Lassi (Sweet / Salt) <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Traditional blended yogurt drink available sweet or salted. Smooth and refreshing.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Lassi', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Butter Milk <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Thin, spiced yogurt drink with cumin, curry leaves, and green chili. Light and digestive.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Butter Milk', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mango Juice</div>
            <div class="item-desc">Sweet, tropical mango juice. Chilled and refreshing.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mango Juice', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Mysore Coffee <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Strong South Indian filter coffee made with chicory, served with steamed milk. Rich and aromatic.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Mysore Coffee', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Masala Chai <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Spiced Indian tea brewed with ginger, cardamom, cinnamon, and cloves in milk. Warming and fragrant.</div>
            <div class="item-price">$2.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Masala Chai', 2.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Soda &amp; Bottle Water</div>
            <div class="item-desc">Assorted sodas or chilled bottled water.</div>
            <div class="item-price">$2.75</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Soda & Bottle Water', 2.75)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

    <!-- DESSERTS -->
    <div class="category">
      <div class="category-header">Desserts</div>
      <div class="category-items">

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Rasmalai (2) <small style="color:#888;font-size:0.8rem;">no Vegan / no Gluten free</small></div>
            <div class="item-desc">Homemade Cottage Cheese in Condensed Milk, Garnished with Pistachio.</div>
            <div class="item-price">$4.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Rasmalai (2)', 4.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Gulab Jamun (2) <small style="color:#888;font-size:0.8rem;">no Gluten free</small></div>
            <div class="item-desc">Dry Milk &amp; Cottage Cheese Balls, Deep Fried &amp; Soaked in Saffron &amp; Honey Syrup.</div>
            <div class="item-price">$4.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Gulab Jamun (2)', 4.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Payasam <small style="color:#888;font-size:0.8rem;">no Vegan / no Gluten free</small></div>
            <div class="item-desc">Fine Vermicelli Noodle Cooked in Milk with Raisins, Cashews &amp; Saffron.</div>
            <div class="item-price">$4.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Payasam', 4.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Carrot Halwa <small style="color:#888;font-size:0.8rem;">no Vegan</small></div>
            <div class="item-desc">Grated Carrots Cooked in Butter &amp; Cream.</div>
            <div class="item-price">$4.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Carrot Halwa', 4.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Ice Cream</div>
            <div class="item-desc">Rose, Mango, Vanilla &amp; Kesar Pista.</div>
            <div class="item-price">$4.99</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Ice Cream', 4.99)" type="button">Add to Cart</button></div>
        </div>

        <div class="menu-item">
          <div class="item-details">
            <div class="item-name">Falooda <small style="color:#888;font-size:0.8rem;">no Vegan / no Gluten free</small></div>
            <div class="item-desc">Cooked Vermicelli &amp; Basil Seeds Mixed with Condensed Milk (Rabdi), Topped with Rose Ice Cream, Garnished with Rose Syrup.</div>
            <div class="item-price">$7.50</div>
          </div>
          <div class="item-action"><button class="btn btn-add" onclick="addToCart('Falooda', 7.50)" type="button">Add to Cart</button></div>
        </div>

      </div>
    </div>

  </main>

  </div>

<div class="cart-overlay no-print" id="cartOverlay" onclick="toggleCart(false)"></div>
<aside class="cart-drawer no-print" id="cartDrawer">
  <div class="cart-sidebar">
    <div class="cart-drawer-header">
      <h2>Your Order</h2>
      <button class="cart-drawer-close" onclick="toggleCart(false)" type="button">&times;</button>
    </div>
    <div class="employee-note">Need a specific request? Please see an employee!</div>
    <div class="table-number-section">
      <label class="table-number-label">TABLE NUMBER</label>
      <input class="table-number-input" id="tableNumberInput" placeholder="Enter Table #" type="text">
    </div>
    <div class="party-size-section">
      <label class="party-size-label">NUMBER OF GUESTS AT TABLE</label>
      <input class="party-size-input" id="partySizeInput" placeholder="Enter # of guests" type="number" min="1" oninput="updateCart()">
      <div class="gratuity-note" id="gratuityNote" style="display:none;">Parties of 5+ include an automatic 15% gratuity</div>
    </div>
    <div id="cartEmptyMessage" class="cart-empty">Your cart is empty</div>
    <div id="cartItemsContainer" class="cart-items"></div>

    <div class="cart-total">
      <div class="total-row"><span>Subtotal:</span><span>$<span id="cartSubtotal">0.00</span></span></div>
      <div class="total-row"><span>Tax (7%):</span><span>$<span id="cartTax">0.00</span></span></div>
      <div class="total-row" id="gratuityRow" style="display:none;"><span>Gratuity (15%):</span><span>$<span id="cartGratuity">0.00</span></span></div>
      <div class="total-row-final"><span>Total:</span><span>$<span id="cartTotal">0.00</span></span></div>
    </div>

    <div class="cart-sidebar-actions">
      <button class="btn btn-print" onclick="printOrder()" type="button">Print Order (2 Copies)</button>
      <button class="btn btn-empty" onclick="emptyCart()" type="button">Empty Cart</button>
    </div>
  </div>
</aside>

<div id="receipt-content"></div>

<script>
let cart = [];

function toggleCart(open) {
  document.getElementById('cartDrawer').classList.toggle('open', open);
  document.getElementById('cartOverlay').classList.toggle('open', open);
}

function addToCart(name, price) {
  const existing = cart.find(i => i.name === name);
  if (existing) { existing.quantity++; }
  else { cart.push({ name, price, quantity: 1, spice: '', masalaOnSide: false }); }
  updateCart();
  // Brief "added" flash on the button without opening the drawer every time
  flashAdded(name);
}

function flashAdded(name) {
  // find the button that just added this item and briefly show "Added!"
  const btns = document.querySelectorAll('.btn-add');
  btns.forEach(btn => {
    if (btn.getAttribute('onclick') && btn.getAttribute('onclick').includes("'" + name.replace(/'/g, "\\'") + "'")) {
      const orig = btn.textContent;
      btn.textContent = '✓ Added!';
      btn.style.background = '#2e7d32';
      setTimeout(() => { btn.textContent = orig; btn.style.background = ''; }, 900);
    }
  });
}

function updateQuantity(name, amount) {
  const item = cart.find(i => i.name === name);
  if (item) {
    item.quantity += amount;
    if (item.quantity <= 0) cart = cart.filter(i => i.name !== name);
  }
  updateCart();
}

function setSpice(name, level) {
  const item = cart.find(i => i.name === name);
  if (item) item.spice = (item.spice === level) ? '' : level;
  updateCart();
}

function toggleMasalaOnSide(name) {
  const item = cart.find(i => i.name === name);
  if (item) item.masalaOnSide = !item.masalaOnSide;
  updateCart();
}

function isMasalaDosa(name) {
  return /masala/i.test(name) && /dosa/i.test(name);
}

function emptyCart() { cart = []; updateCart(); }

function getPartySize() {
  const val = parseInt(document.getElementById('partySizeInput').value, 10);
  return isNaN(val) || val < 1 ? 0 : val;
}

function updateCart() {
  const totalItems = cart.reduce((s, i) => s + i.quantity, 0);
  const subtotal = cart.reduce((s, i) => s + i.price * i.quantity, 0);
  const tax = subtotal * 0.07;
  const partySize = getPartySize();
  const gratuityApplies = partySize >= 5;
  const gratuity = gratuityApplies ? subtotal * 0.15 : 0;
  const total = subtotal + tax + gratuity;

  document.getElementById('cartCount').textContent = totalItems;
  // price badge removed
  document.getElementById('cartSubtotal').textContent = subtotal.toFixed(2);
  document.getElementById('cartTax').textContent = tax.toFixed(2);
  document.getElementById('cartTotal').textContent = total.toFixed(2);

  const gratuityRow = document.getElementById('gratuityRow');
  const gratuityNote = document.getElementById('gratuityNote');
  if (gratuityApplies) {
    gratuityRow.style.display = 'flex';
    gratuityNote.style.display = 'block';
    document.getElementById('cartGratuity').textContent = gratuity.toFixed(2);
  } else {
    gratuityRow.style.display = 'none';
    gratuityNote.style.display = 'none';
  }

  const container = document.getElementById('cartItemsContainer');
  const emptyMsg = document.getElementById('cartEmptyMessage');

  if (cart.length === 0) { emptyMsg.style.display = 'block'; container.innerHTML = ''; return; }
  emptyMsg.style.display = 'none';
  const spiceLevels = ['Mild', 'Medium', 'Super Spicy'];
  container.innerHTML = cart.map(item => `
    <div class="cart-item">
      <div class="cart-item-header">
        <span class="cart-item-name">${item.name}</span>
        <span class="cart-item-price">$${(item.price * item.quantity).toFixed(2)}</span>
      </div>
      <div class="cart-item-controls">
        <div class="qty-controls">
          <button class="qty-btn" onclick="updateQuantity('${item.name}', -1)">-</button>
          <span class="qty-display">${item.quantity}</span>
          <button class="qty-btn" onclick="updateQuantity('${item.name}', 1)">+</button>
        </div>
        <button class="btn-remove" onclick="updateQuantity('${item.name}', -${item.quantity})">Remove</button>
      </div>
      <div class="spice-section">
        <label class="spice-label">Spice Level</label>
        <div class="spice-options">
          ${spiceLevels.map(level => `<button type="button" class="spice-btn${item.spice === level ? ' selected' : ''}" data-level="${level}" onclick="setSpice('${item.name}', '${level}')">${level}</button>`).join('')}
        </div>
      </div>
      ${isMasalaDosa(item.name) ? `
      <div class="masala-side-section">
        <button type="button" class="masala-side-btn${item.masalaOnSide ? ' selected' : ''}" onclick="toggleMasalaOnSide('${item.name}')">${item.masalaOnSide ? '✓ Masala On the Side' : 'Put Masala On the Side'}</button>
      </div>` : ''}
    </div>
  `).join('');
}

function buildReceiptHTML(tableNumber, label, partySize) {
  const subtotal = cart.reduce((s, i) => s + i.price * i.quantity, 0);
  const tax = subtotal * 0.07;
  const gratuityApplies = partySize >= 5;
  const gratuity = gratuityApplies ? subtotal * 0.15 : 0;
  const total = subtotal + tax + gratuity;
  const now = new Date();
  const dateStr = now.toLocaleDateString();
  const timeStr = now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' });

  let itemsHtml = '';
  cart.forEach(item => {
    itemsHtml += `<div class="receipt-item-row"><span class="receipt-item-name">${item.quantity}x ${item.name}</span><span>$${(item.price * item.quantity).toFixed(2)}</span></div>`;
    if (item.spice) itemsHtml += `<div class="receipt-item-detail">Spice Level: ${item.spice}</div>`;
    if (item.masalaOnSide) itemsHtml += `<div class="receipt-item-detail">Masala on the side</div>`;
  });

  return `
    <div class="single-receipt-copy">
      <div class="receipt-header">Serve Up Udipi Cafe</div>
      <div class="receipt-copy-label">${label}</div>
      <div class="receipt-info">100% Vegetarian Restaurant</div>
      <div class="receipt-table">TABLE ${tableNumber}</div>
      <div class="receipt-info">Date: ${dateStr} &nbsp;|&nbsp; Time: ${timeStr}${partySize > 0 ? ` &nbsp;|&nbsp; Guests: ${partySize}` : ''}</div>
      <hr class="receipt-divider">
      ${itemsHtml}
      <hr class="receipt-divider-solid">
      <div class="receipt-total-row"><span>Subtotal:</span><span>$${subtotal.toFixed(2)}</span></div>
      <div class="receipt-total-row"><span>Tax (7%):</span><span>$${tax.toFixed(2)}</span></div>
      ${gratuityApplies ? `<div class="receipt-total-row"><span>Gratuity (15%):</span><span>$${gratuity.toFixed(2)}</span></div>` : ''}
      <div class="receipt-total-row receipt-grand-total"><span>TOTAL:</span><span>$${total.toFixed(2)}</span></div>
      <hr class="receipt-divider">
      <div class="receipt-footer">Thank you for dining with us!</div>
      <div class="receipt-footer">Special requests? Please see an employee.</div>
    </div>`;
}

function printOrder() {
  if (cart.length === 0) { alert('Your cart is empty. Please add items before printing.'); return; }
  const tableInput = document.getElementById('tableNumberInput');
  const tableNumber = tableInput.value.trim();
  if (!tableNumber) { alert('Please enter your Table Number before printing.'); tableInput.focus(); return; }
  const partySize = getPartySize();
  const receiptDiv = document.getElementById('receipt-content');
  receiptDiv.innerHTML =
    `<div class="receipt-page-break">${buildReceiptHTML(tableNumber, 'Customer Copy', partySize)}</div>` +
    buildReceiptHTML(tableNumber, 'Kitchen Copy', partySize);
  window.print();
}

updateCart();
</script>
</body>
</html>
