# StatsDude OAuth bridge

Static pages for login redirects that must be `https` (Instagram Login, later TikTok Web).
Each folder forwards `?code&state` to the dashboard on `http://localhost:3005` in the same
browser; nothing is stored or sent elsewhere. Published with GitHub Pages; the source of
truth lives in `Youtube-supporter-app/tools/oauth-bridge/`.
