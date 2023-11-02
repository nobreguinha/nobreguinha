<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="favicon.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite App</title>
  </head>
  <style>
    rect {
      fill: #e9e9eb;
    }
    a {
      fill: #0079ff;
    }
    text {
      fill: #242424;
      font-size: 18px;
      font-family: '-apple-system', 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell',
        'Fira Sans', 'Droid Sans', 'Helvetica Neue', 'sans-serif';
    }

    .typing-1 {
      opacity: 0;
      animation: fade-in-out 1.5s;
    }

    .msg-1 {
      animation: wait 1.7s, msg-1 0.2s 1.7s;
    }

    .typing-2 {
      opacity: 0;
      animation: wait 2.5s, fade-in-out 1.5s 2.5s;
    }

    .msg-2 {
      animation: wait 4.2s, msg-2 0.2s 4.2s;
    }

    .typing-3 {
      opacity: 0;
      animation: wait 5s, fade-in-out 1.5s 5s;
    }

    .msg-3 {
      animation: wait 6.7s, msg-3 0.2s 6.7s;
    }

    .typing-4 {
      opacity: 0;
      animation: wait 7.5s, fade-in-out 1.5s 7.5s;
    }

    .msg-4 {
      animation: wait 9.2s, msg-4 0.2s 9.2s;
    }

    .typing-5 {
      opacity: 0;
      animation: wait 10s, fade-in-out 1.5s 10s;
    }

    .msg-5 {
      animation: wait 11.7s, msg-5 0.2s 11.7s;
    }

    @keyframes fade-in-out {
      0%,
      100% {
        opacity: 0;
      }
      25%,
      90% {
        opacity: 1;
      }
    }

    @keyframes msg-1 {
      0% {
        opacity: 0;
        transform: translate(10px, 5px);
      }
      100% {
        opacity: 1;
        transform: translate(10px, 0);
      }
    }

    @keyframes msg-2 {
      0% {
        opacity: 0;
        transform: translate(10px, 53px);
      }
      100% {
        opacity: 1;
        transform: translate(10px, 48px);
      }
    }

    @keyframes msg-3 {
      0% {
        opacity: 0;
        transform: translate(10px, 125px);
      }
      100% {
        opacity: 1;
        transform: translate(10px, 120px);
      }
    }

    @keyframes msg-4 {
      0% {
        opacity: 0;
        transform: translate(10px, 197px);
      }
      100% {
        opacity: 1;
        transform: translate(10px, 192px);
      }
    }

    @keyframes msg-5 {
      0% {
        opacity: 0;
        transform: translate(10px, 245px);
      }
      100% {
        opacity: 1;
        transform: translate(10px, 240px);
      }
    }


    @media (prefers-color-scheme: dark) {
      rect {
        fill: palevioletred;
      }
      text {
        fill: #dcdcdc;
      }
      a {
        fill: #0c82f9;
      }
    }
  </style>
  <body>
    <svg width="550" height="400" viewBox="0 0 550 400" fill="none" xmlns="http://www.w3.org/2000/svg">


      <!-- typing 1 -->
      <g transform="translate(10, 0)" class="typing-1">
        <rect x="8.27246" width="69.7276" height="42" rx="20.9774" />
        <circle cx="13.591" cy="33.091" r="7.68185" />
        <circle cx="3.54547" cy="41.9547" r="3.54547" />

        <circle cx="27.4778" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" repeatCount="indefinite" />
        </circle>
        <circle cx="42.8411" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.2s" repeatCount="indefinite" />
        </circle>
        <circle cx="58.2054" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.4s" repeatCount="indefinite" />
        </circle>
      </g>

      <!-- Hi, I'm Artem -->
      <g transform="translate(10, 0)" class="msg-1">
        <rect width="133" height="42" rx="18.0355" />
        <text x="15" y="27">Hi, I'm Nill</text>
      </g>

      <!-- typing 2 -->
    <g transform="translate(10, 48)" class="typing-2">
        <rect x="8.27246" width="69.7276" height="42" rx="20.9774" />
        <circle cx="13.591" cy="33.091" r="7.68185" />
        <circle cx="3.54547" cy="41.9547" r="3.54547" />

        <circle cx="27.4778" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" repeatCount="indefinite" />
        </circle>
        <circle cx="42.8411" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.2s" repeatCount="indefinite" />
        </circle>
        <circle cx="58.2054" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.4s" repeatCount="indefinite" />
        </circle>
      </g>

      <!-- From Istanbul... -->
      <g transform="translate(10, 48)" class="msg-2">
        <rect width="418" height="66.1302" rx="18.0355" />
        <text x="15" y="27">I live in Columbus, Ohio – it’s supposed to be 79° F</text>
      </g>

      <!-- typing 3 -->
      <g transform="translate(10, 120)" class="typing-3">
        <rect x="8.27246" width="69.7276" height="42" rx="20.9774" />
        <circle cx="13.591" cy="33.091" r="7.68185" />
        <circle cx="3.54547" cy="41.9547" r="3.54547" />

        <circle cx="27.4778" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" repeatCount="indefinite" />
        </circle>
        <circle cx="42.8411" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.2s" repeatCount="indefinite" />
        </circle>
        <circle cx="58.2054" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.4s" repeatCount="indefinite" />
        </circle>
      </g>
      oo

      <!-- From Istanbul... -->
      <g transform="translate(10, 120)" class="msg-3">
        <rect width="430" height="66.1302" rx="18.0355" />
        <text x="15" y="27">I’m a product designer. I used to work at GitHub,</text>
        <text x="15" y="50">
        </text>
      </g>

      <!-- typing 4 -->
      <g transform="translate(10, 192)" class="typing-4">
        <rect x="8.27246" width="69.7276" height="42" rx="20.9774" />
        <circle cx="13.591" cy="33.091" r="7.68185" />
        <circle cx="3.54547" cy="41.9547" r="3.54547" />

        <circle cx="27.4778" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" repeatCount="indefinite" />
        </circle>
        <circle cx="42.8411" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.2s" repeatCount="indefinite" />
        </circle>
        <circle cx="58.2054" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.4s" repeatCount="indefinite" />
        </circle>
      </g>

      <!-- LinkedIn -->
      <g transform="translate(10, 192)" class="msg-4">
        <rect width="220" height="42" rx="18.0355" />
        <text x="15" y="27">Thanks for stopping by</text>
      </g>

      <!-- typing 5 -->
      <g transform="translate(10, 240)" class="typing-5">
        <rect x="8.27246" width="69.7276" height="42" rx="20.9774" />
        <circle cx="13.591" cy="33.091" r="7.68185" />
        <circle cx="3.54547" cy="41.9547" r="3.54547" />

        <circle cx="27.4778" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" repeatCount="indefinite" />
        </circle>
        <circle cx="42.8411" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.2s" repeatCount="indefinite" />
        </circle>
        <circle cx="58.2054" cy="20.9773" r="5.02275" fill="#999999">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="1s" begin="0.4s" repeatCount="indefinite" />
        </circle>
      </g>

      <!-- Thanks -->
      <g transform="translate(10, 240)" class="msg-5">
        <rect width="210" height="42" rx="18.0355" />
        <text x="15" y="27">Have a great day! 👋🏻</text>
      </g>

     
    </svg>
  </body>
</html>
![nobreguinha's GitHub stats](https://github-readme-stats.vercel.app/api?username=nobreguinha&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nobreguinha)](https://github.com/zeynabmvs/github-readme-stats)


<!--
**nobreguinha/nobreguinha** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
