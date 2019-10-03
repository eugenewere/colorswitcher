# colorswitcher
it allows you to change color of texts on click  off a specific color by adding this link

<link href="css/colors/default.css" rel="stylesheet" id="color-opt">

then create new css's files add change colors of ur liking
 eg 
  jquery code
    $("ul.pattern .default" ).click(function(){
			$("#color-opt").attr("href", "css/colors/default.css" );
			return false;
		});
    
    to green color
    $("ul.pattern .light-green" ).click(function(){
			$("#color-opt").attr("href", "css/colors/light-green.css" );
			return false;
		});

