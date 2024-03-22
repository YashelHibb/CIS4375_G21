<template>
  <header class="u-clearfix u-header u-palette-5-light-2 u-header" id="sec-8229">
      <div class="u-align-left u-clearfix u-sheet u-sheet-1">
          <h3 class="u-headline u-text u-text-1">Classic Nails</h3>
          <nav class="u-menu u-menu-one-level u-offcanvas u-menu-1" data-responsive-from="MD">
            <div class="u-custom-menu u-nav-container">
                <ul class="u-nav u-spacing-2 u-unstyled u-nav-1">
                    <li class="u-nav-item">
                        <router-link :class="{ 'u-active-palette-4-base': $route.path === '/', 'u-border-active-palette-1-base u-border-hover-palette-1-light-1 u-border-no-left u-border-no-right u-border-no-top u-button-style u-hover-palette-4-base u-nav-link u-text-active-grey-90 u-text-grey-90 u-text-hover-grey-90': true }" to="/" style="padding: 10px 20px;">Home</router-link>
                    </li>
                    <li class="u-nav-item">
                        <router-link :class="{ 'u-active-palette-4-base': $route.path === '/services', 'u-border-active-palette-1-base u-border-hover-palette-1-light-1 u-border-no-left u-border-no-right u-border-no-top u-button-style u-hover-palette-4-base u-nav-link u-text-active-grey-90 u-text-grey-90 u-text-hover-grey-90': true }" to="/services" style="padding: 10px 20px;">Services</router-link>
                    </li>
                    <li class="u-nav-item"> 
                        <router-link :class="{ 'u-active-palette-4-base': $route.path === '/login', 'u-border-active-palette-1-base u-border-hover-palette-1-light-1 u-border-no-left u-border-no-right u-border-no-top u-button-style u-hover-palette-4-base u-nav-link u-text-active-grey-90 u-text-grey-90 u-text-hover-grey-90': true }" to="/login" style="padding: 10px 20px;">Login</router-link> 
                    </li>
                </ul>
            </div>
          </nav>
      </div>
  </header>
</template>

<style>
.u-active-palette-4-base {
     color: #111111 !important;
     background-color: #f4e1cb !important;
}
</style>
