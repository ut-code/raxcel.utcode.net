<svelte:head>
  <title>Raxcel</title>
  <meta name="description" content="Raxcel - ラクなエクセル、ラクセル" />
</svelte:head>

<div
  class="min-h-screen bg-linear-to-br from-blue-500 via-purple-600 to-blue-700"
>
  <!-- Navigation -->
  <div class="navbar bg-base-100/10 backdrop-blur-md fixed top-0 z-50">
    <div class="navbar-start">
      <a class="btn btn-ghost text-xl font-bold text-white" href="/">Raxcel</a>
    </div>
    <div class="navbar-end">
      <a class="btn btn-ghost text-white hover:text-blue-200" href="#features"
        >機能</a
      >
      <a class="btn btn-primary ml-2" href="#download">ダウンロード</a>
    </div>
  </div>

  <!-- Hero Section -->
  <div class="hero min-h-screen pt-16">
    <div class="hero-content text-center text-white">
      <div class="max-w-4xl">
        <h1
          class="text-6xl md:text-7xl font-bold mb-6 bg-linear-to-r from-white to-blue-100 bg-clip-text text-transparent drop-shadow-2xl"
        >
          Raxcel
        </h1>

        <p class="text-2xl md:text-3xl mb-4 font-light">
          <span class="font-semibold text-blue-200">楽</span
          >ラクなエクセル、ラクセル
        </p>

        <div id="download">
          <a
            href="/"
            class="btn btn-primary btn-lg text-lg px-8 py-4 shadow-2xl hover:shadow-blue-500/25 transition-all duration-300 hover:scale-105"
          >
            <svg
              class="w-6 h-6 mr-2"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
              ></path>
            </svg>
            Windows版をダウンロード
          </a>
          <p class="text-sm mt-3 opacity-75">
            最新バージョンはGitHubリリースで入手可能
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Features Section -->
  <div class="py-20 bg-base-100" id="features">
    <div class="container mx-auto px-4">
      <div class="text-center mb-16">
        <h2
          class="text-4xl md:text-5xl font-bold mb-4 bg-linear-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent"
        >
          強力な機能
        </h2>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">
          最先端のツールと直感的なデザインで、スプレッドシートアプリケーションの未来を体験してください
        </p>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 max-w-6xl mx-auto">
        <!-- Feature 1: AI Chat with Spreadsheet Context -->
        <div
          class="card bg-linear-to-br from-purple-50 to-pink-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
        >
          <div class="card-body items-center text-center">
            <div
              class="w-16 h-16 bg-purple-500 rounded-full flex items-center justify-center mb-4"
            >
              <svg
                class="w-8 h-8 text-white"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
                ></path>
              </svg>
            </div>
            <h3 class="card-title text-2xl text-gray-800 mb-3">
              AIチャット＆分析
            </h3>
            <p class="text-gray-600 leading-relaxed">
              スプレッドシートデータについてAIと直接チャットできます。自然言語を使って質問し、洞察を得て、タスクを自動化します。
            </p>
          </div>
        </div>

        <!-- Feature 2: Import & Export XLSX -->
        <div
          class="card bg-linear-to-br from-blue-50 to-indigo-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
        >
          <div class="card-body items-center text-center">
            <div
              class="w-16 h-16 bg-blue-500 rounded-full flex items-center justify-center mb-4"
            >
              <svg
                class="w-8 h-8 text-white"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M8 7V3m8 4V3m-4 18h4m-4-13H7M3 11V7a2 2 0 012-2h14a2 2 0 012 2v10a2 2 0 01-2 2h-3m-4-3V7"
                ></path>
              </svg>
            </div>
            <h3 class="card-title text-2xl text-gray-800 mb-3">XLSX互換性</h3>
            <p class="text-gray-600 leading-relaxed">
              XLSX形式でデータをシームレスにインポートおよびエクスポートでき、他のスプレッドシートアプリケーションとの互換性を確保します。
            </p>
          </div>
        </div>

        <!-- Feature 3: Dynamic Charts -->
        <div
          class="card bg-linear-to-br from-green-50 to-emerald-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
        >
          <div class="card-body items-center text-center">
            <div
              class="w-16 h-16 bg-green-500 rounded-full flex items-center justify-center mb-4"
            >
              <svg
                class="w-8 h-8 text-white"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
                ></path>
              </svg>
            </div>
            <h3 class="card-title text-2xl text-gray-800 mb-3">
              直感的なグラフ作成
            </h3>
            <p class="text-gray-600 leading-relaxed">
              データを視覚化し、傾向を明らかにするために、さまざまな動的でインタラクティブなグラフを簡単に作成できます。
            </p>
          </div>
        </div>

        <!-- Feature 4: Built-in Functions -->
        <div
          class="card bg-linear-to-br from-yellow-50 to-orange-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
        >
          <div class="card-body items-center text-center">
            <div
              class="w-16 h-16 bg-orange-500 rounded-full flex items-center justify-center mb-4"
            >
              <svg
                class="w-8 h-8 text-white"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"
                ></path>
              </svg>
            </div>
            <h3 class="card-title text-2xl text-gray-800 mb-3">
              強力な組み込み関数
            </h3>
            <p class="text-gray-600 leading-relaxed">
              複雑な計算、データ操作、統計分析のための包括的な組み込み関数セットを活用してください。
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer footer-center p-10 bg-base-200 text-base-content">
    <div class="flex gap-8 items-center">
      <!-- GitHub Link -->
      <a
        href="https://github.com/ut-code/Raxcel"
        target="_blank"
        rel="noopener noreferrer"
        class="hover:opacity-70 transition-opacity"
        aria-label="GitHub Repository"
      >
        <svg class="w-10 h-10" fill="currentColor" viewBox="0 0 24 24">
          <path
            d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
          ></path>
        </svg>
      </a>

      <!-- ut.code() Link -->
      <a
        href="https://utcode.net"
        target="_blank"
        rel="noopener noreferrer"
        class="hover:opacity-70 transition-opacity"
        aria-label="ut.code() Website"
      >
        <svg
          width="100%"
          height="100%"
          viewBox="0 0 1000 1000"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          xml:space="preserve"
          class="w-10 h-10"
          style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;"
          ><g
            ><path
              d="M890.745,946.777c0,29.395 -23.828,53.223 -53.223,53.223l-536.499,-0c-29.392,-0 -53.221,-23.828 -53.221,-53.223l0,-384.28c0,-29.396 -23.828,-53.224 -53.22,-53.224l-32.108,0c-29.393,0 -53.219,-23.828 -53.219,-53.211l-0,-402.842c-0,-14.115 5.606,-27.651 15.587,-37.633c9.981,-9.98 23.517,-15.587 37.632,-15.587l675.048,-0c14.116,-0 27.663,5.607 37.635,15.587c9.984,9.982 15.588,23.518 15.588,37.633l0,893.557Z"
              style="fill:#303030;"
            /><g
              ><path
                d="M674.79,915.838c39.93,0.039 79.861,0.233 119.791,-0.007c8.379,-0.158 15.883,-7.261 16.047,-16.049c0.053,-8.727 0.055,-17.454 0,-26.181c-0.159,-8.432 -7.392,-15.983 -16.261,-16.04l-29.477,0l-0,-7.732c9.932,-0 19.865,-0.062 29.798,0.001c12.399,0.236 23.431,10.938 23.673,23.673c0.054,8.697 0.001,17.393 0.001,26.09c-0.076,12.538 -10.837,23.892 -23.972,23.972l-119.592,-0l20.481,13.611l-4.281,6.44l-31.14,-20.698c-1.518,-1.077 -1.427,-1.552 -1.611,-2.278c-0.39,-1.56 0.015,-3.03 1.611,-4.162l31.14,-20.698c1.427,2.147 2.854,4.293 4.281,6.44l-20.489,13.618Z"
                style="fill:#fff;"
              /></g
            ><g
              ><path
                d="M253.836,294.263l0,-166.728l36.79,-0l-0,183.401c-0,13.169 0.362,22.562 1.087,28.181c0.725,5.617 1.993,9.937 3.806,12.957c3.866,7.128 9.454,12.505 16.763,16.129c7.309,3.625 21.109,5.438 31.499,5.438c10.511,-0 24.34,-1.813 31.589,-5.438c7.249,-3.624 12.868,-9.001 16.854,-16.129c1.812,-3.02 3.081,-7.309 3.806,-12.866c0.724,-5.558 1.088,-14.861 1.088,-27.91l-0,-183.763l36.607,-0l-0,166.728c-0,27.668 -1.721,47.331 -5.165,58.989c-3.443,11.66 -9.394,21.294 -17.85,28.907c-7.975,7.128 -17.096,12.443 -27.366,15.947c-10.269,3.505 -26.756,5.256 -39.563,5.256c-12.687,0 -29.112,-1.751 -39.382,-5.256c-10.269,-3.504 -19.452,-8.819 -27.546,-15.947c-8.337,-7.492 -14.257,-17.187 -17.761,-29.088c-3.504,-11.9 -5.256,-31.503 -5.256,-58.808Z"
                style="fill:#fff;fill-rule:nonzero;"
              /></g
            ><g
              ><path
                d="M551.366,127.535l206.417,-0l0,30.807l-84.633,0l0,239.764l-36.789,-0l-0,-239.764l-84.995,0l-0,-30.807Z"
                style="fill:#fff;fill-rule:nonzero;"
              /></g
            ><g
              ><rect
                x="369.932"
                y="716.782"
                width="63.792"
                height="73.216"
                style="fill:#fff;"
              /></g
            ><g
              ><path
                d="M745.392,775.139c-9.302,4.953 -18.853,8.668 -28.63,11.145c-9.789,2.476 -20.177,3.715 -31.177,3.715c-34.673,0 -61.584,-12.263 -80.731,-36.789c-19.159,-24.526 -28.732,-59.02 -28.732,-103.481c-0,-44.22 9.641,-78.683 28.913,-103.391c19.272,-24.707 46.114,-37.06 80.55,-37.06c11,0 21.388,1.238 31.177,3.715c9.777,2.476 19.328,6.192 28.63,11.146l0,37.514c-8.94,-7.371 -18.547,-12.988 -28.811,-16.855c-10.276,-3.866 -20.607,-5.798 -30.996,-5.798c-23.798,-0 -41.621,9.182 -53.458,27.546c-11.837,18.364 -17.756,46.092 -17.756,83.183c0,36.97 5.919,64.637 17.756,83.001c11.837,18.366 29.66,27.548 53.458,27.548c10.638,-0 21.06,-1.934 31.267,-5.8c10.208,-3.865 19.725,-9.484 28.54,-16.854l0,37.515Z"
                style="fill:#fff;fill-rule:nonzero;"
              /></g
            ></g
          ></svg
        >
      </a>
    </div>
  </footer>
</div>
