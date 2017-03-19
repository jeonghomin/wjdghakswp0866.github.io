<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8"/>
		<title>숙제 인덱스</title>
		<style>
			th, td {
				border: 1px solid black;
			}
			#nav ul {
				list-style-type: none;
				margin: 0px;
				padding: 0px;
				display: block;
			}	
			#nav {
				right: 0;
				position: absolute;
			}
			a {
				text-decoration: none;
				color: black;
			}
			a:hover {
				text-decoration: underline;
			}
			#name{
				text-align: right;			
			}
		</style>
	</head>
	
	<body>
		<h1>숙제 인덱스</h1>
		<h3 id="name">20161415 민정호</h3>
		<table id="nav">
			
			<tbody>	
				<tr>
					<td>
						<ul>
							<li><a href=#week1>1주차 과제</a></li>
							
						</ul>
					</td>
				</tr>	
			</tbody>
		</table>
			
		<ul>
			<li id="week1">1주차 과제
			<ul>
				<li><a href="/1/0.html" target="_blank">자바스크립트</a></li>
				<li><a href="/1/1.html" target="_blank">애국가</a></li>
				<li><a href="/1/2.html" target="_blank">애국가2</a></li>
			</ul>
			</li>
			
			
		</ul>
	</body>
</html>
