<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>College Student Council of Ligao Community College Inc.</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #eef1f7;
            color: #1b1b1b;
        }
        header {
            background: linear-gradient(135deg, #0033a0, #0059e6);
            color: white;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ffcc00;
            padding: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
        }
        nav a {
            margin: 0 20px;
            color: #0033a0;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #001a66;
            transform: scale(1.1);
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 20px 10px;
        }
        .section {
            background: white;
            padding: 25px;
            margin-top: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .section:hover {
            transform: translateY(-3px);
        }
        .logo {
            display: block;
            margin: 0 auto 20px auto;
            width: 220px;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.2));
        }
        h2 {
            color: #0033a0;
            border-left: 6px solid #ffcc00;
            padding-left: 10px;
        }
        .login-box input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 1rem;
            outline: none;
            transition: 0.3s;
        }
        .login-box input:focus {
            border-color: #0033a0;
            box-shadow: 0 0 6px rgba(0,51,160,0.3);
        }
        .btn {
            background-color: #0033a0;
            color: white;
            padding: 12px;
            border: none;
            width: 100%;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1rem;
            margin-top: 8px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #002266;
            transform: scale(1.02);
        }
        a {
            color: #0033a0;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <img src="541526356_797711839450215_8497742864824694207_n.jpg" alt="CSC Logo" class="logo">
        <h1>College Student Council of Ligao Community College Inc.</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#transparency">Transparency</a>
        <a href="#announcements">Announcements</a>
        <a href="#more">More</a>
    </nav>

    <div class="container">

        <!-- LOGIN FIRST PAGE -->
        <div class="section" id="login">
            <h2>Login</h2>
            <p>Please login to access the system.</p>
            <div class="login-box">
                <input type="text" placeholder="Email or Username" />
                <input type="password" placeholder="Password" />
                <a href="#home"><button class="btn">Login</button></a>
                <br><br>
                <p>Don't have an account? <a href="#create">Create Account</a></p>
            </div>
        </div>

        <!-- CREATE ACCOUNT PAGE -->
        <div class="section" id="create">
            <h2>Create an Account</h2>
            <div class="login-box">
                <input type="text" placeholder="Last Name" />
                <input type="text" placeholder="First Name" />
                <input type="text" placeholder="Middle Initial" />

                <input type="number" placeholder="Age" />

                <input type="text" placeholder="Program" />
                <input type="text" placeholder="Year Level" />
                <input type="text" placeholder="ID Number" />

                <input type="email" placeholder="Email Address" />
                <input type="password" placeholder="Create Password" />

                <input type="text" placeholder="If CSC Officer, indicate Position" />
                <input type="text" placeholder="CSC Identity Code" />

                <button class="btn">Confirm</button>

                <p style="margin-top:15px; font-weight:bold; color:#0033a0;">Once confirmed, your account will be under verification process. Please wait within 24 hours for processing.<br>Check your email for confirmation.</p>
            </div>
        </div>
        </div>

        <!-- HOME PAGE AFTER LOGIN -->
        <div class="section" id="home">
            <h2>Homepage</h2>
            <p>This homepage appears AFTER login. Students will see Transparency and Announcements only. Officers will see additional access for uploading reports.</p>
        </div>

        <!-- TRANSPARENCY -->
        <div class="section" id="transparency">
            <h2>Transparency Section</h2>
            <p>Students can access published transparency documents, financial reports, and council updates here.</p>
        </div>

        <!-- ANNOUNCEMENTS -->
        <div class="section" id="announcements">
            <h2>Announcements & Updates</h2>
            <p>Stay updated with the latest activities, projects, and important notices from the CSC.</p>
        </div>

        <!-- OFFICER PANEL (HIDDEN TO STUDENTS) -->
        <div class="section" id="officer-panel">
            <h2>Officer Panel (Restricted)</h2>
            <p>Officers can upload Transparency Reports and Announcements here.</p>
        </div>

        <!-- MORE -->
        <div class="section" id="more">
            <h2>More</h2>
            <p>Account Settings | Logout</p>
        </div>

    </div>
</body>
</html>
