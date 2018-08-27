//META{"name":"ClearVision_Ruby","description":"A raging, red theme with customizable colors & background! Based on Discord Reborn by @Omniscient &DarkMatter by @Hammock. Server: https://discord.me/clearvision","author":"Zerthox","version":"5"}*//{}
/* "ClearVision - Ruby v5" by @Zerthox */
/* Based on "Discord Reborn v4.30" by @Omniscient & "DarkMatter" by @Hammock */

/* IMPORT CSS FROM GITHUB */
@import url(https://zerthox.github.io/ClearVision/css/ClearVision_v5.min.css);

:root {
	--main-color: #e62727;
	--hover-color: #b31e1e;
    --background-blur: 0px;
    --background-brightness: 100%;
}

body::after,
.callout-backdrop,
.userPopout-11hFKo::before,
.userPopout-3XzG_A::before,
.root-SR8cQa::before,
#pubs-container::before,
.auth-background,
.auth-tiling-bg,
.invite-modal .invite-splash,
.radio-theme.light label,
.radio-theme.dark label {
    background-image: url(https://i.imgur.com/U6ZfbgS.jpg) !important; /* IMPORTANT: Link must be HTTPS! */
}
