# GoogleMapAPI

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
