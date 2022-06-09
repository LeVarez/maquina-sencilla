<script lang="ts">
  export let busBits: number;
  export let input: string = '';
  export let output: string = '';

  export let orientation: Orientation = 'horizontal';

  type Orientation = 'horizontal' | 'vertical';
</script>

<div class="register-container">

</div>

<style lang="scss">
  .register-container {
    width: 50px;
    height: 300px;
    background-color: rgb(224, 211, 165);
    font-weight: bold;
  }
</style>