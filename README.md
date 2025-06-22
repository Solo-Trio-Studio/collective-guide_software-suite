Run on ubuntu & apache. 


The following was used to generate the table form:

<DOCTYPE! html>
<body>
	<script>
		fI = 'abcdefghijklmnopqrs'.split('');
      		sI = ['a', 'b', 'c', 'd', 'e'];
		for(var i=0; i<18; i++) {
                 	console.log("<td><strong><label id="+fI[i].toUpperCase()+"></label></strong></td>");
                	console.log("<td><label for="+fI[i]+sI[0]+" id="+fI[i].toUpperCase()+sI[0].toUpperCase()+"></label></td>");
                	console.log("<td><input type=text id="+fI[i]+sI[0]+"/></td>");
                	console.log("<td><label for="+fI[i]+sI[1]+" id="+fI[i].toUpperCase()+sI[1].toUpperCase()+"></label></td>");
                	console.log("<td><input type=text id="+fI[i]+sI[1]+"/></td>");
                	console.log("<td><label for="+fI[i]+sI[2]+" id="+fI[i].toUpperCase()+sI[2].toUpperCase()+"></label></td>");
                	console.log("<td><input type=text id="+fI[i]+sI[2]+"/></td>");
                	console.log("<td><label for="+fI[i]+sI[3]+" id="+fI[i].toUpperCase()+sI[3].toUpperCase()+"></label></td>");
                	console.log("<td><input type=text id="+fI[i]+sI[3]+"/></td>");
                	console.log("<td><label for="+fI[i]+sI[4]+" id="+fI[i].toUpperCase()+sI[4].toUpperCase()+"></label></td>");
                	console.log("<td><input type=text id="+fI[i]+sI[4]+"/></td>");
			console.log("");
			console.log("N e X t");
			console.log("");
      		}
	</script>
</body>
