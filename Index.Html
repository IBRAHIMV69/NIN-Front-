<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazing Video Page with Ads</title>
    <style>
        /* General Styles */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #1a1a1a;
            color: #fff;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Video Container */
        .video-container {
            width: 100%;
            max-width: 800px;
            margin: auto;
            background: black;
        }

        .video-container iframe {
            width: 100%;
            height: calc(100vw * 9 / 16);
            max-height: 450px;
            border-radius: 8px;
            border: none;
        }

        /* Scrollable Number Navigation */
        .scroll-container {
            display: flex;
            overflow-x: auto;
            white-space: nowrap;
            padding: 10px;
            background: #000;
            border: 1px solid #555;
            scrollbar-width: none;
            -ms-overflow-style: none;
        }

        .scroll-container::-webkit-scrollbar {
            display: none;
        }

        .number {
            padding: 8px 20px;
            background: #333;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            margin: 0 5px;
            flex: 0 0 auto;
        }

        .number.active {
            background: #ffcc00;
            color: black;
        }

        /* Scrollable Video List */
        .video-list {
            max-height: 400px; /* Set a maximum height */
            overflow-y: auto; /* Enable vertical scrolling */
            text-align: left;
            padding: 10px;
            font-size: 15px;
            background: #1a1a1a;
            margin: 20px auto; /* Center the video list with margin */
            width: 100%;
            max-width: 800px; /* Match max width with video container */
            border-radius: 8px; /* Rounded corners */
        }

        .video-item {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px;
            cursor: pointer;
            border-bottom: 1px solid #333; /* Divider */
            transition: background 0.3s; /* Smooth hover transition */
        }

        .video-item img {
            width: 90px; /* Fixed thumbnail width */
            height: 65px; /* Fixed thumbnail height */
            border-radius: 5px;
        }

        .video-item:hover {
            background: #333; /* Highlight on hover */
        }

        .video-item.active {
            background: #333; /* Highlight active video item */
        }

        /* Ad Overlay */
.ad-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.6);
  display: none;
  align-items: center;
  justify-content: center;
  z-index: 9999;
}

/* Common popup container */
.ad-popup {
  position: relative;
  width: 100%;
  max-width: 320px;
  border-radius: 15px;
  text-align: center;
  background: rgba(0, 0, 0, 0.1);
  padding: 10px;
}

/* Image Ad */
.ad-popup img#adImage {
  width: 100%;
  height: auto;
  border-radius: 12px;
  display: block;
}

/* Video Ad (iframe style) */
.ad-popup iframe#adVideo {
  width: 100%;
  height: 280px;
  border: none;
  border-radius: 8px;
  display: block;
  background: #000;
}

/* Close button */
.close-btn {
  position: absolute;
  top: 11px;
  right: 10px;
  background: rgba(0, 0, 0, 0.1);
  color: white;
  border: none;
  font-size: 18px;
  cursor: pointer;
  border-radius: 50%;
  padding: 2px 8px;
  z-index: 2;
}

/* Timer */
#adTimer {
  background: rgba(0, 0, 0, 0.6);
  color: white;
  padding: 6px 12px;
  margin-top: 8px;
  border-radius: 10px;
  font-weight: bold;
}

/* Buttons */
#skipButton,
#visitButton {
  padding: 8px 15px;
  border: none;
  border-radius: 8px;
  border: 1px solid #333;
  cursor: pointer;
  font-weight: bold;
  margin: 5px 5px 0;
}

#skipButton {
  background: #ffcc00;
  color: #000;
  display: none;
}

#visitButton {
  background: #00b300;
  color: white;
  display: none;
}

        /* Ad Container Styles */
        .ad-container {
            position: fixed;
            bottom: 0;
            width: 100%;
            background: #fff;
            border: 1px solid #ccc;
            box-shadow: 0 -2px 8px rgba(0, 0, 0, 0.2);
            padding: 8px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            z-index: 1000;
            display: none; /* Hidden until ad shows */
        }

        .ad-content {
            display: flex;
            align-items: center;
            flex-grow: 1;
            overflow: hidden;
        }

        .app-icon {
            width: 50px; /* Fixed icon size */
            height: 50px; /* Fixed icon size */
            border-radius: 12px;
            overflow: hidden;
            margin-right: 10px;
            flex-shrink: 0;
        }

        .app-icon img {
            width: 100%; /* Full width */
            height: 100%; /* Full height */
            object-fit: cover;
        }

        .ad-info {
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }

        .app-name {
            font-weight: bold;
            font-size: 16px;
            color: #333;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            max-width: 200px; /* Limit width to fit */
            margin-bottom: 4px;
        }

        .ad-meta {
            font-size: 14px;
            color: #555; /* Text color */
            white-space: nowrap;
        }

        .install-button {
            background-color: #007bff;
            color: white;
            padding: 8px 14px;
            border: none;
            border-radius: 20px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
            margin-left: 10px;
            flex-shrink: 0;
        }

        .install-button:hover {
            background-color: #0056b3;
        }

        .sponsored {
            font-size: 12px;
            color: #777; /* Color for sponsored text */
            margin-right: 5px;
        }

        .ad-wrapper {
            display: flex;
            align-items: center;
            flex: 1;
            overflow: hidden;
        }

    </style>
