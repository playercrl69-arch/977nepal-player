<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>977 Nepal</title>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/shaka-player/4.7.11/shaka-player.ui.min.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/shaka-player/4.7.11/controls.min.css" crossorigin="anonymous">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    html, body {
      background: #000;
      height: 100%;
      width: 100%;
      overflow: hidden;
      font-family: system-ui, -apple-system, sans-serif;
    }

    .shaka-video-container {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
    }

    video {
      width: 100%;
      height: 100%;
      object-fit: contain;
      background: #000;
    }

    .shaka-spinner-container,
    .shaka-spinner,
    .shaka-spinner-svg {
      display: none !important;
    }

    /* ===============================
       TOP-RIGHT SUBSCRIBE (LIKE FANCode)
       =============================== */
    .subscribe-overlay {
      position: absolute;
      top: 14px;
      right: 14px;
      z-index: 9999;
      background: #ff0000;
      color: #fff;
      padding: 6px 10px;
      border-radius: 4px;
      font-size: 13px;
      font-weight: 800;
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 6px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.6);
    }

    .subscribe-overlay span {
      background: #fff;
      color: #ff0000;
      padding: 2px 6px;
      border-radius: 3px;
      font-size: 11px;
      font-weight: 900;
    }

    .subscribe-overlay:hover {
      opacity: 0.9;
    }

    /* ===============================
       TOP LEFT WATERMARK (MOVED FROM BOTTOM CENTER)
       =============================== */
    .watermark {
      position: absolute;
      top: 20px;
      left: 20px;
      z-index: 9998;
      color: white;
      font-size: 24px;
      font-weight: bold;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.8), 0 0 10px rgba(0, 0, 0, 0.5);
      pointer-events: none;
      white-space: nowrap;
      padding: 5px 15px;
      border-radius: 4px;
      background-color: rgba(0, 0, 0, 0.4);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }

    /* Optional: Add a subtle animation */
    .watermark {
      animation: pulse 3s infinite alternate;
    }

    @keyframes pulse {
      0% { opacity: 0.8; }
      100% { opacity: 1; }
    }

    @media (max-width: 600px) {
      .subscribe-overlay {
        top: 10px;
        right: 10px;
        font-size: 12px;
      }
      
      .watermark {
        font-size: 18px;
        top: 10px;
        left: 10px;
        padding: 4px 10px;
      }
    }
  </style>
</head>

<body>

  <div class="shaka-video-container" data-shaka-player>
    <video autoplay playsinline preload="metadata"
      poster="https://media.crictracker.com/media/featureimage/2021/09/Fan-Code.jpg">
    </video>

    <!-- TOP LEFT WATERMARK -->
    <div class="watermark">977 Nepal</div>

    <!-- TOP RIGHT SUBSCRIBE BUTTON -->
    <a
      href="https://www.youtube.com/@977nepalYT?sub_confirmation=1"
      target="_blank"
      class="subscribe-overlay"
    >
      SUBSCRIBE
      <span>LIVE</span>
    </a>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', async () => {
      shaka.polyfill.installAll();

      if (!shaka.Player.isBrowserSupported()) return;

      const video = document.querySelector('video');
      const player = new shaka.Player(video);

      const container = document.querySelector('.shaka-video-container');
      const ui = new shaka.ui.Overlay(player, container, video);

      ui.configure({
        controlPanelElements: [
          'play_pause', 'time_and_duration', 'mute', 'volume',
          'spacer', 'quality', 'fullscreen'
        ]
      });

      player.configure({
        drm: {
          clearKeys: {
            "7e9239c1982d984a002df3ed049d0756":
            "1b8a17598129a3618535c8fb05f103fe"
          }
        },
        streaming: {
          lowLatencyMode: true
        }
      });

      const streamUrl =
        "https://a204aivottepl-a.akamaihd.net/sin-nitro/live/clients/dash/enc/fdb3pubmek/out/v1/aefca6420f944a9482e117f315de535f/cenc.mpd";

      try {
        await player.load(streamUrl);
        video.volume = 0.8;

        try {
          await video.play();
        } catch {
          video.muted = true;
          video.play();
        }
      } catch (e) {
        console.error(e);
      }
    });
  </script>

</body>
</html>
