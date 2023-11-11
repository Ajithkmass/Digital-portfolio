<!DOCTYPE html>
<html>
<head>
    <style>
        /* Reset some default styles for the page */
        body, h1, p {
            margin: 0;
            padding: 0;
        }

        /* Style the navigation bar */
        .navbar {
            background-color: #333;
            color: white;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        /* Style the navigation links */
        .navbar a {
            text-decoration: none;
            color: white;
            margin: 0 10px;
        }

        /* Center the content */
        .content {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 500px;
        }

        /* Style the text */
        .text {
            text-align: center;
            padding: 20px;
        }

        /* Style the image */
        .image {
            max-width: 50%;
            height: auto;
        }

        /* Style the download link */
        .download-link {
            font-weight: bold;
            text-decoration: none;
            color: #333;
        }
	/* Style the navigation links */
	.navbar a {
   	 text-decoration: none;
    	color: white;
    	margin: 0 10px;
    	transition: color 0.3s; /* Add a smooth color transition effect */
	}

	/* Apply the hover effect */
	.navbar a:hover {
   	 color: #ffcc00; /* Change the link color on hover */
	}

    </style>
</head>
<body>
    <div class="navbar">
        <div>
            <h1>My Website</h1>
        </div>
        <div>
            <a href="#portfolio">Portfolio</a>
            <a href="#home">Home</a>
            <a href="#contact">Contact</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#skills">Skills</a>
        </div>
    </div>

    <div class="content">
        <div class="text">
            <h2>AJITH</h2>
            <p>THSIS IS MY OFFICIAL PORTFOLIO WEBSITE 
                     TO SHOW YOU ALL
               I AM STUDYING IN ST JOHN'S COLLEGE</p>
            <a class="download-link" href="your-cv.pdf" download>Download CV</a>
        </div>
        <div class="image">
            <img src="workoholic.png" alt="Image Description">
        </div>
    </div>
</body>
</html>
