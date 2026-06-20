<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Elite Exterior Services</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#0f172a;
    color:white;
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    font-size:1.2rem;
}

.hero-btn{
    display:inline-block;
    margin-top:20px;
    background:#22c55e;
    color:white;
    padding:12px 24px;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

.services{
    padding:60px 20px;
    text-align:center;
}

.services h2{
    margin-bottom:40px;
    font-size:2.2rem;
}

.service-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    max-width:1200px;
    margin:auto;
}

.card{
    background:white;
    padding:30px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.card h3{
    margin-bottom:15px;
    color:#0f172a;
}

.price{
    font-size:2rem;
    color:#22c55e;
    margin:15px 0;
    font-weight:bold;
}

.pricing{
    background:#0f172a;
    color:white;
    padding:60px 20px;
    text-align:center;
}

.pricing h2{
    margin-bottom:20px;
}

.pricing-box{
    max-width:700px;
    margin:auto;
    background:white;
    color:#333;
    padding:30px;
    border-radius:10px;
}

.contact{
    padding:60px 20px;
    text-align:center;
}

form{
    max-width:600px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:5px;
}

button{
    background:#22c55e;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:5px;
    cursor:pointer;
    font-size:1rem;
}

footer{
    background:#111827;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>
<body>

<header>
    <h1>Elite Exterior Services</h1>
    <p>Pressure Washing • Car Detailing • Window Cleaning</p>
    <a href="#contact" class="hero-btn">Get a Free Quote</a>
</header>

<section class="services">
    <h2>Our Services</h2>

    <div class="service-grid">

        <div class="card">
            <h3>Pressure Washing</h3>
            <p>Driveways, sidewalks, patios, fences, and exterior surfaces.</p>
            <div class="price">$99.99</div>
        </div>

        <div class="card">
            <h3>Car Detailing</h3>
            <p>Interior and exterior detailing to make your vehicle shine.</p>
            <div class="price">$99.99</div>
        </div>

        <div class="card">
            <h3>Window Cleaning</h3>
            <p>Streak-free residential and commercial window cleaning.</p>
            <div class="price">$99.99</div>
        </div>

    </div>
</section>

<section class="pricing">
    <h2>Simple Pricing</h2>

    <div class="pricing-box">
        <h3>Base Service</h3>
        <p>$99.99 for any single service.</p>

        <br>

        <h3>Bundle Pricing</h3>
        <p>
            Add any additional service for only <strong>$50</strong>.
        </p>

        <br>

        <p>
            Examples:
        </p>

        <ul style="list-style:none; margin-top:10px;">
            <li>1 Service = $99.99</li>
            <li>2 Services = $149.99</li>
            <li>3 Services = $199.99</li>
        </ul>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Request a Quote</h2>

    <form>
        <input type="text" placeholder="Your Name" required>

        <input type="email" placeholder="Email Address" required>

        <input type="tel" placeholder="Phone Number">

        <textarea rows="5" placeholder="Tell us what services you need"></textarea>

        <button type="submit">Submit Request</button>
    </form>
</section>

<footer>
    <p>&copy; 2026 Elite Exterior Services. All Rights Reserved.</p>
</footer>

</body>
</html>
