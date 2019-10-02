<template>
  <div id="app">
    <x-greet />
    <x-greet name="Mark" />
    <x-counter />
    <take-object title="Favorites" :obj.prop={favorites} />
  </div>
</template>

<script>
import './web-components.js';

export default {
  name: 'app',
  data() {
    return {
      favorites: {color: 'yellow', number: 19}
    }
  }
}
</script>
