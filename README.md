! Youtube

!#if (!adguard_app_windows && !adguard_app_mac && !adguard_app_android)

www.youtube.com#%#//scriptlet('abort-on-stack-trace', 'btoa', '/[A-Za-z]lb \S+polymer/')

! For the closable popup

youtube.com#?#ytd-enforcement-message-view-model:has(> div.ytd-enforcement-message-view-model)

youtube.com#$#tp-yt-iron-overlay-backdrop { display: none !important; }

youtube.com#$?#tp-yt-paper-dialog:has(> ytd-enforcement-message-view-model > div.ytd-enforcement-message-view-model) { remove: true; }

! For the overlay

youtube.com#$#ytd-watch-flexy[player-unavailable] #player-container-outer.ytd-watch-flexy { visibility: visible !important; }

youtube.com#$?#yt-playability-error-supported-renderers:has(yt-button-view-model[dialog-dismiss]) { display: none !important; }

!#endif