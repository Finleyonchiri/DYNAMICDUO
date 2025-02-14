
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Finley & Faith's Journey</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            padding-bottom: 50px; /* Added padding to prevent overlap with footer */
        }
        header {
            background-color: #ff8c00;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            padding: 14px 20px;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ff8c00;
        }
        section {
            padding: 20px;
            margin: 10px;
        }
        .content-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .content-container div {
            width: 48%;
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .highlight {
            font-weight: bold;
            color: #ff8c00;
        }
        .bounce {
            animation: bounce 1s infinite;
        }
        @keyframes bounce {
            0% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0); }
        }
        .profile-img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .spotify-playlist iframe, .podcast-embed iframe {
            width: 300px;
            height: 380px;
            border: none;
        }
        .date-count {
            font-size: 18px;
            margin-top: 20px;
        }
        .podcast-embed {
            display: flex;
            justify-content: center;
            padding: 20px;
        }
        .podcast-embed iframe {
            border: none;
            border-radius: 8px;
        }
        .hidden {
            display: none;
        }
        .button {
            background-color: #ff8c00;
            padding: 10px 20px;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            text-align: center;
        }
        .button:hover {
            background-color: #ff6600;
        }
        .form-input {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container {
            max-width: 600px;
            margin: 20px auto;
        }
        .score-table {
            width: 100%;
            border: 1px solid #ccc;
            border-collapse: collapse;
        }
        .score-table th, .score-table td {
            padding: 10px;
            text-align: center;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>

<!-- Home Page Welcome -->
<header>
    <h1>Welcome to Finley & Faith's Journey</h1>
    <a href="#" onclick="toggleSection('home-section')" class="button">Home</a>
</header>

<!-- Navigation -->
<nav>
    <a href="#" onclick="toggleSection('playlist-section')">Playlist</a>
    <a href="#" onclick="toggleSection('canva-section')">Canva</a>
    <a href="#" onclick="toggleSection('calendar-section')">Calendar</a>
    <a href="#" onclick="toggleSection('profile-section')">Profile</a>
    <a href="#" onclick="toggleSection('podcast-section')">Podcast</a>
</nav>

<!-- Home Section -->
<section id="home-section">
    <h2>Welcome to Our Site</h2>
<p>Faith and Finley Onchiri are a testament to love's enduring power, two hearts intertwined in a dance of devotion, laughter, and shared dreams. Their love story is a beautiful journey marked by unwavering support, deep understanding, and the magic of everyday moments cherished together. From whispered secrets to joyous celebrations, Faith and Finley have crafted a bond that grows stronger with each passing day, illuminating their lives with a radiant light that only true love can bring.</p>
<p>Welcome to our vibrant web space, a dynamic hub that seamlessly blends creativity, entertainment, and personalization. Our platform features an intuitive <strong>Canva</strong> integration, allowing users to create stunning designs effortlessly. Dive into an immersive world of <strong>games</strong> designed to entertain and challenge. Personalize your experience with a detailed <strong>profile</strong>, showcasing your unique identity. Finally, curate your own <strong>playlists</strong> to enjoy your favorite tunes and videos, making our web a go-to destination for creativity, fun, and personal expression.</p>
<p>🌟 Welcome to Today's Feedback! 🌟 Our vibrant website is your ultimate creative playground. With our intuitive <strong>Canva integration</strong>, you can effortlessly craft stunning designs. Step into an immersive world of <strong>games</strong> that entertain and challenge, while personalizing your experience with a detailed <strong>profile</strong> that showcases your unique identity. Curate your favorite tunes and videos with customizable <strong>playlists</strong>, making our platform a go-to hub for creativity, fun, and personal expression. We value your feedback immensely, so please share your thoughts with us in the form below! 😊</p>
<p>Your Name: <input type="text" id="name" name="name" placeholder="Enter your name" required></p>
<p>Your Email: <input type="email" id="email" name="email" placeholder="Enter your email" required></p>
<p>Your Feedback: <textarea id="feedback" name="feedback" rows="5" placeholder="Tell us your thoughts..." required></textarea></p>
<p><a href="mailto:nyabugafinley@gmail.com?subject=Feedback&body=Name:%20[name]%0AEmail:%20[email]%0AFeedback:%20[feedback]"><button type="submit">Submit Feedback</button></a></p>
<p id="successMessage" class="success-message" style="display:none;">Your feedback was received successfully! Thank you for sharing your thoughts with us.</p>
</section>
<section style="background-image: url('https://assets.onecompiler.app/42jd8ggps/438uv2s2r/WhatsApp%20Image%202025-02-12%20at%2014.23.40_eda2ea01.jpg'); background-size: cover; background-position: center; height: 30vh; color: white; text-align: center; display: flex; justify-content: center; align-items: center;">
    <h1>Welcome to Our Website</h1>
    <a href="https://finleyonchiri.github.io/faith-and-finley-daily-game/" style="padding: 10px 20px; background-color: #4CAF50; color: white; border-radius: 5px; text-decoration: none;">GAMES</a>
</section>
 <!-- Play Game Button -->
    <section id="play-game">
        <a href="https://finleyonchiri.github.io/faith-and-finley-daily-game/" target="_blank">
            <button class="play-button">Play Game</button>
        </a>
    </section>

<!-- Playlist Section -->
<section id="playlist-section" class="hidden">
    <h2>Our Playlists</h2>
    <div class="spotify-playlists">
        <p>Here are our favorite playlists. Enjoy!</p>

<p><strong>Giveon</strong></p>
        
        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/4fxd5Ee7UefO4CUXgwJ7IP?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Top Christian</strong></p>     

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/5rwdHhhy28n7iOnrSC291e?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Hot list ke</strong></p> 

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1DWWWXigQZAD8B?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Amapiano</strong></p>     

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/4Ymf8eaPQGT7HMTymoX82f?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>The Story Teller</strong></p>     

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/7xPDTxQrpZPvvI0LzuO73p?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Nyashinski</strong></p>      

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/7KY9NaOVRmptl8vlpVomi6?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Bien</strong></p>        

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/2zhossaaVN2pXg5p8o101X?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>mr Lamar</strong></p>   

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/2YZyLoL8N0Wb9xBt1NhZWg?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
<p><strong>Sauti Sol</strong></p>      

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/4Rj9lQm9oSiMlirgpsM6eo?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
</section>


<!-- Canva Section -->
<section id="canva-section" class="hidden">
    <h2>Our Canva</h2>
    <p>We have an encrypted Canva web accessible only via password. Please click the button below to access it.</p>
    <a href="https://talescybers.my.canva.site/finley-and-faith-s-private-website" class="bounce button" target="_blank">Visit Our Canva</a>
</section>

<!-- Calendar Section -->
<section id="calendar-section" class="hidden" style="background-color: #e3f2fd; border: 1px solid #4CAF50; border-radius: 15px; padding: 25px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <h2 style="color: #1e88e5; text-align: center; font-family: 'Arial Black', Gadget, sans-serif;">Our Journey - Days, Months, Years, Hours, Minutes & Seconds</h2>
    <div id="date-count" class="date-count" style="color: #333; font-weight: bold; font-size: 1.2em; text-align: center;">
        <!-- Timer will be shown here -->
    </div>
</section>

<!-- Profile Section -->
<section id="profile-section" class="hidden">
    <h2>Your Profiles</h2>
    <button onclick="toggleProfileDetails()">Show Profile Details</button>
    <div id="profile-details">
        <!-- Editable Profile Form -->
        <div class="form-container" id="profile-form-container">
            <h3>Edit Profile for Finley</h3>
            <label for="name">Name:</label>
            <input type="text" id="finley-name" class="form-input" placeholder="Enter your name">
            <label for="email">Email:</label>
            <input type="email" id="finley-email" class="form-input" placeholder="Enter your email">
            <label for="phone">Phone:</label>
            <input type="text" id="finley-phone" class="form-input" placeholder="Enter your phone number">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="finley-dob" class="form-input">
            <label for="profile-pic">Profile Picture:</label>
            <input type="file" id="profile-pic" class="form-input" accept="image/*">
            <button onclick="saveFinleyProfile()" class="button">Save Finley's Profile</button>
        </div>

        <div class="form-container" id="faith-form-container">
            <h3>Edit Profile for Faith</h3>
            <label for="name">Name:</label>
            <input type="text" id="faith-name" class="form-input" placeholder="Enter your name">
            <label for="email">Email:</label>
            <input type="email" id="faith-email" class="form-input" placeholder="Enter your email">
            <label for="phone">Phone:</label>
            <input type="text" id="faith-phone" class="form-input" placeholder="Enter your phone number">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="faith-dob" class="form-input">
            <label for="profile-pic">Profile Picture:</label>
            <input type="file" id="faith-profile-pic" class="form-input" accept="image/*">
            <button onclick="saveFaithProfile()" class="button">Save Faith's Profile</button>
        </div>

        <!-- Display Profile Data -->
        <div class="content-container">
            <div>
                <h3>Finley's Profile</h3>
                <img id="finley-img" class="profile-img" alt="Finley's Profile Picture">
                <p id="finley-name-text">Name: Finley</p>
                <p id="finley-email-text">Email: finley@example.com</p>
                <p id="finley-phone-text">Phone: 123-456-7890</p>
                <p id="finley-dob-text">Date of Birth: 1995-06-15</p>
            </div>
            <div>
                <h3>Faith's Profile</h3>
                <img id="faith-img" class="profile-img" alt="Faith's Profile Picture">
                <p id="faith-name-text">Name: Faith</p>
                <p id="faith-email-text">Email: faith@example.com</p>
                <p id="faith-phone-text">Phone: 098-765-4321</p>
                <p id="faith-dob-text">Date of Birth: 1996-11-10</p>
            </div>
        </div>

        <!-- Our Games Section -->
        <div id="score-section">
            <h3>Update Scores</h3>
            <h4>Finley's Score</h4>
            <input type="number" id="finley-score-input" class="form-input" placeholder="Enter Finley's score">
            <button onclick="updateFinleyScore()" class="button">Update Finley's Score</button>

            <h4>Faith's Score</h4>
            <input type="number" id="faith-score-input" class="form-input" placeholder="Enter Faith's score">
            <button onclick="updateFaithScore()" class="button">Update Faith's Score</button>

            <h4>Scoreboard</h4>
            <table class="score-table">
                <tr>
                    <th>Player</th>
                    <th>Score</th>
                </tr>
                <tr>
                    <td>Finley</td>
                    <td id="finley-score">0</td>
                </tr>
                <tr>
                    <td>Faith</td>
                    <td id="faith-score">0</td>
                </tr>
            </table>
        </div>
    </div>
</section>

<!-- Podcast Section -->
<section id="podcast-section" class="hidden">
    <h2>Our Podcasts</h2>
    <div class="spotify-podcasts">
        <p>Listen to our favorite podcasts!</p>

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/album/6YYGHDGOwrqvKxNZCkQs4r?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/show/5ehrCYFqWXgB8z2zaexKUj?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/episode/4O2f6QEg0qXWrUTWymDbkY?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/show/3JI1oNMx00PeIIxJfbz4ux?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
</section>

<script>
    // Toggle between sections
    function toggleSection(sectionId) {
        const sections = document.querySelectorAll('section');
        sections.forEach(section => section.classList.add('hidden'));

        const activeSection = document.getElementById(sectionId);
        activeSection.classList.remove('hidden');
    }

    // Show profile details when the button is clicked
    function toggleProfileDetails() {
        const profileFormContainer = document.getElementById('profile-form-container');
        profileFormContainer.classList.toggle('hidden');
        const faithFormContainer = document.getElementById('faith-form-container');
        faithFormContainer.classList.toggle('hidden');
    }

    // Show the date and time countdown
    const startDate = new Date("2024-11-06T00:00:00");
    function updateCountdown() {
        const now = new Date();
        const diff = now - startDate;

        const seconds = Math.floor(diff / 1000);
        const minutes = Math.floor(seconds / 60);
        const hours = Math.floor(minutes / 60);
        const days = Math.floor(hours / 24);
        const months = Math.floor(days / 30);
        const years = Math.floor(months / 12);

        document.getElementById('date-count').innerHTML = `
            We have been dating for ${years} years, ${months % 12} months, ${days % 30} days, ${hours % 24} hours, 
            ${minutes % 60} minutes, and ${seconds % 60} seconds!
        `;
    }
    setInterval(updateCountdown, 1000); // Update the countdown every second

    // Update Profile for Finley and Store in Local Storage
    function saveFinleyProfile() {
        var name = document.getElementById('finley-name').value;
        var email = document.getElementById('finley-email').value;
        var phone = document.getElementById('finley-phone').value;
        var dob = document.getElementById('finley-dob').value;
        var profilePic = document.getElementById('profile-pic').files[0] ? document.getElementById('profile-pic').files[0].name : null;

        // Update profile for Finley
        localStorage.setItem('finley-name', name);
        localStorage.setItem('finley-email', email);
        localStorage.setItem('finley-phone', phone);
        localStorage.setItem('finley-dob', dob);
        localStorage.setItem('finley-profilePic', profilePic);

        // Show updated information in profile section
        document.getElementById('finley-name-text').innerText = 'Name: ' + name;
        document.getElementById('finley-email-text').innerText = 'Email: ' + email;
        document.getElementById('finley-phone-text').innerText = 'Phone: ' + phone;
        document.getElementById('finley-dob-text').innerText = 'Date of Birth: ' + dob;

        if (profilePic) {
            document.getElementById('finley-img').src = URL.createObjectURL(document.getElementById('profile-pic').files[0]);
        }
    }

    // Update Profile for Faith and Store in Local Storage
    function saveFaithProfile() {
        var name = document.getElementById('faith-name').value;
        var email = document.getElementById('faith-email').value;
        var phone = document.getElementById('faith-phone').value;
        var dob = document.getElementById('faith-dob').value;
        var profilePic = document.getElementById('faith-profile-pic').files[0] ? document.getElementById('faith-profile-pic').files[0].name : null;

        // Update profile for Faith
        localStorage.setItem('faith-name', name);
        localStorage.setItem('faith-email', email);
        localStorage.setItem('faith-phone', phone);
        localStorage.setItem('faith-dob', dob);
        localStorage.setItem('faith-profilePic', profilePic);

        // Show updated information in profile section
        document.getElementById('faith-name-text').innerText = 'Name: ' + name;
        document.getElementById('faith-email-text').innerText = 'Email: ' + email;
        document.getElementById('faith-phone-text').innerText = 'Phone: ' + phone;
        document.getElementById('faith-dob-text').innerText = 'Date of Birth: ' + dob;

        if (profilePic) {
            document.getElementById('faith-img').src = URL.createObjectURL(document.getElementById('faith-profile-pic').files[0]);
        }
    }

    // Update Finley's Score in the Table
    function updateFinleyScore() {
        var score = document.getElementById('finley-score-input').value;
        document.getElementById('finley-score').innerText = score;
    }

    // Update Faith's Score in the Table
    function updateFaithScore() {
        var score = document.getElementById('faith-score-input').value;
        document.getElementById('faith-score').innerText = score;
    }
</script>
<footer style="background-color: #D4674C; color: white; padding: 5px; text-align: center;">
    <p>&copy; 2025 talesonlineoffices@gmail.com All rights reserved.</p>
    <div>
        <a href="https://facebook.com" style="color: blue; margin: 0 10px; text-decoration: none;">Facebook</a>
        <a href="https://twitter.com" style="color: blue; margin: 0 10px; text-decoration: none;">Twitter</a>
        <a href="https://instagram.com" style="color: blue; margin: 0 10px; text-decoration: none;">Instagram</a>
    </div>
</footer>

</body>