</head>
<body>

    <!-- Video Container -->
    <div class="video-container">
        <iframe id="videoPlayer" src="https://www.youtube.com/embed/UHkue_HukXU" allowfullscreen></iframe>
    </div>

    <!-- Scrollable Number Navigation -->
    <div class="scroll-container" id="numberScroll"></div>

    <!-- Video List -->
    <div class="video-list" id="videoList"></div>

    <!-- Ad Overlay -->
    <div class="ad-overlay" id="adOverlay">
  <div class="ad-popup" id="adPopup" onclick="goToAdLink()">
    <button class="close-btn" onclick="closeAd(event)">✖</button>

    <img id="adImage" style="display: none;" />
    <iframe
      id="adIframe"
      allow="autoplay; encrypted-media"
      allowfullscreen
      style="display: none;"
    ></iframe>

    <div id="adTimer">Ad • 5 </div>
    <div style="display: flex; justify-content: center; gap: 10px; margin-top: 10px;">
      <button id="skipButton" onclick="closeAd(event)">Skip Ad</button>
      <button id="visitButton" onclick="visitAd(event)" style="display: none;">Visit Ad</button>
    </div>
  </div>
</div>

    <!-- Ad Container -->
    <div class="ad-container" id="adContainer">
        <div class="ad-wrapper">
            <div class="ad-content" id="adContent"></div>
        </div>
        <a href="#" id="installButton" class="install-button" target="_blank">Install</a>
    </div>

    <script>
        // Function to show or hide the ad container based on the scroll position
        function handleScroll() {
            const videoList = document.getElementById('videoList');
            const adContainer = document.getElementById('adContainer');

            const isAtBottom = videoList.scrollHeight - videoList.scrollTop === videoList.clientHeight;

            if (isAtBottom) {
                adContainer.style.display = 'none'; // Hide ad container when scrolled to bottom
            } else {
                adContainer.style.display = 'flex'; // Show ad container when not at bottom
            }
        }

        // Add event listener to handle scroll on the video list
        document.getElementById('videoList').addEventListener('scroll', handleScroll);

        // App data for ads
        const apps = [
            {
                name: "Cheelee: Short Videos f...",
                icon: "https://tinylink.info/119AL",
                rating: "4.5",
                link: "https://tinylink.info/119Aa"
            },
            {
                name: "CoolApp",
                icon: "https://tinylink.info/119A0",
                rating: "4.8",
                link: "https://tinylink.info/YchD"
            },
            {
                name: "Z League: Mini Games & Friends",
                icon: "https://tinylink.info/Ycg4",
                rating: "4.0",
                link: "https://tinylink.info/119yG"
            }
            // You can add unlimited apps here
        ];

        const adContainer = document.getElementById('adContainer');
        const adContent = document.getElementById('adContent');
        const installButton = document.getElementById('installButton');

        // Load saved index
        let currentAdIndex = parseInt(localStorage.getItem('currentAdIndex')) || 0;

        function showAd(index) {
            const app = apps[index];
            adContent.innerHTML = `
                <div class="app-icon">
                    <img src="${app.icon}" alt="App Icon">
                </div>
                <div class="ad-info">
                    <div class="app-name">${app.name}</div>
                    <div class="ad-meta">
                        <span class="sponsored">Sponsored ·</span>
                        <span>${app.rating} ★ FREE</span>
                    </div>
                </div>
            `;
            installButton.href = app.link;
            adContainer.style.display = 'flex';

            // Save the current index for next time
            localStorage.setItem('currentAdIndex', index);
        }

        function rotateAds() {
            showAd(currentAdIndex);
            currentAdIndex = (currentAdIndex + 1) % apps.length;
        }

        // Show ad immediately and start rotating
        rotateAds();
        setInterval(rotateAds, 15000); // Rotate every 15 seconds

        // Ad Overlay
        const ads = [
  {
    type: "image",
    image: "https://bit.ly/4gHMJHL",
    link: "https://true-click.pro/a/44J1UBOggfxOkx"
  },
  {
    type: "image",
    image: "https://bit.ly/49TAXap",
    link: "https://true-click.pro/a/44J1UBOggfxOkx"
  },
  {
    type: "youtube",
    youtube: "https://www.youtube.com/embed/UHkue_HukXU?autoplay=1&mute=0&enablejsapi=1",
    link: "https://true-click.pro/a/44J1UBOggfxOkx"
  }
];

