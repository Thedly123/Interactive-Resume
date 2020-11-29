<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="utf-8">

  <title>Map Test 2</title>
  <meta name="description" content="The HTML5 Herald">
<script src='https://kit.fontawesome.com/a076d05399.js'></script>

 <style>
 	body{
 		color: #ddd;
 		background-color: #000012; 
 	}
 	#main-wrapper{

 		color: #eee;
 		height: 400px;
 		width: 90%;
 		margin: auto;
 		padding: 0;
 		columns: white;

 	}
 	#landing{
 		height: 800px;
 		padding: 20%;
 	}
 	#profile{
 		border-radius: 9px;
 		font-size: 1em;
 		color:black;
 		height: 600px;
 		padding: 3%;
 		background-color: white;
 		margin-bottom: 10%;
 	}
 	#pro-pic{
 		background-image: url(https://media-exp1.licdn.com/dms/image/C4D03AQEEHIl22lGmlg/profile-displayphoto-shrink_200_200/0?e=1611792000&v=beta&t=XwlvzW0MYDtM3Jgm1-DxE7vDc_4Fowt2IRx7V9TQXoA);

 	}
 	#education,#content{
 		height: 1000px;
 		color: #444;
 		padding: 5%;
 		background-color: #F8F8FF;
 		border-radius: 20px;
 		border: 20px solid white;
 		margin-bottom: 100px;
 		overflow: hidden;

 	}
 	img {
 		width: 300px;
 		height: 200px;
  		border-radius: 18px;
  		margin: auto;

		}
	#pro-spa{
		font-size: 3em;
		color:#00FFFF;
	}
	#pro-spa:hover{
		font-size: 2.8; 
		color:#FF7F50;
		/*#00aaaa;
		#FF7F50
		*/
	}
/*---------------------------------------------*/
#social-med{
	background-color: #ddd;
	height: 400px;
	margin-top: 100px;
	padding: 10px;
	border-radius: 9px;
}
#work{
	background-color: #444;
	height: 600px;
	padding: 20px;
	border-radius: 9px;
}
/*---------------------------------------------*/

 	td{
 		width: auto;
 		padding: 20px;
 	}
 </style>

</head>
<!-------------------------------------------------|  Body   |--------------------------------------------------------------->
<body>
	<div id="main-wrapper">
		<div id="landing">
			<div style="font-size: 2em;"> <span id="pro-spa" > Software Engineer </span><br>
				based in <span id="pro-spa" >North New Jersey, U.S.A.</span> <br>Focussed on <span id="pro-spa">interactive  Web developement.</span>
			</div>
		</div>
	<div id="profile"  >
		<h1 style="text-align: center; color: #5F9EA0;"> Profile</h1><br>
		<div style="float: left ; width: 35%; padding: 1%;padding-right: 50px;">
		    <span style="color: #5F9EA0; font-size: 1.5em;">About Me</span><br>	  
		    <p>
		    	I came from a third world country. I had virtually no access to computers. Being here in America and having
		    		access to computers allowed me to see the world with a computer bias. Many technologies taking for granted here, is heaven sent back home. I want to help decrease that gap however I can, whether by opening schools back home or possibly creating tutorial sessions in the native language.
		    	<br><br>
		    	Many users see the front of a computer and use the GUI (Graphical User Interfaces). The first time I used a computer. It fascinated me to know how it worked... the philosophy behind computers and the methods of how they work. Studying computers at NJIT (New Jersey Institute of Technology), has only left me hungrier. 
		    	<br><br>
		    	As of right now, I’m looking to land my first job/internship in software engineering. I hope to apply what I’ve learned from the foundation of computers to data structures and algorithm.  I familiar with programing languages' concepts, know some basic programing techniques, and have adequate problem skills.
				programing languages' concepts, know some basic programing techniques, and have adequate problem skills.
		    </p>
		</div>
		<div  id="pro-pic" style="border: 5px solid #000; height: 200px; width: 200px; border-radius: 50%; overflow: hidden; margin: auto; float: left">

			<img src="https://media-exp1.licdn.com/dms/image/C4D03AQEEHIl22lGmlg/profile-displayphoto-shrink_200_200/0?e=1611792000&v=beta&t=XwlvzW0MYDtM3Jgm1-DxE7vDc_4Fowt2IRx7V9TQXoA" style="width: 200px;">
		</div>
		<div style="float: left;width: 35%; padding: 1%; padding-left: 50px;">
			<span style="color: #5F9EA0; font-size: 1.5em;">Details </span><br>	 <br>
			<b>Name:</b><br>Thedly Toussaint<br><br>
			<b>Age: </b><br>26<br><br>
			<b>Location:</b><br>Irvington, New Jersey, United States of America<br><br>
			<div id="map">
				<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1eudjEnmBENwVCAjiSl1VLT8my_15BaJM" width="400" height="280"></iframe>
			</div>
		</div>
	</div>
