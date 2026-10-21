<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kashmir Reels 🍁</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { background-color: #000; color: #fff; font-family: sans-serif; overflow: hidden; height: 100vh; }
        
        /* Top Header */
        .header { position: absolute; top: 10px; width: 100%; text-align: center; z-index: 10; font-size: 18px; font-weight: bold; text-shadow: 0 2px 4px rgba(0,0,0,0.8); }
        .header span { color: #ff3b5c; margin: 0 10px; }

        /* Video Feed Area */
        .feed-container { height: 100vh; width: 100vw; display: flex; align-items: center; justify-content: center; position: relative; background: #111; }
        .video-placeholder { text-align: center; }
        .logo-icon { font-size: 80px; margin-bottom: 10px; animation: pulse 1.5s infinite; }
        @keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.1); } 100% { transform: scale(1); } }
        
        /* Right Side Actions (Like, Comment, Share) */
        .right-actions { position: absolute; right: 15px; bottom: 80px; display: flex; flex-direction: column; align-items: center; gap: 20px; z-index: 10; }
        .action-btn { background: rgba(0,0,0,0.4); border: none; color: white; width: 45px; height: 45px; border-radius: 50%; font-size: 20px; display: flex; align-items: center; justify-content: center; cursor: pointer; }

        /* Bottom Navigation Bar */
        .bottom-nav { position: absolute; bottom: 0; width: 100%; height: 60px; background-color: #000; display: flex; justify-content: space-around; align-items: center; border-top: 1px solid #222; z-index: 10; }
        .nav-item { color: #888; font-size: 14px; background: none; border: none; cursor: pointer; text-align: center; }
        .nav-item.active { color: #fff; font-weight: bold; }
        .upload-btn { background: #fff; color: #000; width: 40px; height: 25px; border-radius: 6px; font-weight: bold; font-size: 18px; border: none; display: flex; align-items: center; justify-content: center; }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        Following | <span style="color:#fff;">For You</span> 🍁
    </div>

    <!-- Main Video Feed -->
    <div class="feed-container">
        <div class="video-placeholder">
            <div class="logo-icon">🍁</div>
            <h2>Kashmir Reels</h2>
            <p style="color: #aaa; font-size: 14px; margin-top: 5px;">Swipe up/down for next video</p>
        </div>

        <!-- Right Side Buttons -->
        <div class="right-actions">
            <button class="action-btn" onclick="alert('Liked!')">❤️</button>
            <button class="action-btn" onclick="alert('Comments section')">💬</button>
            <button class="action-btn" onclick="alert('Share link copied!')">↗️</button>
        </div>
    </div>

    <!-- Bottom Navigation Bar -->
    <div class="bottom-nav">
        <button class="nav-item active" onclick="alert('Search Page')">🔍 Search</button>
        <button class="upload-btn" onclick="alert('Upload Video Camera')">+</button>
        <button class="nav-item" onclick="alert('User Profile')">👤 Profile</button>
    </div>

</body>
</html>
