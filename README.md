5 months intern at Sunbytes company - Ho Chi Minh city 
21/5/2021 - Learn slick slider

#1. What is this? 
This can help you create the carousel for your website faster and esier. There are many kind of slider which you want to use.

#2: Reference: https://kenwheeler.github.io/slick/

#3: How to use? 
	##3.1 HTML project 
		###Step 1: Create a project on local 
		###Step 2: Create css, js, images folders and index.html file 
		###Step 3: Download frameworks are nessecsary. 
			####3.1: Download slick slider form the "Reference" - extract file 
			####3.2: Download bootstrap any version ( You can search like: download bootstrap 4.6 and download it) - extract file 
			####3.3: Download jquery: https://jquery.com/download/ ( Right click and save link - example: "Download the uncompressed, development jQuery 3.6.0 slim build") - extract file 
			####3.4: Download popper: https://store.jahia.com/module/popperjs - extract file Step 
#4: Copy files 
	##4.1: Copy bootstrap.min.css, slick.css, slick-theme.css to css folder in the local project 
	##4.2: Copy bootstrap.min.js,jquery-3.6.0.slim.min.js, popper.min.js, slick.min.js to js folder in the local project 

#Step 5: Download images and save them on the images folder 

#Step 6: Open index.html file Add links in tag: Add links in tag: 
	<script src="js/bootstrap.min.js"></script> 
	<script src="js/jquery-3.6.0.slim.min.js"></script> 
	<script src="js/popper.min.js"></script>
	<script src="js/slick.min.js"></script> 

#Step 7: Add html for index file 

#Step 8: Add script for run slick slider 
	<script> $('.slider').slick({ 
		slidesToShow: 1, 
		slidesToScroll: 1, 
		autoplay: true, 
		autoplaySpeed: 1000, 
		});
	</script> 
This is one of types that you can use in slick slider. If you don not want your carousel like this please choose another in "Reference".
