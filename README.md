# html_css
//html part
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo">
                <img src="C:\Users\manvi\Downloads\logo.png" alt="Myntra Logo">
            </div>
            <div class="search-bar">
                <input type="text" placeholder="Search for products, brands and more">
                <button><img src="C:\Users\manvi\Downloads\search.png" style="width:20px;height:20px;" alt="Search"></button>
            </div>
            <div class="icons">
			    <div class="icon"><img src="C:\Users\manvi\Downloads\profile.png" style="width:20px;height:20px;"><p style="font-size:60%;font-family:verdana;text-align:center;"> Profile</p></div>
                <div class="icon"><img src="C:\Users\manvi\Downloads\like.jpg" style="width:30px;height:20px;"><p style="font-size:60%;font-family:verdana;text-align:center;"> Wishlist</p></div>
                <div class="icon"><img src="C:\Users\manvi\Downloads\bag.jpg" style="width:20px;height:20px;"><p style="font-size:60%;font-family:verdana;text-align:center;"> Bag</p></div>
                
            </div>
        </div>
        <nav>
            <ul>
                <li>Men</li>
                <li>Women</li>
                <li>Kids</li>
                <li>Footwear</li>
                <li>Home</li>
                <li>Beauty</li>
				<li>Studio</li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="carousel">
            <img src="C:\Users\manvi\Downloads\men.jpg" style="width:70px;height:70px;">
            <img src="C:\Users\manvi\Downloads\women.jpg"  style="width:70px;height:70px;">
            <img src="C:\Users\manvi\Downloads\kids.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\footwear.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\home.jpg" style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\beauty.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\hand bag.jpg"  style="width:70px;height:70px;">
			
			<img src="C:\Users\manvi\Downloads\watch.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\jeweller.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\headphones.jpg"  style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\sunglasses.jpg" style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\traveling bag.jpg" style="width:70px;height:70px;">
			
			<img src="C:\Users\manvi\Downloads\skincare.jpg" style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\hair care.jpg" style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\gym.jpg" style="width:70px;height:70px;">
			<img src="C:\Users\manvi\Downloads\chappal.jpg" style="width:70px;height:70px;">
		
        </section>
		<div>
		<img src="C:\Users\manvi\Downloads\sam.webp" style="align:center;width:1200px;height:800px;">		
		</div>
		<div>
		<img src="C:\Users\manvi\Downloads\ranbir.jpg" style="align:center;width:1200px;height:500px;">	
		</div>
		
		
    </main>
    <footer>
        <ul>
            <li>Privacy Policy</li>
            <li>Terms of Use</li>
            <li>Contact Us</li>
        </ul>
    </footer>
</body>
</html>




//css part
/* Reset CSS */
* {
    padding: 0;
	margin: 0;
    box-sizing: border-box;
}
body 
{
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}
header 
{
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.navbar
{
    display: flex;
    align-items: center;
}
.logo img 
{
    max-height: 40px;
}
.search-bar 
{
    flex: 1;
    display: flex;
    overflow: hidden;
	align-items: center;
    border: 1px solid #ccc;
    border-radius: 20px;
}
.search-bar input[type="text"] 
{
    flex: 1;
    padding: 10px;
    border: none;
    outline: none;
}
.search-bar button 
{
    padding: 8px;
    cursor: pointer;
	background-color: transparent;
    border: none;
}
.icons 
{
    display: flex;
    margin-left: 20px;
}
.icon 
{
    margin-right: 10px;
    cursor: pointer;
}
nav ul 
{
    list-style-type: none;
    padding: 0;
    margin: 10px 0;
    display: flex;
}
nav ul li 
{
    margin-right: 20px;
    cursor: pointer;
}
main 
{
    padding: 20px;
}
.carousel 
{
    margin-bottom: 20px;
}
.carousel img 
{
    width: 100%;
    border-radius: 5px;
}
.featured-categories 
{
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.featured-categories h2 
{
    margin-bottom: 20px;
}
.category 
{
    width: 22%;
    margin-right: 4%;
    margin-bottom: 20px;
    float: left;
    text-align: center;
}
.category img 
{
    width: 100%;
    border-radius: 5px;
}
.category p 
{
    margin-top: 10px;
}
footer 
{
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}
footer ul 
{
    list-style-type: none;
    padding: 0;
}
footer ul li 
{
    display: inline;
    margin-right: 20px;
    cursor: pointer;
}

