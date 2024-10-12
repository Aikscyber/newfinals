<template>
	<div id="resume">		
		<div id="objective">
			<p>
				{{ objective }}
			</p>
		</div>
	
		<dl>
			<dd class="clear"></dd>
			
			<dt>{{ education }}</dt>
			<dd>
				<h2>{{ elementary }}</h2>
				<p class="year"><strong>2008-2016</strong><br />
				<strong>CHRISTIAN FRIENSHIP LEARNING CENTER INC.</strong> </p>

				<h2>{{ highschool }}</h2>
				<p class="year"><strong>2016-2019</strong><br />
				<strong>SAPANG BATO NATIONAL HIGH SCHOOL</strong> </p>

				<h2>{{ seniorhighschool }}</h2>
				<p class="year"><strong>2019-2021</strong><br />
				<strong>SAPANG BATO SENIOR HIGH SCHOOL</strong> </p>

				<h2>{{ college }}</h2>
				<p class="year"><strong>2022-Present</strong><br />
				<strong>HOLY ANGEL UNIVERSITY</strong> </p>
			</dd>
			
			<dd class="clear"></dd>
			
			<dt>{{ skills }}</dt>
			<dd>
				<h2>{{ tSkills }}</h2>
				<p>Proficient in creating structured web pages using HTML and CSS</p>
				<p>Ability to add interactivity to websites using JavaScript</p>
				<p>Experience with popular frameworks Vue.js</p>
				<p>Knowledge of server-side technologies such as Node.js and PHP </p>
				
				<h2>{{ sSkills }}</h2>
				<p>Willingness to learn and adapt to new tools</p>
				<p>Ability to manage multiple tasks</p>
				<p>Precision in coding syntax errors and to ensure code readability and performance</p>
			</dd>
			<dd class="clear"></dd>
		</dl>
		<div class="clear"></div>
	</div>
</template>

<script>
export default {
  name: 'Resume',
  data () {
    return {
		objective: 'I aim to apply my technical knowledge and problem-solving skills to contribute to innovative technology solutions. I aim to deepen my understanding of web development while gaining practical experience through collaborative projects. I aim to leverage my passion for technology to create efficient and scalable solutions.',
		education: 'Education',
		elementary: 'ELEMENTARY',
		highschool: 'HIGHSCHOOL',
		seniorhighschool: 'SENIOR HIGH SCHOOL',
		college: 'COLLEGE',
		skills: 'Skills',
		tSkills: 'Technical Skills',
		sSkills: 'Soft Skills'
    }
  }
}
</script>

<style>
* { 
	margin: 0; 
    padding: 0; 
}

body { 
    font: 16px Helvetica, Sans-Serif; 
    line-height: 24px;
	
}

.clear { 
	clear: both; 
}


#resume { 
	width: 800px; 
	margin: 40px auto 60px;
	text-align: left; 
}

#pic { 
	float: right; 
	margin: -30px 0 0 0; 
}

h1 { 
	margin: 0 0 16px 0; 
	padding: 0 0 16px 0; 
	font-size: 42px; 
	font-weight: bold; 
	letter-spacing: -2px; 
	border-bottom: 1px solid #999; 
}

.year {
	font-style: italic;
}

h2 { 
	font-size: 20px; 
	margin: 0 0 6px 0; 
	position: relative; 
	font-weight: bold;
}

h2 span { 
	position: absolute; 
	bottom: 0; 
	right: 0; 
	font-style: italic; 
	font-family: Georgia, Serif; 
	font-size: 16px; 
	color: #999; 
	font-weight: normal; 
}

p { 
	margin: 0 0 16px 0; 
}

a { 
	color: #999; 
	text-decoration: none; 
	border-bottom: 1px dotted #999; 
}

a:hover { 
	border-bottom-style: solid; 
	color: black; 
}

ul { 
	margin: 0 0 32px 17px; 
}

#objective { 
	width: 500px; 
	float: left; 
}

#objective p { 
	font-family: Georgia, Serif; 
	font-style: italic; 
	color: #666; 
}

dt { 
	font-style: italic; 
	font-weight: bold; 
	font-size: 18px; 
	text-align: right; 
	padding: 0 26px 0 0; 
	width: 150px; 
	float: left; 
	height: 100px; 
	border-right: 1px solid #999;  
}

dd { 
	width: 600px; 
	float: right; 
}

dd.clear { 
	float: none; 
	margin: 0; 
	height: 15px; 
}
</style>
