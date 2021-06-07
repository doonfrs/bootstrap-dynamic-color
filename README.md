# Bootstrap 5 Dynamic color
I've replaced all hard coded colors in default bootstrap theme with variable (primary,secondary etc..)
and now you can override default colors without the need of rebuilding bootstrap sass files.

## usage example
    <html>
    <head>
    <style>
	  <link rel="stylesheet" href="csspath/bootstrap5dynamic.css">
	
	<!-- Or RTL version
	<!--<link rel="stylesheet" href="csspath/bootstrap5dynamic-rtl.css">!-->
	  
	  <!-- override bootstrap variables !-->
	<style>
    :root {
    	--bs-blue: #0d6efd;
    	--bs-indigo: #6610f2;
    	--bs-purple: #6f42c1;
    	--bs-pink: #d63384;
    	--bs-red: #dc3545;
    	--bs-orange: #fd7e14;
    	--bs-yellow: #ffc107;
    	--bs-green: #198754;
    	--bs-teal: #20c997;
    	--bs-cyan: #0dcaf0;
    	--bs-white: #fff;
    	--bs-gray: #6c757d;
    	--bs-gray-dark: #343a40;
    	--bs-primary: red;
    	--bs-secondary: #6c757d;
    	--bs-success: #198754;
    	--bs-info: #0dcaf0;
    	--bs-warning: #ffc107;
    	--bs-danger: #dc3545;
    	--bs-light: #f8f9fa;
    	--bs-dark: #212529;"
    </style>
    </head>
    <body>
    
    </body>
    </html>
