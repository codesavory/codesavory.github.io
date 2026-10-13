---
layout: null
permalink: /index.html
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>codesavory moved to codesavory.dev</title>
  <meta http-equiv="refresh" content="0; url=https://codesavory.dev/" />
  <link rel="canonical" href="https://codesavory.dev/" />
  <meta name="robots" content="noindex" />
  <style>
    body { font-family: system-ui, sans-serif; max-width: 480px; margin: 8rem auto; padding: 0 1.5rem; color: #1a1815; line-height: 1.55; }
    a { color: #6a8f6e; }
    @media (prefers-color-scheme: dark) { body { background: #0e0d0b; color: #f0ebe3; } a { color: #8ab870; } }
  </style>
  <script>
    // Old project pages map to their new homes. Anything else goes to the root.
    (function () {
      var play = ["csvad", "houdini", "houdiniClothSimulation", "houdiniInfectionSystem", "rippleBubbles", "endlessBlossom"];
      var work = ["imageimate", "pathtracer", "raster", "raytracer", "realistic_3d_avatar", "realtime_relighting"];
      var target = "https://codesavory.dev/";
      try {
        var name = window.location.pathname.split("/").filter(Boolean).pop() || "";
        name = name.replace(/\.html$/, "");
        if (play.indexOf(name) > -1) target = "https://codesavory.dev/play";
        else if (work.indexOf(name) > -1) target = "https://codesavory.dev/work";
      } catch (e) {}
      window.location.replace(target);
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
