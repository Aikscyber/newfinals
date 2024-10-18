<template>
  <div id="about">
      <h1>About</h1>
      <p>{{ msg }}</p>
      <p>{{ msg1 }}</p>
  </div>
</template>

<script>
export default {
name: 'about',
data () {
  return {
    msg: 'Welcome to 4K Vape Shop, your go-to destination for premium disposable vapes! We are dedicated to providing a wide range of high-quality vaping products designed to offer an exceptional experience for both new and experienced vapers.',
    msg1: "At 4K Vape Shop, we believe in simplicity and convenience. Our flagship product, the 4K Disposable Vape, features a sleek design, a powerful 550mAh rechargeable battery, and a capacity of 8ml of premium e-liquid. Each device delivers up to 4000 puffs, making it perfect for on-the-go use."
  }
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#about {
  background-color: #eaeaea;
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
  margin-bottom: 15px;
}

p {
  font-size: 1.1em;
  color: #444;
  line-height: 1.6;
  margin-top: 10px;
}
</style>
