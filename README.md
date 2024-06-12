<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kapenguria Dental Centre</title>
    <style>
        /* General styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header styles */
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            margin: 5px 0;
        }

        header h2 {
            margin-top: 5px;
        }

        header img {
            max-width: 200px;
            margin-top: 10px;
            border-radius: 50%;
            transition: transform 0.3s ease;
        }

        header img:hover {
            transform: scale(2.1);
        }

        /* Navigation styles */
        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
            background-color: #fff;
            border-bottom: 1px solid #ccc;
        }

        nav ul li {
            display: inline-block;
            margin-right: 20px;
            position: relative;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 10px 15px;
            display: block;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #4CAF50;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
            left: 0;
        }

        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #f1f1f1;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* Main content styles */
        main {
            padding: 20px 0;
        }

        section {
            margin-bottom: 30px;
        }

        section h2 {
            color: #4CAF50;
        }

        section ul {
            padding-left: 20px;
        }

        /* Footer styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Utility styles */
        .text-center {
            text-align: center;
        }

        .text-blue {
            color: blue;
        }
    </style>
</head>
<body>
    <!-- Header section -->
    <header>
        <h1>Kapenguria Dental Centre</h1>
        <h2>One Stop Centre for All Dental Solutions</h2>
        <!-- Add your logo here -->
        <img src="image3.jpeg" alt="Kapenguria Dental Centre Logo">
    </header>

    <!-- Navigation menu -->
    <nav>
        <ul>
            <li class="dropdown">
                <a href="#" class="dropbtn">Patient</a>
                <div class="dropdown-content">
                    <a href="patient.php">Patient Form</a>
                    <a href="patient2.php">Patient List</a>
                </div>
            </li>
            <li class="dropdown">
                <a href="#" class="dropbtn">Booking Appointment</a>
                <div class="dropdown-content">
                    <a href="appointment.php">Book Appointment</a>
                    <a href="appointment2.php">Appointments</a>
                </div>
            </li>
            <li class="dropdown">
                <a href="#" class="dropbtn">Comments</a>
                <div class="dropdown-content">
                    <a href="comment.php">Comment and Rate</a>
                    <a href="comment2.php">Comments and Ratings</a>
                </div>
            </li>
        </ul>
    </nav>

    <!-- Main content section -->
    <main class="container">
        <!-- Services section -->
        <section id="services">
            <h2>Services Offered</h2>
            <ul>
                <li>Implants</li>
                <li>Extractions</li>
                <li>Teeth Cleaning</li>
                <li>Dental consultation</li>
                <li>Oral hygiene instructions and motivation</li>
                <li>Diet counselling</li>
                <li>Paediatric dentistry</li>
                <li>Orthodontic and braces work</li>
                <li>Teeth filling</li>
                <li>Scaling and polishing/teeth cleaning</li>
                <li>Teeth whitening</li>
                <li>Minor oral surgery</li>
                <li>Emergency and referral service</li>
                <li>Drugs prescription</li>
                <li>Teeth replacement (crown and bridge work, dentures, metal frameworks)</li>
                <li>Root canal treatment</li>
                <li>Biopsy services</li>
                <li>Radiology services (IOPA x-ray, BBW, OPG, lateral cephalograms, skull view, others)</li>
            </ul>
        </section>

        <!-- Dental diseases section -->
        <section id="diseases">
            <h2>Dental Diseases</h2>
            <ul>
                <li>Dental caries</li>
                <li>Pulp disease</li>
                <li>Gum disease</li>
                <li>Oral cancers</li>
                <li>Fractured teeth and jaw bones</li>
                <li>Soft tissue facial injuries</li>
                <li>Teeth malocclusion</li>
                <li>Paediatric teeth conditions</li>
                <li>Dental abscess</li>
                <li>Jaw diseases</li>
            </ul>
        </section>

        <!-- Staff section -->
        <section id="staff">
            <h2>Our Staff</h2>
            <ul>
                <li>Dental Officers: [Names and Contacts]</li>
                <li>Dental Assistants: [Names and Contacts]</li>
                <!-- Add more staff members here -->
            </ul>
        </section>

        <!-- Location section -->
        <section id="location">
            <h2>Location</h2>
            <p>Address: Teachers Plaza, Opposite Main Stage, Ground Floor, Room 8, Kapenguria, West Pokot</p>
        </section>

        <!-- Contact section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Phone No: 0739275898</p>
            <p>Email: kapedent@gmail.com</p>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p class="text-blue">&copy; 2024 Kapenguria Dental Centre. All rights reserved.</p>
    </footer>
</body>
</html>
