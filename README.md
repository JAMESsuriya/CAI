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
 const swfobject = {};
    </script>
    <script>
        Object.defineProperty(swfobject, "embedSWF", {
            value: function() {
                var ruffle = window.RufflePlayer.newest();
                var player = ruffle.create_player();
                var container = document.getElementById(arguments[1]);
                container.innerHTML = "";
                container.style.width = arguments[2] + "px";
                container.style.height = arguments[3] + "px";
                player.style.width = container.style.width;
                player.style.height = container.style.height;
                container.appendChild(player);
                player.stream_swf_url(arguments[0]);
            },
            writable: false,
            configurable: false
        });
    </script>
    <!-- End workaround - This code also works if placed before <swfobject.js> -->

    <script src="swfobject.js"></script>

</head>
<body>

<div id="file_div">Flash Player not detected!</div>
<script>
    swfobject.embedSWF("mig29.swf", "file_div", "550", "400", "8");
</script>

</body>
</html>
