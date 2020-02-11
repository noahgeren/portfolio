<!DOCTYPE html>
<html xmlns:th="https://thymeleaf.org" xmlns:layout="http://www.ultraq.net.nz/thymeleaf/layout" th:lang="${#locale.language}">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Noah Geren</title>
	<!-- Fonts -->
	<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
	<!-- CSS -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
	<link rel="stylesheet" href="//unpkg.com/bootstrap-vue@latest/dist/bootstrap-vue.min.css" />
	<!-- Javascript -->
	<script src="//polyfill.io/v3/polyfill.min.js?features=es2015%2CIntersectionObserver"></script>
	<script src="https://cdn.jsdelivr.net/npm/vue@2.6.11"></script>
	<script src="//unpkg.com/bootstrap-vue@latest/dist/bootstrap-vue.min.js"></script>
	<!-- Style -->
	<style>
		body {
			font-family:"Roboto", sans-serif;
		}
		h1 {
			font-size: 48pt;
		}
	</style>
</head>
<body>
	<div id="app">
		<b-container fluid>
	    	<b-row>
	    		<b-col class="text-center">
	    			<img th:src="@{/img/NoahHeadshot.jpeg}" class="rounded-circle h-50" />
	    			<h1>Noah Geren</h1>
	    		</b-col>
	    	</b-row>
	    </b-container>
	</div>
</body>
<script>
	const app = new Vue({
		el: '#app'
	});
</script>
</html>