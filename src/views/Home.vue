<template>
  <div class="grid-container">
    <Header />
    <Nav />
    <Customers />
  </div>
</template>

<script>
import Header from '@/components/Header';
import Nav from '@/components/Nav';
import Customers from '@/components/Customers';

export default {
  name: 'Home',
  components: {
    Header,
    Nav,
    Customers
  }
}
</script>
