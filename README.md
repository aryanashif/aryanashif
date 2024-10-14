<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fafafa;
            margin: 0;
            padding: 0;
        }

        .navbar {
            background-color: #fff;
            border-bottom: 1px solid #dbdbdb;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .navbar img {
            width: 120px;
        }

        .navbar input[type="text"] {
            border: 1px solid #dbdbdb;
            padding: 5px;
            border-radius: 3px;
        }

        .navbar .icons {
            display: flex;
            gap: 20px;
        }

        .icons img {
            width: 24px;
            cursor: pointer;
        }

        .container {
            margin-top: 80px;
            display: flex;
            justify-content: center;
        }

        .feed {
            width: 500px;
        }

        .post {
            background-color: #fff;
            border: 1px solid #dbdbdb;
            margin-bottom: 20px;
            border-radius: 5px;
        }

        .post-header, .post-footer {
            padding: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .post-header img {
            border-radius: 50%;
            width: 40px;
            height: 40px;
            margin-right: 10px;
        }

        .post-image img {
            width: 100%;
            display: block;
        }

        .post-footer .icons img {
            width: 24px;
            cursor: pointer;
        }

        .post-footer .like-count {
            font-size: 14px;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Logo">
        <input type="text" placeholder="Search">
        <div class="icons">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Instagram_home_icon.png" alt="Home">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Instagram_messenger_icon.png" alt="Messenger">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/de/Instagram_add_post_icon.png" alt="Add Post">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Instagram_heart_icon.png" alt="Notifications">
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Instagram_profile_icon.png" alt="Profile">
        </div>
    </div>

    <div class="container">
        <div class="feed">
            <!-- Example Post -->
            <div class="post">
                <div class="post-header">
                    <img src="https://via.placeholder.com/40" alt="User">
                    <span>username</span>
                </div>
                <div class="post-image">
                    <img src="https://via.placeholder.com/500x500" alt="Post">
                </div>
                <div class="post-footer">
                    <div class="icons">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/7/70/Instagram_like_icon.png" alt="Like">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Instagram_comment_icon.png" alt="Comment">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/e/eb/Instagram_send_icon.png" alt="Share">
                    </div>
                    <div class="like-count">Liked by user1 and 200 others</div>
                </div>
            </div>

            <!-- More posts can be added similarly -->
        </div>
    </div>
</body>
</html>
