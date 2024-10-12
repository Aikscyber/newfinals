<template>
	<div id="app">
		<div id="wrap">

			<img src="./assets/default_profile.jpg" alt="Photo of Aiko" id="pic" />

			<div id="contact-info" class="vcard">
	
				<h1 class="fn">{{ name }}</h1>
				
				<h3>{{ course }}</h3>
				<p>
					Cell: <span class="tel">{{ phone }}</span><br />
					Email: <a class="email" href="mailto:aikoocampo03@gmail.com">{{ email }}</a>
				</p>
			</div>
		</div>
    	<resume></resume>
	</div>
  	
</template>

<script>
import Resume from './components/Resume.vue';
export default {
  name: 'app',
  components: {
    Resume
  },
  data () {
    return {
		name: 'Aiko S. Ocampo',
		course: 'BSIT Web Development',
		phone: '09753962768',
		email: 'aikoocampo03@gmail.com'

    }
  }
}
</script>

<style>
* { 
	margin: 0; 
    padding: 0; 
}

#wrap { 
	width: 800px; 
	margin: 40px auto 60px; 
}

#pic { 
	float: right; 
	margin: -30px 0 0 0; 
}

img {
	width: 300px;
	height: 300px;
}

h1{ 
	margin: 0 0 16px 0; 
	padding: 0 0 16px 0; 
	font-size: 42px; 
	font-weight: bold; 
	letter-spacing: -2px; 
	border-bottom: 1px solid #999; 
}

h3 {
	font-weight: bold;
}
html{
	background-color: antiquewhite;
}
</style>
