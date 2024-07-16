<html><head><script src="ruffle/ruffle.js"></script>
</head>
<body>
<script>
    window.RufflePlayer = window.RufflePlayer || {};
    window.addEventListener("load", (event) => {
        const ruffle = window.RufflePlayer.newest();
        const player = ruffle.createPlayer();
        const container = document.getElementById("container");
        container.appendChild(player);
        player.load("mig29.swf");
    });
</script>
<script src="ruffle/ruffle.js"></script>

</body>
</html
