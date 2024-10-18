<template>
   <div id="home">
    <h1>Home</h1>
    <p>
      Welcome to 4K Vape Shop!

      {{ msg }}
    </p>
   </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'At 4K Vape Shop, we offer a wide range of high-quality disposable vapes designed to provide an exceptional vaping experience. Our top-selling product, the 4K Disposable Vape, features a sleek design, a powerful 550mAh rechargeable battery, and a capacity of 8ml of premium e-liquid. Each device delivers up to 4000 puffs, making it perfect for both new and experienced vapers .style of its community, and prides itself on its customer-centric service. Experience life beyond the ordinary here at Tower Ground Inc.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#home {
  background-color: #f4f4f4;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  max-width: 600px;
  margin: 20px auto;
}

h1 {
  font-size: 2.5em;
  color: #333;
  text-align: center;
}

p {
  font-size: 1.2em;
  color: #555;
  line-height: 1.5;
  margin-top: 15px;
}
</style>