<!----------------------------------------| Education |------------------------------>
	<div id="education">
	<tr><th>	<h1 style="color: #5F9EA0">Education</h1></th></tr>
			<table>
				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
							<span style="font-size: 1.3em;">New Jersey Institute of Technology</span>
					
							<img src="https://news.njit.edu/sites/news/files/styles/16by9-banner/public/2019MayCampusPhotos-21-2%20%282%29%20%281%29_1.jpg?itok=0MuWYRo3" alt="NJIT">
						</div>
						<date style="color: #5F9EA0">January 2017 - December 2020</date>
					</td>
					<td>
						<b>University- Programing Language Concepts</b>
						<p>
					 ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					 ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.						
					</p>
					
					<i class='fas fa-map' style='font-size:24px'></i>
					<a href="https://computing.njit.edu/">NJIT</a><br>
					<i class='fas fa-map-marker' style='font-size:24px'></i>
					<a href="https://www.google.com/maps/dir/40.7240704,-74.252288/new+jersey+institute+of+technology/@40.7365409,-74.2489865,13z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x89c2537d98c396f9:0xb97c287a2ef95f43!2m2!1d-74.1770884!2d40.7427996">Newark, NJ</a>

					</td>
				</tr>

				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
					<span style="font-size: 1.3em;">Essex County College</span><br>

					<img src="https://static01.nyt.com/images/2017/09/21/nyregion/21essex/21essex-superJumbo.jpg" alt="ECC">
				</div>
					<date style="color: #5F9EA0">September 2013 - December 2018</date>
					</td>
					<td>
						<b>Community College - Foundation of Computer Science</b>
						<p>
					 ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					 ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.						
					</p>
					<i class='fas fa-map' style='font-size:24px'></i>
					<a href="https://www.essex.edu/associate-in-science-in-computer-science/">Essex County College</a><br>
					<i class='fas fa-map-marker' style='font-size:24px'></i>
					<a href="https://www.google.com/maps/dir/40.7240704,-74.252288/essex+county+college/@40.7365409,-74.2491785,13z/data=!3m1!4b1!4m9!4m8!1m1!4e1!1m5!1m1!1s0x89c2537c680d44c1:0xd8e308bf36c11192!2m2!1d-74.178945!2d40.7383482">Newark, NJ</a>
					</td>
				</tr>

				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
					<span style="font-size: 1.3em;">Frank Morrel College </span><br> 
					<img src="https://www.nj.com/resizer/9dtUH1anhlEuu84V8EBprPCYzFs=/1280x0/smart/advancelocal-adapter-image-uploads.s3.amazonaws.com/image.nj.com/home/njo-media/width2048/img/ledgerupdates_impact/photo/2011/03/irvington-highjpg-3fb512f527ad2b41.jpg" alt="NJIT">
				</div>
					<date style="color: #5F9EA0">September 2009 - December 2013</date>
					</td>
					<td>
						<b>High School - Intro To Computers</b>
						<p>
					 I graduated highschool, where I enjoyed courses like literature, science, math, biology, and arts; as well as after-school-programs like soccer, bowling, and modeling. I realized in my third year that I had an interest in STEM, specifically Egineering, so I took a course on computers that thought me the concept of binary and hexidecimal numbers along with how to type properly. I eventually thought of heading to Essex County College to major in General Engineer. 
					</p>
					<i class='fas fa-map-marker' style='font-size:24px'></i>
					<a href="https://irvington.net">Irvington, NJ</a>

					</td>
				</tr>
			</table>

		</div>

