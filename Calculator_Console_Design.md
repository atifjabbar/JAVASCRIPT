// 1 --> make file index.html
// 2 --> open index.html file with text editor or vscode
// 3 --> copy this code into index.html and save
// 4 --> open index.html flie with any browser


<html>
	<head>
		<script>
			function Render()
			{
                alert("CALCULATOR FOR BEGINNER");
                var operator = prompt("Give your operation", "+ , - , * , /");
                if (operator === "+") 
	                {
	                var inputA = prompt("1st Input for Addition", "000");
                	var inputB = prompt("2nd Input for Addition", "000");
                	alert(Number(inputA) + Number(inputB));
                	}
                	else if (operator === "-") 
                		{
                		var inputA = prompt("1st Input for Subtraction", "000");
                		var inputB = prompt("2nd Input for Subtraction", "000");
                		alert(inputA - inputB);
                		}
                		else if (operator === "*") 
                			{
                			var inputA = prompt("1st Input for Multiplication", "000");
                			var inputB = prompt("2nd Input for Multiplication", "000");
                			alert(inputA * inputB);
                			}
                			else if (operator === "/") 
                   				{
                				var inputA = prompt("1st Input for Division", "000");
                				var inputB = prompt("2nd Input for Division", "000");
                				alert(inputA / inputB);
                				}
                				else
                                 	{
                    				alert("Operation Is Out Of Reach");
                    				}
			}
		</script>
	</head>
	<body>
		<form name="frmMain">
            <input type="submit" value="Click" onclick="Render()" />
        </form>
	</body>
</html>
