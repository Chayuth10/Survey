<style>
body{background-color:#ff6699;}

.ContentBG
{
	display:table;
	position:relative;
	width: 75%;
	height: 100%;
	margin-left: auto;
    margin-right:auto; 
	background-color:white;
	
	
}

#container
{
	display:grid;
	grid-template-columns: 400px 400px;
	grid-template-rows: 100px;
	justify-content:center;
	margin:10px;
	grid-row-gap: 20px;
}

.showngrid
{

	border-style:solid; 
	border-color:black;
}

.surveyhead
{
	grid-area: 1 / 1 / 1 / 3; 
	font-size: 30px;
	font-family:Comic Sans MS;
	margin:20px;
}

#description
{
	font-size:15px; 
	font-family:Courier New;
	text-align: right; 
	padding-right:20px;
}

#description-right
{
	font-size:15px; 
	font-family:Courier New;
}

#name{}
#email{}
#number{}


</style>

<div><h2 style="color:#ffffcc; text-align: center; font-family:Comic Sans MS; font-size: 45px; ">Survey Form</h2></div>

<div class="ContentBG">
<div id="container">
<div class="surveyhead " style="text-align: center;"><u >Please Fill a form below</u></div>
<div  id="description"> First Name: </div>
<div ><input type="text" id="name" name="fname"placeholder="First Name"> </div>
<div  id="description"> Last Name: </div>
<div ><input type="text" id="name" name="Lname"placeholder="Last Name"> </div>
<div  id="description"> Email: </div>
<div ><input type="text" id="email" name="email" placeholder="Email"> </div>
<div  id="description"> Age: </div>
<div ><input type="text" id="number" name="age" placeholder="Age" min="1" max="125" type="number"> </div>

<div   id="description"> Which option best describes your current role?: </div>

<div id="description-right">
 <select name=" Which option best describes your current role?
">
  <option value="volvo">Student</option>
  <option value="saab">Full-time job</option>
  <option value="fiat">Part-time job</option>
  <option value="audi">Unemployment</option>
</select> 
</div>
<div  id="description"> How likely is that you would recommend freeCodeCamp to a friend? :</div>

<div  id="description-right" >
<form>
  <input type="radio" name="gender" value="male"> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other<br>  
</form>
</div>

<div   id="description"> What do you like most in FCC: </div>

<div id="description-right">
	<select name="select FCC">
	<option value="Figure">Figure</option>
	<option value="Nendroid">Nendroid</option>
	<option value="Fujimshi">Fujimshi</option>
	<option value="Music">Music</option>
	</select> 
</div>

<div   id="description"> Things that should be improved in the future
(Check all that apply): </div>

<div id="description-right">
	 <input type="checkbox" name="choice1" value="Front-end">Front-end Projects <br>
	<input type="checkbox" name="choice2" value="Back-end">Back-end Projects<br>
	<input type="checkbox" name="choice3" value="datavisul">Data Visualization<br>
	<input type="checkbox" name="choice4" value="Challenges">Challenges<br>
	<input type="checkbox" name="choice5" value="OPensource">Open Source Community<br>
	<input type="checkbox" name="choice6" value="Gitter">Gitter help rooms<br>
	<input type="checkbox" name="choice7" value="Videos">Videos<br>
	<input type="checkbox" name="choice8" value="City">City Meetups<br>
	<input type="checkbox" name="choice9" value="Wiki">Wiki<br>
	<input type="checkbox" name="choice10" value="Forum">Forum<br>
	<input type="checkbox" name="choice11" value="Additional ">Additional Courses<br>

</div>

</div>
</div>
