# Demo 4

some texts

<!DOCTYPE html>
<html>
<head>
<title> Alcohol Units Calculator </title>
<link rel="stylesheet" type="text/css" href="alccalc.css">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
</head>

<body>

<h1>Alcohol Unit Calculator</h1>
<p>Units of alcohol are used as a way of helping people understand, and control, how much they drink.  This site focuses on UK units.  Other countries may use different quantities of alcohol per unit.  One unit of alcohol is 10 ml of alcohol.  One 125 ml glass of wine at 8% Alcohol by Volume (ABV) contains one unit of alcohol.  A litre bottle of vodka at 40% contains 40 units of alcohol.  To find out ho many units of alcohol are in a drink you need the size of the drink in litres, and the strength of the drink in ABV %.  You multiply these and the answer is the number of units.</p>

<p>This simple webpage will calculate how many units of alcohol are in a drink, or what the price per unit is.</p>


<form name="alcohol">
<fieldset>
<legend>Units Calculator</legend>
<p>Enter the serving size and the ABV%, but don't enter the l (liter) or % symbols.</p>
<ol>
<li><label for="size">Serving size in litres: <input type="text" name="size" id="size" /></label></li>
<li><label for="abv">ABV:<input type="text" name="abv" id="abv" /></label></li>
<li><label for="units">Units: <input type="text" name="units" id="units" /></label></li>
<li><input type="button" value="Calculate" onclick="alcohol.units.value=alcohol.size.value*alcohol.abv.value" /></li>
</ol>
<ul>
<li>One pint is 0.57 litres. A bottle of wine is usually 0.75 l.</li>
<li>There are 1000 ml on 1 l.  So, 330 ml is 0.33 l</li>
<li>Don't enter the % sign when entering the ABV.  Just enter the number.</li>
</ul>
</fieldset>
</form>

<hr>

<form name="priceperunit">
<fieldset>
<legend>Price per Unit Calculator</legend>
<ol>
<li><label for="totalcost">Cost in pounds and pence: <input type="text" name="totalcost" id="totalcost" /></label></li>
<li><label for="numberofunits">Number of Units: <input type="text" name="numberofunits" id="numberofunits" /></label></li>
<li><label for="costperunit">Cost per Unit: <input type="text" name="costperunit" id="costperunit" /></label></li>
<li><input type="button" value="Calculate" onclick="priceperunit.costperunit.value=priceperunit.totalcost.value/priceperunit.numberofunits.value" /></li>
</ol>
<ul>
<li>Don't enter the &pound; sign.  &pound;5.58 would be 5.58 </li>
<li>The result is in pounds. 0.6 is &pound;0.60, or 60p.</li>
</ul>
</fieldset>
</form>

<hr>
<h2>Recommended Limits</h2>
<p>In England we talk about "low risk" drinking, "increased risk" drinking, and "high risk" drinking.  Current guidelines for low risk drinking are no more than 2 to 3 units per day for women and 3 to 4 units per day for men; with some days alcohol free; and don't "save up" your units.  Increased risk drinking is under 50 units per week, but more than recommended levels (roughly 14 to 21 units per week for women and 21 to 28 units per week for men).  High risk drinking is more than 50 units per week.  For people with alcoholism a sudden stop in drinking can be dangerous.  To get a medically supervised detox a person would be drinking 40 units per day, or 20 units per day if they also have a severe mental health problem as well as the alcoholism.</p>


<hr>
<h2>What does 20 units look like? What does 40 units look like? What does 50 units look like?</h2>
<ul>
<li>Two bottles of 13% wine is about 19.5 units.  Four bottles of 13% wine is 39 units. Five bottles is 50 units.</li>
<li>Two and a half cans (500ml cans) of Tennent's Super (9%) lager is about 20 units.  Nine cans is a bit over 40 units. Eleven cans is about 50 units.</li>
<li>Seven pints of Stella Artois (4.8%ABV) is about 20 units.  Fourteen and a half pints is about 40 units.  Eighteen pints is about 50 units.</li>
<li>One litre of 'Tesco Fino Sherry' (15%) is 15 units.  Two and a half bottles is about 40 units.</li>
<li>Half a litre of spirits is roughly 20 units. One litre is roughly 40 units.</li>
</ul>
<hr>

<h2>Further Information</h2>

<ul>
<li><a href="http://www.nhs.uk/Livewell/alcohol/Pages/Alcoholhome.aspx">NHS Live Well - Drinking and Alcohol</a></li>
<li><a href="http://www.nhs.uk/conditions/Alcohol-misuse/Pages/Introduction.aspx">NHS - Alcohol misuse</a></li>
<li><a href="http://www.nice.org.uk/guidance/CG115">NICE CG115 - Alcohol-use disorders: diagnosis, assessment and management of harmful drinking and alcohol dependence</a></li>
<li><a href="https://www.gov.uk/government/policies/reducing-harmful-drinking">Gov.UK - Reducing harmful drinking</a></li>
<li><a href="https://en.wikipedia.org/wiki/Unit_of_alcohol">Wikipedia - Unit of Alcohol</a></li>
</ul>

<hr>
<p>I'm keen to transfer this from HTML tables to proper HTML and CSS.  I want it to validate as correct using W3C tools.  Please get in touch if you can help!  dan dot bealecocks at googlemail dot com</p>


</body>
</html>