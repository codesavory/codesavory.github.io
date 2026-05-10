---
layout: null
permalink: /index.html
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>codesavory — moved to codesavory.dev</title>
  <meta http-equiv="refresh" content="0; url=https://codesavory.dev/" />
  <link rel="canonical" href="https://codesavory.dev/" />
  <meta name="robots" content="noindex" />
  <style>
    body { font-family: system-ui, sans-serif; max-width: 480px; margin: 8rem auto; padding: 0 1.5rem; color: #1a1815; line-height: 1.55; }
    a { color: #6a8f6e; }
    @media (prefers-color-scheme: dark) { body { background: #0e0d0b; color: #f0ebe3; } a { color: #8ab870; } }
  </style>
  <script>
    // Preserve the path/query when redirecting (e.g., /pages/imageimate.html → /work)
    (function () {
      try {
        // Map known old paths to new ones
        var pathMap = {
          "/pages/csvad.html": "/houdini",
          "/pages/houdini.html": "/houdini",
          "/pages/houdiniClothSimulation.html": "/houdini",
          "/pages/houdiniInfectionSystem.html": "/houdini",
          "/pages/rippleBubbles.html": "/houdini",
          "/pages/endlessBlossom.html": "/houdini",
          "/pages/imageimate.html": "/work",
          "/pages/realistic_3d_avatar.html": "/work",
          "/pages/realtime_relighting.html": "/work",
        };
        var path = window.location.pathname;
        var target = "https://codesavory.dev" + (pathMap[path] || "/");
        window.location.replace(target);
      } catch (e) {
        window.location.replace("https://codesavory.dev/");
      }
    })();
  </script>
</head>
<body>
  <h1>This site moved.</h1>
  <p>
    The portfolio is now at <a href="https://codesavory.dev/">codesavory.dev</a>.
    Redirecting&hellip; if you aren&rsquo;t sent automatically,
    <a href="https://codesavory.dev/">follow the link</a>.
  </p>
</body>
</html>
