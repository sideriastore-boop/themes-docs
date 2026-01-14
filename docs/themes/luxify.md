---
sidebar_position: 3
---

# Luxify

## Home page

### Home Slider

```css title="Home Slider"
.home_slider_slide {
}

.home_slider_card {
}
```

![Home Slider Container](./luxify-assets/home_slider.png)

### Home section title

```css
.home_section_top_container {
}

.home_section_top_title {
}
```

![Home Section Top](./luxify-assets/home_section_top.png)

### Category Card

```css
.luxify_category_card {
}

.luxify_category_card_img {
}

.luxify_category_card_name {
}
```

![Category Card](./luxify-assets/luxify_category_card.png)

### Featured Card

```css
.luxify_product_featured_container {
}

.luxify_product_featured_category_card {
}

.luxify_product_featured_card {
}

.luxify_product_featured_card_img {
}
```

![Featured Card](./luxify-assets/luxify_product_featured.png)

### Home product carousel

```css
.home_products_carousel_card {
}
```

![Home Product Carousel](./luxify-assets/home_products_carousel.png)

### Home products grid

```css
.home_products_grid_container {
}

.home_products_grid_card {
}
```

![Home Products Grid](./luxify-assets/home_products_grid.png)

### Home banner

```css
.home_banner {
}

.home_banner_img {
}
```

![Home Banner](./luxify-assets/home_banner.png)

## Product page

### Product name

```css
.product_name {
}
```

### Product price

```css
.product_price_container {
}

.product_price {
}
```

![Product Price](./luxify-assets/product_price.png)

### Product description

```css
.product_description {
}
```

### Product image

```css
.luxify_product_active_img {
}

.luxify_product_images_grid {
}

.luxify_product_images_grid_img {
}
```

![Product Image](./luxify-assets/product_images.png)

### Product form checkout

```css
.product_form_checkout {
}
```

![Form](./luxify-assets/product_form_checkout.png)

### Total shipping cost

```css
.total_shipping_container {
}

.total_shipping {
}
```

![Total Shipping](./luxify-assets/shipping_cost.png)

### Total price

```css
.total_price_container {
}

.total_price {
}
```

![Total Price](./luxify-assets/total_price.png)

### Fake Stock

```css
.fake_stock_container {
}

.fake_stock_progress {
}

.fake_stock_count {
}
```

![Fake Stock](./luxify-assets/fake_stock.png)

### Fake visitors

```css
.fake_visitors_container {
}
```

![Fake Visitors](./luxify-assets/fake_visitors.png)

### Products grid

```css
.products_grid_container {
}

.products_grid_card {
}
```

![Product Page Products Grid](./luxify-assets/products_grid.png)

### Product reviews

```css
.reviews_summary {
}

.user_review_content {
}

.user_review_name {
}

.user_review_comment {
}

.user_review_img {
}
```

![Product Reviews](./luxify-assets/product_reviews.png)

## Inputs, textarea

```css
.global_input {
}

.global_textarea {
}

.gov_select {
}
```

![Inputs](./luxify-assets/inputs.png)

## Buttons

### Checkout button and add to cart button

```css
.checkout_btn {
}

.add_to_cart_btn {
}
```
<div class="purchase-buttons">
  <button class="checkout_btn">إتمام الشراء</button>
  <button class="add_to_cart_btn">أضف للسلة</button>

  <!-- payment note -->
  <div class="payment-note">
    <div class="note-row">
      <span class="icon">
        <!-- أيقونة الشحن -->
        <svg viewBox="0 0 1024 1024" xmlns="http://www.w3.org/2000/svg">
          <path d="M128.896 736H96a32 32 0 0 1-32-32V224a32 32 0 0 1 32-32h576a32 32 0 0 1 32 32v96h164.544a32 32 0 0 1 31.616 27.136l54.144 352A32 32 0 0 1 922.688 736h-91.52a144 144 0 1 1-286.272 0H415.104a144 144 0 1 1-286.272 0z"/>
        </svg>
      </span>
      <p>
        رسوم الشحن تُحسب عند الدفع.<br>
        التسليم المُقدّر في خلال 1–4 أيام عمل.
      </p>
    </div>

    <div class="note-row">
      <span class="icon">
        <!-- أيقونة الدفع -->
        <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path opacity="0.1" d="M3 10V15C3 16.8856 3 17.8284 3.58579 18.4142C4.17157 19 5.11438 19 7 19L17 19C18.8856 19 19.8284 19 20.4142 18.4142C21 17.8284 21 16.8856 21 15V10H3Z"/>
          <path d="M3.5 10H20.5" stroke-width="2" stroke-linecap="round"/>
          <path d="M6 14H8" stroke-width="2" stroke-linecap="round"/>
          <path d="M11 14H13" stroke-width="2" stroke-linecap="round"/>
          <path d="M3 9C3 7.11438 3 6.17157 3.58579 5.58579C4.17157 5 5.11438 5 7 5H17C18.8856 5 19.8284 5 20.4142 5.58579C21 6.17157 21 7.11438 21 9V15C21 16.8856 21 17.8284 20.4142 18.4142C19.8284 19 18.8856 19 17 19H7C5.11438 19 4.17157 19 3.58579 18.4142C3 17.8284 3 16.8856 3 15V9Z"
                stroke-width="2" stroke-linejoin="round"/>
        </svg>
      </span>
      <p>الدفع نقدًا عند الاستلام</p>
    </div>
  </div>
