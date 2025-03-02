<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AIO - Outstanding Front Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
            text-align: center;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .nav {
            display: flex;
            gap: 20px;
            position: relative;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            position: relative;
        }
        .dropdown {
            position: absolute;
            background: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            display: none;
            flex-direction: column;
            top: 25px;
            left: 0;
        }
        .dropdown a {
            color: black;
            padding: 10px;
            text-decoration: none;
            display: block;
            white-space: nowrap;
        }
        .dropdown a:hover {
            background: #ddd;
        }
        .nav-item:hover .dropdown {
            display: flex;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .story-box {
            display: flex;
            gap: 10px;
            overflow-x: auto;
            padding: 10px;
            background: #fff;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .story {
            width: 80px;
            height: 120px;
            background: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
            font-weight: bold;
        }
        .post-box {
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .post-box textarea {
            width: 100%;
            height: 60px;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            resize: none;
        }
        .post-box button {
            margin-top: 10px;
            padding: 10px;
            width: 100%;
            border: none;
            background: #333;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        .gap {
            height: 100px;
            width: 100%;
            display: flex;
        }
        .box-container {
            display: flex;
            justify-content: space-between;
            width: 100%;
        }
        .box {
            height: 200px;
            width: 50%;
            background: rgb(224, 248, 117);
        }
    </style>
</head>
<body>
    <header>
        <h1>AIO</h1>
        <nav class="nav">
            <a href="#video">Video</a>
            <div class="nav-item">
                <a href="#tutor">Tutor</a>
                <div class="dropdown">
                    <a href="#tutor-post">Post</a>
                    <a href="#tutor-video">Video</a>
                </div>
            </div>
            <a href="#advice">Advice</a>
            <a href="#profile">Profile</a>
        </nav>
    </header>
    
    <div class="container">
        <div class="story-box">
            <div class="story">Your Story</div>
            <div class="story">Story 1</div>
            <div class="story">Story 2</div>
            <div class="story">Story 3</div>
        </div>
        
        <div class="post-box">
            <textarea placeholder="What's on your mind?"></textarea>
            <button>Post</button>
        </div>
        
        <div class="gap"></div>
        
        <div class="box-container">
            <div class="box"></div>
            <div class="box"></div>
        </div>
        
        <div class="section" id="video">
            <h2>Photos & Videos</h2>
            <div class="content">
                <div class="box">Photo Gallery</div>
                <div class="box">Video Collection</div>
            </div>
        </div>
        <div class="section" id="tutor-post">
            <h2>Tutor Post</h2>
            <p>Posts from tutors to guide you.</p>
        </div>
        <div class="section" id="tutor-video">
            <h2>Tutor Video</h2>
            <p>Video tutorials from experts.</p>
        </div>
        <div class="section" id="advice">
            <h2><a href="#advice">Job Related Advice</a></h2>
            <p>Find guidance on job hunting and career growth.</p>
        </div>
        <div class="section">
            <h2>Life Line Telling</h2>
            <p>Insights and predictions about life paths.</p>
        </div>
        <div class="section">
            <h2>Thousand Business Ideas</h2>
            <p>Explore innovative business ideas to start your journey.</p>
        </div>
    </div>
</body>
</html>
