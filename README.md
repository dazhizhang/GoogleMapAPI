# GoogleMapAPI
documentation 
Maps Embed API
    	https://developers.google.com/maps/documentation/embed/embedding-map?hl=zh-cn#place_id_parameters 

获取地点ID 
	https://console.cloud.google.com/google/maps-apis/api-list?project=united-bot-436600-m4&authuser=1 

	places api
	https://developers.google.com/maps/documentation/places/web-service/choose-api?hl=zh-cn
# code

<!DOCTYPE html>
<html>
    <head>
        <title>PHP Test3</title>
    </head>
    <body>
    	
    	<?php echo '<p>Hello World3</p>'; ?>
    	
    	<?php 
    	$location = "City+Hall,New+York,NY"; 
    	?>

    	Location: <input type="text" name="name" value="<?php echo $location;?>">

       
        <!--这是一个注释，注释在浏览器中不会显示 使用place_id
<iframe width="600" height="450" style="border:0" 正在加载="lazy" allowfullscreen src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJk4kqj4sz34cRdxAfDbDue2k&key=BALABALABALA"></iframe>
-->
<iframe width="600" height="450" style="border:0" 正在加载="lazy" allowfullscreen src="https://www.google.com/maps/embed/v1/place?q=City+Hall,New+York,NY&key=AIzaSyDbMRIR9ulgYXGG6C7JmCV_FteaFcsuC18"></iframe>

    </body>
</html>
