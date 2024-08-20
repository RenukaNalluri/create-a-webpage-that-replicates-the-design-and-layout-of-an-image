# create-a-webpage-that-replicates-the-design-and-layout-of-an-image
#html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css"/>
</head>
<body>
    <section class="about-section">
        
            <img src="image.jpg"/>
            <div class="about-content">
                <h1>About US</h1>
                <h2>Sample Headline</h2>
                <p>Article evident arrived express highest men did boy.Mistress<br/>sensible entirely am
                so.Quick can manor smart money hopes worth<br/>too.Comfort produce husband boy
                her had hearing. Law others<br/>theirs passed but wishes . You day real less till dear
                read. Considered<br/>use dispatched melancholy sympathize discreation led. Oh feel if up<br/>
                to till like </p>
                <p>Image from <b>Freepik</b></p>
                <button>Contact Us</button>
            </div>
        
        <div class="info-class">
            <div class="card">
            <h3>📞 CALL US</h3>
                <p>1-234-567-8901</p>
                <p>1-234-567-8901</p>    
            </div>
            <div class="card h3">
                <h3>📍 LOCATION</h3>
                <p>123 Rock Street,21 Avenue,New York,NY 123-4560</p>
            </div>
            <div class="card p">
                <h3>🕒 HOURS</h3>
                <p>Mon - Fri : 8am - 8pm , Sat - Sun : 9am - 6pm</p>
            </div>
        </div>
        

    </section>
    
</body>
</html>

#css

img{
    
    width: 350px;
    height: 250px;
    margin-right: 500px;
    margin-top: 100px;
}
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f0e9e2;
}

.about-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    
}

.about-container {
    display: flex;
    justify-content: space-between;
    margin-left: 300px ;
    
    
}

.about-image {
    max-width: 300px;
    border-radius: 10px;
}

.about-content {

    margin-left: 450px;
    margin-top: -250px;
    margin-bottom: 80px;
    

    
}

h1 {
    font-size: 2em;
    margin: 0;
}

h2 {
    font-size: 1.5em;
    color: black;
}

p {
    line-height: 1.6;
}

.image-credit {
    font-size: 0.8em;
    color: #ff6333;
}

.contact-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: black;
    color: #ff6333;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

.info-cards {
    display: flex;
    justify-content: space-around;
    width: 80%;
    margin-top: 30px;
}

.card {
    background-color: #ff6333;
    color: white;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    width: 230px;
    height: 100px;
    float: left;
    margin: 25px;
    font-size: medium;

}

.card h3 {
    margin: 5px;
    float: left;
}

.card p {
    margin: 5px;
    float: left;
}
button{
    background-color: black;
    border-radius: 10px;
    width: 100px;
    height: 25px;
    color: #f0e9e2;
}
