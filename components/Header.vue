<template>
  <header id="header">
    <div class="wrapper d-flex align-items-center justify-content-between">
      <div class="header-left">
        <NuxtLink to="/" id="site-logo">Logo</NuxtLink>
      </div>
      <div class="header-right">
        <nav>
          <ul>
            <li>
              <NuxtLink to="/about">About</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/services">Services</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/locations">Locations</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/contact">Contact</NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
