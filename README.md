<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="style.css">
</head>
<body>
    <!-- nav bar -->
    <header class="nav">
        <ul class="nav-home">
            <li style="color: #65AEF2">Home</li>
            <li style="color: #262626">About</li>
            <li style="color: #262626">Newsletter</li>
            <li style="color: #262626">Rooms</li>
            <li style="color: #262626">Services</li>
            <li style="color: #262626">Pricing</li>
        </ul>
    </header>

    <!-- hero section -->
    <section>
        <p>Discover Extraordinary Comfort in Hotels</p>
    </section>

    <!-- section -->
    <section>
        <h4>Special Offers</h4>
        <h3>Best offer of the month</h3>
        <p>Experience Fantastic Benefits and Obtain Better Rates When You Make a Direct Booking on Our Official Website</p>
        <a>View all</a>
        <div>
            <div>
                <img>
                <b>Room</b>
                <h4>Honeymoon</h4>
                <p>Indulge in a Memorable One-Time Romantic Dinner for Two</p>
                <div>
                    <h4>$699</h4>
                    <h6>/night</h6>
                </div>
                
            </div>
            <div>
                <img>
                <b>Room</b>
                <h4>Meetings</h4>
                <p>Experience an Exclusively Private Environment to Boost Your Productivity</p>
                <div>
                    <h4>$999</h4>
                    <h6>/night</h6>
                </div>
                
            </div>
            <div>
                <img>
                <b>Dining</b>
                <h4>Romantic Dining</h4>
                <p>Indulge in a Memorable One-Time Romantic Dinner for Two</p>
                <div>
                    <h4>$499</h4>
                    <h6>/table</h6>
                </div>
                
            </div>
        </div>
    </section>

    <!-- footer -->
     <section>
        <form>
            <label>Newsletter & Special Promo</label>
            <input type="email" placeholder="Enter your email here">
            <input type="button">
        </form>
        <div>
            <ul>
                <li>About us</li>
                <li>Contact</li>
                <li>Location</li>
            </ul>
            <ul>
                <li>FAQ</li>
                <li>Term of Use</li>
                <li>Privacy Police</li>
            </ul>
            <ul>
                <li>Services & Facilities</li>
                <li>Careers</li>
                <li>How to book</li>
            </ul>
        </div>
     </section>

</body>
</html>




.nav {
    background: #FFFFFF;
    width: 1440px;
    height: 80px;
    border-radius: 18px;
    padding-top: 19px;
    padding-right: 49px;
    padding-bottom: 19px;
    padding-left: 49px;
    gap: 120px;
}

.nav li {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 3rem;
}

.nav-home {
    font-weight: 400px;
    font-style: 'Regular';
    font-size: 24px;
    line-height: 100%;
    letter-spacing: 0%;
}

.nav-ul {
    font-weight: 400px;
    font-style: 'Regular';
    font-size: 24px;
    line-height: 100%;
    letter-spacing: 0%;
    color: #262626;
}
