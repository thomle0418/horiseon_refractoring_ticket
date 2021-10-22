# horiseon_refractoring_ticket

For this assignment I refractored the HTML and CSS files for Horiseon Social Solutions Services, Inc. Refactoring was done in a manner that upheld the integrity of the website. I edited proper semantic elements to the HTML code and increased the web page's acessibility by including detailed descriptions to images. Lastly I condensed CSS attributes that shared similar properties to streamline the file for ease of readability. 




<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon Social Solution Services</title>
</head>

<body>
<!--Header and Navigation Bar Section-->
    
    <header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

    <article class="hero" title="Team members in a meeting"></article>

<!--Search Engine Optimization, Online Reputation Management, and Social Media Marketing Section-->
    <section class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" alt="Notebook with a diagram of SEO written in it on a desk." class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>

        <div class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="Reputation chart depicated on a laptop" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>

        <div class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="Logos of various social media placed on a table" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </section>

<!--Benefits Section-->
    <aside class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="Lead Generation" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>

        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Brand Awareness" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>

        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Cost Management" />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </aside>
<!--Footer Section-->
    <section class="footer">
        <h4>Made with ❤️️ by Horiseon</h4>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </section>
</body>

</html>