<!----------------------------------------| Experience |------------------------------>
		<div id="content">
			<h1 style="color: #5F9EA0">Experience</h1>
			<table>
				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
							<span style="font-size: 1.3em;">Army National Guard</span><br>
					
							<img src="https://www.nj.gov/military/assets/images/njarnglogo.png"  style="width: 200px;" alt="NG/NJ">
						</div>
						<date style="color: #5F9EA0">November 2020 - Current</date>
					</td>
					<td>
						<b>25U - Signal Support Specialist</b>
						<p>
					 A Signal Support Systems Specialist maintains vital signal support systems and terminal devices; the equipment that needs to consistently work in order for commanders to stay informed, track, and direct the movement of their troops. Also performs signal support and technical assistance for computer systems, local area networks, and maintenance on equipment, terminal devices, power generators, and vehicles. 
					 <br>
					SKILLS  LEARNED<br>

					Electronic Troubleshooting<br>
					Circuits & Wiring<br>
					Radios & Networks					
					</p>
					<i class='fas fa-map' style='font-size:24px'></i>
					<a href="https://nationalguard.com/select-your-state/NJ?utm_campaign=ngpaidsearch3&utm_source=89&utm_medium=googlebrand&utm_content=web">NJ Army National Guard</a>

					</td>
				</tr>

				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
					<span style="font-size: 1.3em;">Wholefoods Market</span><br>

					<img src="https://upload.wikimedia.org/wikipedia/commons/a/a2/Whole_Foods_Market_201x_logo.svg" alt="ECC">
				</div>
					<date style="color: #5F9EA0">November 2017 - Current </date>
					</td>
					<td>
						<b>Customer Support - 'Boothie' </b>
						<p>
						As an all around Team Member for Whole Foods Store Support department, my objective entails selecting, training, developing, mentoring, motivating, and counselings Team Members in a manner that sustains a high-performance team and minimizes turnover, which demonstrates decision-making ability, leadership skills, and ability to prioritize and delegate.						
					</p>
					<i class='fas fa-map' style='font-size:24px'></i>
					<a href="https://www.wholefoodsmarket.com/?gclid=EAIaIQobChMIqof409mm7QIVvQeICR2dVweXEAAYASAAEgJ_6PD_BwE">
						Wholefoods.com
					</a><br>
					<i class='fas fa-map-marker' style='font-size:24px'></i>

					<a href="https://www.wholefoodsmarket.com/stores/madison">Rose City (Madison), NJ)</a>

					</td>
				</tr>

				<tr>
					<td>
						<div style="width: 400px; color:black; float: left;overflow: hidden;">
					<span style="font-size: 1.3em;">Heavenly Pilgrims Church </span><br> 
					<img src="https://blog.capterra.com/wp-content/uploads/2018/06/HEAD-Ideas_for_Youth_Ministry-_Tips_to_Promote_and_Sustain_Involvement_Hero_no_text.png" alt="NJIT">
				</div>
					<date style="color: #5F9EA0">September 2016 - December 2017</date>
					</td>
					<td>
						<b>Volunteer Work - Church Youth Sunday School Teacher </b>
						<p>			
					</p>
					<i class='fas fa-map-marker' style='font-size:24px'></i>
					<a href="https://irvington.k12.nj.us/">Irvington, NJ</a>

					</td>
				</tr>


			</table>

		</div>

		<div id="work">
			<div id="loc-par">
			<ul>
				<li><a href="">stuff</a></li>
				<li><a href="">stuff</a></li>
				<li><a href="">stuff</a></li>
				<li><a href="">stuff</a></li>
			</ul>
			</div>

		</div>

		<div id="social-med">
			<div>
				Social Media
			</div>
		</div>
		
	</div>


</body>
</html>
