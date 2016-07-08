Responsive web design

reset.css // to override html element property

normalize.css // it's maintain css property stable on each browser

Meta
<meta name="viewport" content="width=device-width, initial-scale=1"

viewport //it try to adjust the view as per device

css // handle media query for min and max width and orientation

units
px //need to define for each device size not a better option for responsive
rem //it will work according to root
	if body font-size: 10px
	and child div font-size:1.5rem; then it will 15px actually
	//Not better option
em //it will work according to parent
	if div font-size: 10px
	and child div font-size:1.5em; then it will 15px actually
	//better option
vh (similar to %)
	//it's depend on device height;
vw (similar to %)
	//it's depend on device width;
	//Best option
 
Approach name: Desktop first Approach, Mobile first approach