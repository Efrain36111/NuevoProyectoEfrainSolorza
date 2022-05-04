<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enciclopedia Coppel</title>
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <nav>
      <ul class="nav-right-section">
        <li>
          <a href="">Enciclopedia Coppel</a>
        </li>
        <li>
          <a href="">Imagenes</a>
        </li>
        <li class="menu-icon">
          <a href=""></a>
        </li>
        <li>
          <a href="">
            <img src="https://seeklogo.com/images/C/coppel-institucional-logo-06C73CD476-seeklogo.com.png" alt="">
          </a>
        </li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="main-logo">
      <img src="https://thumbs.dreamstime.com/z/pila-de-libros-23026923.jpg" alt="">
    </section>
    <section class="main-input">
      <div class="main-input-container">
        <span class="search-icon">
        </span>
        <input type="text">
        <a class="micro-icon" href=""></a>
      </div>
    </section>
  </main>

  <footer>
    <ul class="footer-left">
      <li>
        <a href="">Publicidad</a>
      </li>
      <li>
        <a href="">Enciclopedia</a>
      </li>
      <li>
        <a href="">Cómo funciona la búsqueda</a>
      </li>
    </ul>
    <ul class="footer-right">
      <li>
        <a href="">Privacidad</a>
      </li>
      <li>
        <a href="">Condiciones</a>
      </li>
      <li>
        <a href="">Preferencias</a>
      </li>
    </ul>
  </footer>
  
<!-- Code injected by live-server -->
<script type="text/javascript">
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script></body>
</html>
