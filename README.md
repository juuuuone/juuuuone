<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Top Languages</title>
</head>
<body>
    <svg
        width="300"
        height="285"
        viewBox="0 0 300 285"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
    >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            .header { font-size: 15.5px; }
          }

          @keyframes slideInAnimation {
            from {
              width: 0;
            }
            to {
              width: calc(100%-100px);
            }
          }
          @keyframes growWidthAnimation {
            from {
              width: 0;
            }
            to {
              width: 100%;
            }
          }
          .stat {
            font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
          }
          @supports(-moz-appearance: auto) {
            .stat { font-size:12px; }
          }
          .bold { font-weight: 700 }
          .lang-name {
            font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
            fill: #434d58;
          }
          .stagger {
            opacity: 0;
            animation: fadeInAnimation 0.3s ease-in-out forwards;
          }
          #rect-mask rect{
            animation: slideInAnimation 1s ease-in-out forwards;
          }
          .lang-progress{
            animation: growWidthAnimation 0.6s ease-in-out forwards;
          }

          @keyframes scaleInAnimation {
            from {
              transform: translate(-5px, 5px) scale(0);
            }
            to {
              transform: translate(-5px, 5px) scale(1);
            }
          }
          @keyframes fadeInAnimation {
            from {
              opacity: 0;
            }
            to {
              opacity: 1;
            }
          }
        </style>

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="299"
          fill="#fffefe"
          stroke-opacity="1"
        />

        <g
          data-testid="card-title"
          transform="translate(25, 35)"
        >
          <g transform="translate(0, 0)">
            <text
              x="0"
              y="0"
              class="header"
              data-testid="header"
            >Most Used Languages</text>
          </g>
        </g>

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          <svg data-testid="lang-items" x="25">
            <g transform="translate(0, 0)">
              <g class="stagger" style="animation-delay: 450ms">
                <text data-testid="lang-name" x="2" y="15" class="lang-name">Kotlin</text>
                <text x="215" y="34" class="lang-name">94.08%</text>

                <svg width="205" x="0" y="25">
                  <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                  <svg data-testid="lang-progress" width="94.08%">
                    <rect
                        height="8"
                        fill="#A97BFF"
                        rx="5" ry="5" x="0" y="0"
                        class="lang-progress"
                        style="animation-delay: 750ms;"
                    />
                  </svg>
                </svg>
              </g>
            </g>
            <g transform="translate(0, 40)">
              <g class="stagger" style="animation-delay: 600ms">
                <text data-testid="lang-name" x="2" y="15" class="lang-name">JavaScript</text>
                <text x="215" y="34" class="lang-name">2.39%</text>

                <svg width="205" x="0" y="25">
                  <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                  <svg data-testid="lang-progress" width="2.39%">
                    <rect
                        height="8"
                        fill="#f1e05a"
                        rx="5" ry="5" x="0" y="0"
                        class="lang-progress"
                        style="animation-delay: 900ms;"
                    />
                  </svg>
                </svg>
              </g>
            </g>
            <g transform="translate(0, 80)">
              <g class="stagger" style="animation-delay: 750ms">
                <text data-testid="lang-name" x="2" y="15" class="lang-name">HTML</text>
                <text x="215" y="34" class="lang-name">2.38%</text>

                <svg width="205" x="0" y="25">
                  <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                  <svg data-testid="lang-progress" width="2%">

                    <rect
                        height="8"
                        fill="#e34c26"
                        rx="5" ry="5" x="0" y="0"
                        class="lang-progress"
                        style="animation-delay: 1050ms;"
                    />
                  </svg>
                </svg>
              </g>
            </g>
            <g transform="translate(0, 120)">
              <g class="stagger" style="animation-delay: 900ms">
                <text data-testid="lang-name" x="2" y="15" class="lang-name">CSS</text>
                <text x="215" y="34" class="lang-name">1.32%</text>

                <svg width="205" x="0" y="25">
                  <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                  <svg data-testid="lang-progress" width="2%">
                    <rect
                        height="8"
                        fill="#663399"
                        rx="5" ry="5" x="0" y="0"
                        class="lang-progress"
                        style="animation-delay: 1200ms;"
                    />
                  </svg>
                </svg>
              </g>
            </g>
            <g transform="translate(0, 160)">
              <g class="stagger" style="animation-delay: 1050ms">
                <text data-testid="lang-name" x="2" y="15" class="lang-name">Java</text>
                <text x="215" y="34" class="lang-name">0.36%</text>

                <svg width="205" x="0" y="25">
                  <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                  <svg data-testid="lang-progress" width="2%">
                    <rect
                        height="8"
                        fill="#b07219"
                        rx="5" ry="5" x="0" y="0"
                        class="lang-progress"
                        style="animation-delay: 1350ms;"
                    />
                  </svg>
                </svg>
              </g>
            </g>
          </svg>
        </g>
    </svg>
</body>
</html>