</div>
.payment-note {
  direction: rtl;
  font-size: 14px;
  color: #374151;
  border-top: 1px solid #e5e7eb;
  padding-top: 10px;
  margin-top: 10px;
}

.note-row {
  display: flex;
  gap: 8px;
  margin-bottom: 6px;
}

.note-row .icon {
  width: 18px;
  height: 18px;
  flex-shrink: 0;
  margin-top: 2px;
}

.note-row svg {
  width: 100%;
  height: 100%;
  stroke: #374151;
  fill: none;
}

![Checkout Button](./luxify-assets/button.png)

### Form button

```css
.form_checkout_btn {
}
```

![Form Button](./luxify-assets/form_button.png)

### Quantity button

```css
.quantity_container {
}

.quantity_btn {
}
```

![Quantity Button](./luxify-assets/quantity_btn.png)

## Category page

### Category section header

```css
.category_section_header {
}

.category_section_header_title {
}
```

![Category Section Header](./luxify-assets/category_section_header.png)

### Category products grid

```css
.category_products_grid_container {
}

.category_products_grid_card {
}
```

![Category Products Grid](./luxify-assets/category_products_grid.png)

## Global

### Header

```css
.luxify_header {
}
```

![Luxify Header](./luxify-assets/luxify_header.png)

```css
.luxify_header_container {
}
```

![Luxify Header Container](./luxify-assets/luxify_header_container.png)

```css
.luxify_top_header {
}
```

![Luxify Top Header](./luxify-assets/luxify_top_header.png)

```css
.luxify_header_logo {
}
```

![Luxify Header Logo](./luxify-assets/luxify_header_logo.png)

```css
.luxify_bottom_text {
}
```

![Luxify Bottom Text](./luxify-assets/luxify_bottom_text.png)

### Footer

```css
.luxify_footer {
}

.luxify_footer_links_container {
}

.luxify_footer_link {
}

.luxify_footer_social_container {
}

.luxify_footer_social_link {
}

.footer_store_info {
}
```

![Footer](./luxify-assets/footer.png)

### Slider

:::info
The following classes are used for the global slider component so every slider in the theme will have the same style.
:::

```css
.swiper-pagination {
}

.swiper-pagination-bullet {
}

.swiper-pagination-bullet-active {
}

.slider_buttons_container {
}

.slider_button {
}
```

![Slider](./luxify-assets/global_slider.png)
![slider-pagination](./luxify-assets/slider_pagination.png)

### Payments

```css
.payments_container {
}

.payment_card {
}

.radio_container {
}

.radio_circle {
}

.payment_card_content {
}

.payment_card_name {
}

.payment_card_description {
}

.payment_card_img {
}
```

![Payments](./luxify-assets/payments.png)

## Thanks page

```css
.thanks_content {
}

.thanks_container {
}

.order_invoice_container {
}
```

![Thanks Page](./luxify-assets/thanks_page.png)

## Checkout page

```css
.checkout_bg_right {
}

.checkout_bg_left {
}

.checkout_container {
}

.checkout_order_summary {
}

.checkout_cart_items_container {
}

.checkout_form {
}

.checkout_buy_now {
}
```

![Checkout Page](./luxify-assets/checkout.png)