let currentOverlayAdIndex = localStorage.getItem('currentAdIndex') ? parseInt(localStorage.getItem('currentAdIndex')) : 0;
const popupInterval = 3000000;
const skipDelay = 15;

function showOverlayAd() {
  const ad = ads[currentOverlayAdIndex];
  const adOverlay = document.getElementById("adOverlay");
  const adImage = document.getElementById("adImage");
  const adIframe = document.getElementById("adIframe");
  const timerText = document.getElementById("adTimer");
  const skipBtn = document.getElementById("skipButton");
  const visitBtn = document.getElementById("visitButton");

  adOverlay.style.display = "flex";
  adImage.style.display = "none";
  adIframe.style.display = "none";
  skipBtn.style.display = "none";
  visitBtn.style.display = "none";

  if (ad.type === "image") {
    adImage.src = ad.image;
    adImage.style.display = "block";
  } else if (ad.type === "youtube") {
    adIframe.src = ad.youtube;
    adIframe.style.display = "block";
    visitBtn.style.display = "inline-block"; // Show visit only for video
  }

  let secondsLeft = skipDelay;
  timerText.textContent = `Ad • ${secondsLeft} seconds`;

  const timer = setInterval(() => {
    secondsLeft--;
    timerText.textContent = `Ad • ${secondsLeft} seconds`;

    if (secondsLeft <= 0) {
      skipBtn.style.display = "inline-block";
      clearInterval(timer);
    }
  }, 1000);

  currentOverlayAdIndex = (currentOverlayAdIndex + 1) % ads.length;
  localStorage.setItem("currentAdIndex", currentOverlayAdIndex);
}

function closeAd(e) {
  e.stopPropagation();
  document.getElementById("adOverlay").style.display = "none";
  document.getElementById("adIframe").src = "";
}

function visitAd(e) {
  e.stopPropagation();
  const index = (currentOverlayAdIndex - 1 + ads.length) % ads.length;
  window.open(ads[index].link, "_blank");
}

function goToAdLink() {
  const index = (currentOverlayAdIndex - 1 + ads.length) % ads.length;
  window.open(ads[index].link, "_blank");
}

