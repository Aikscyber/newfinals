<template>
  <div id="contact">
    <h1>{{ msg }}</h1>
      <h2>Get in Touch</h2>
      <p>If you have any questions or comments, feel free to reach out to us!</p>
      <h3>Questions? Comments? Contact Us! Call Us</h3>
      <p>0936 865 8780</p>
      <h3>Email Us</h3>
      <p><a href="mailto:kristelsagun12@gmail.com">kristelsagun12@gmail.com</a></p>
      <p><a href="https://www.facebook.com/profile.php?id=61559604674470">Facebook</a></p>
  </div>
</template>

<script>
export default {
name: 'contact',
data () {
  return {
    msg: 'CONTACT'
  }
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#contact {
  background-color: #f9f9f9;
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

h2, h3 {
  color: #444;
  margin-top: 20px;
}

p {
  font-size: 1.1em;
  color: #555;
  line-height: 1.5;
  margin-top: 10px;
}

a {
  color: #007bff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