showOverlayAd();
setInterval(showOverlayAd, popupInterval);

        // Video Data (Simulated YouTube Links with unlimited videos per season)
        const videoData = {
            4: [
                { title: "GIDAN SARAUTA EPISODE 1", thumb: "https://img.youtube.com/vi/Ob4i4n-KdyU/sddefault.jpg", id: "Ob4i4n-KdyU" },
                { title: "GIDAN SARAUTA EPISODE 2", thumb: "https://img.youtube.com/vi/9i1O2DDtSo4/0.jpg", id: "9i1O2DDtSo4" },
                { title: "GIDAN SARAUTA EPISODE 3", thumb: "https://img.youtube.com/vi/UHkue_HukXU/0.jpg", id: "UHkue_HukXU" }
            ],
            3: [
                { title: "GIDAN SARAUTA EPISODE 1", thumb: "https://img.youtube.com/vi/UE4LjZE-iB0/sddefault.jpg", id: "UE4LjZE-iB0" },
                { title: "GIDAN SARAUTA EPISODE 2", thumb: "https://img.youtube.com/vi/UfGQeTc6axk/0.jpg", id: "UfGQeTc6axk" },
                { title: "GIDAN SARAUTA EPISODE 3", thumb: "https://img.youtube.com/vi/q_oi5_Rltq0/0.jpg", id: "q_oi5_Rltq0" },
                { title: "GIDAN SARAUTA EPISODE 4", thumb: "https://img.youtube.com/vi/z2l2H660P-M/sddefault.jpg", id: "z2l2H660P-M" },
                { title: "GIDAN SARAUTA EPISODE 5", thumb: "https://img.youtube.com/vi/IEi13sUnaR8/0.jpg", id: "IEi13sUnaR8" },
                { title: "GIDAN SARAUTA EPISODE 6", thumb: "https://img.youtube.com/vi/J_0zQYG358A/0.jpg", id: "J_0zQYG358A" },
                { title: "GIDAN SARAUTA EPISODE 7", thumb: "https://img.youtube.com/vi/HODFZKMJSdw/sddefault.jpg", id: "HODFZKMJSdw" },
                { title: "GIDAN SARAUTA EPISODE 8", thumb: "https://img.youtube.com/vi/Ej20279ZJgM/0.jpg", id: "Ej20279ZJgM" },
                { title: "GIDAN SARAUTA EPISODE 9", thumb: "https://img.youtube.com/vi/dr50YgSPq88/0.jpg", id: "dr50YgSPq88" },
                { title: "GIDAN SARAUTA EPISODE 10", thumb: "https://img.youtube.com/vi/FXP0rOhdvc0/sddefault.jpg", id: "FXP0rOhdvc0" },
                { title: "GIDAN SARAUTA EPISODE 11", thumb: "https://img.youtube.com/vi/6Xp2aS9EutQ/0.jpg", id: "6Xp2aS9EutQ" },
                { title: "GIDAN SARAUTA EPISODE 12", thumb: "https://img.youtube.com/vi/rJ7bHQTAHdY/0.jpg", id: "rJ7bHQTAHdY" },
                { title: "GIDAN SARAUTA EPISODE 13", thumb: "https://img.youtube.com/vi/_ZvO6ZQnmcw/0.jpg", id: "_ZvO6ZQnmcw" }
            ],
            2: [
                { title: "GIDAN SARAUTA EPISODE 1", thumb: "https://img.youtube.com/vi/o_mN6ryMRaI/sddefault.jpg", id: "o_mN6ryMRaI" },
                { title: "GIDAN SARAUTA EPISODE 2", thumb: "https://img.youtube.com/vi/zCuLHpBwrhw/sddefault.jpg", id: "zCuLHpBwrhw" },
                { title: "GIDAN SARAUTA EPISODE 3", thumb: "https://img.youtube.com/vi/z70mri8gupE/sddefault.jpg", id: "z70mri8gupE" },
                { title: "GIDAN SARAUTA EPISODE 4", thumb: "https://img.youtube.com/vi/Uj1rpn48SGo/sddefault.jpg", id: "Uj1rpn48SGo" },
                { title: "GIDAN SARAUTA EPISODE 5", thumb: "https://img.youtube.com/vi/0rLC5HPvfTM/sddefault.jpg", id: "0rLC5HPvfTM" },
                { title: "GIDAN SARAUTA EPISODE 6", thumb: "https://img.youtube.com/vi/6Zldxbkbmw0/sddefault.jpg", id: "6Zldxbkbmw0" },
                { title: "GIDAN SARAUTA EPISODE 7", thumb: "https://img.youtube.com/vi/7LovUmyLCTA/sddefault.jpg", id: "7LovUmyLCTA" },
                { title: "GIDAN SARAUTA EPISODE 8", thumb: "https://img.youtube.com/vi/XxeEYlUdoEs/sddefault.jpg", id: "XxeEYlUdoEs" },
                { title: "GIDAN SARAUTA EPISODE 9", thumb: "https://img.youtube.com/vi/zHW6mUMzyok/sddefault.jpg", id: "zHW6mUMzyok" },
                { title: "GIDAN SARAUTA EPISODE 10", thumb: "https://img.youtube.com/vi/gMtdGqRikTM/sddefault.jpg", id: "gMtdGqRikTM" },
                { title: "GIDAN SARAUTA EPISODE 11", thumb: "https://img.youtube.com/vi/KREgvjyAnCw/sddefault.jpg", id: "KREgvjyAnCw" },
                { title: "GIDAN SARAUTA EPISODE 12", thumb: "https://img.youtube.com/vi/n7894aGx1g8/sddefault.jpg", id: "n7894aGx1g8" },
                { title: "GIDAN SARAUTA EPISODE 13", thumb: "https://img.youtube.com/vi/K6NSRPd3xr4/sddefault.jpg", id: "K6NSRPd3xr4" },
            ],
            1: [
                { title: "GIDAN SARAUTA EPISODE 1", thumb: "https://img.youtube.com/vi/MN4hHqWWpwU/sddefault.jpg", id: "MN4hHqWWpwU" },
                { title: "GIDAN SARAUTA EPISODE 2", thumb: "https://img.youtube.com/vi/fMBf5OemK-0/0.jpg", id: "fMBf5OemK-0" },
                { title: "GIDAN SARAUTA EPISODE 3", thumb: "https://img.youtube.com/vi/mR7X7W7QuGM/0.jpg", id: "mR7X7W7QuGM" },
                { title: "GIDAN SARAUTA EPISODE 4", thumb: "https://img.youtube.com/vi/tPyQz1G_EMw/sddefault.jpg", id: "tPyQz1G_EMw" },
                { title: "GIDAN SARAUTA EPISODE 5", thumb: "https://img.youtube.com/vi/Hey-Y3GWg1I/0.jpg", id: "Hey-Y3GWg1I" },
                { title: "GIDAN SARAUTA EPISODE 6", thumb: "https://img.youtube.com/vi/_gL9-LOzEjY/0.jpg", id: "_gL9-LOzEjY" },
                { title: "GIDAN SARAUTA EPISODE 7", thumb: "https://img.youtube.com/vi/vSDsL2lI_58/sddefault.jpg", id: "vSDsL2lI_58" },
                { title: "GIDAN SARAUTA EPISODE 8", thumb: "https://img.youtube.com/vi/Nl6q0_qSNuc/0.jpg", id: "Nl6q0_qSNuc" },
                { title: "GIDAN SARAUTA EPISODE 9", thumb: "https://img.youtube.com/vi/o5GT4TM_ilU/0.jpg", id: "o5GT4TM_ilU" },
                { title: "GIDAN SARAUTA EPISODE 10", thumb: "https://img.youtube.com/vi/HuquZyylKmc/sddefault.jpg", id: "HuquZyylKmc" },
                { title: "GIDAN SARAUTA EPISODE 11", thumb: "https://img.youtube.com/vi/unb-zU-9fLE/0.jpg", id: "unb-zU-9fLE" },
                { title: "GIDAN SARAUTA EPISODE 12", thumb: "https://img.youtube.com/vi/riMDxMz9JQA/0.jpg", id: "riMDxMz9JQA" }
            ],
        };

        // Dynamically generate season buttons
        function generateSeasonButtons() {
            const numberScroll = document.getElementById("numberScroll");
            for (let season in videoData) {
                const numberButton = document.createElement("div");
                numberButton.classList.add("number");
                numberButton.innerText = `Season ${season}`;
                numberButton.onclick = () => loadVideos(season);
                numberScroll.appendChild(numberButton);
            }
            loadVideos(Object.keys(videoData)[0]);
        }

        // Load videos based on number selection
        function loadVideos(num) {
            const videoList = document.getElementById("videoList");
            videoList.innerHTML = "";
            videoData[num]?.forEach(video => {
                const videoItem = document.createElement("div");
                videoItem.classList.add("video-item");
                videoItem.innerHTML = `<img src="${video.thumb}" alt="Thumbnail"><span>${video.title}</span>`;
                videoItem.onclick = () => playVideo(video.id, videoItem);
                videoList.appendChild(videoItem);
            });

            document.querySelectorAll(".number").forEach(el => el.classList.remove("active"));
            document.querySelectorAll(".number")[Object.keys(videoData).indexOf(num)].classList.add("active");
        }

        // Play video in container and highlight the active video item
        function playVideo(videoId, videoItem) {
            document.getElementById("videoPlayer").src = `https://www.youtube.com/embed/${videoId}`;

            const videoItems = document.querySelectorAll(".video-item");
            videoItems.forEach(item => item.classList.remove("active"));
            videoItem.classList.add("active");
        }

        // Enable horizontal scroll with drag
        function enableScrollDrag(scrollContainer) {
            let isDown = false;
            let startX;
            let scrollLeft;

            scrollContainer.addEventListener("mousedown", (e) => {
                isDown = true;
                startX = e.pageX - scrollContainer.offsetLeft;
                scrollLeft = scrollContainer.scrollLeft;
            });

            scrollContainer.addEventListener("mouseleave", () => isDown = false);
            scrollContainer.addEventListener("mouseup", () => isDown = false);

            scrollContainer.addEventListener("mousemove", (e) => {
                if (!isDown) return;
                e.preventDefault();
                const x = e.pageX - scrollContainer.offsetLeft;
                const walk = (x - startX) * 2; // Scroll-fast
                scrollContainer.scrollLeft = scrollLeft - walk;
            });
        }

        // Enable scrolling for numbers
        enableScrollDrag(document.getElementById("numberScroll"));

        // Load seasons and videos on page load
        window.onload = () => {
            generateSeasonButtons();
            setTimeout(showOverlayAd, firstPopupDelay);
            setInterval(showOverlayAd, popupInterval);
        };
    </script>
</body>
</html>
