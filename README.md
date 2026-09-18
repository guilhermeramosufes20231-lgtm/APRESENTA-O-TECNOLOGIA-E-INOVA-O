<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Crescer sem perder o sentido - Projeto CRIA</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Sora:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #F3F5FC;
      --superfície: #FFFFFF;
      --superfície-2: #F8F9FE;
      --tinta: #151A3D;
      --silenciado: #4F557C;
      --azul: #3352D0;
      --violeta: #6748FF;
      --ice: #ECEFFF;
      --verde: #B2D1B0;
      --grad: linear-gradient(135deg, #3352D0 0%, #6F45E6 100%);
      --sombra: 0 1px 2px rgba(21,26,61,.06), 0 16px 34px -16px rgba(51,82,208,.30);
      --ponto: #6F45E6;
      --blob1: rgba(81,82,208,.13);
      --blob2: rgba(110,69,230,.13);
      --ink: #151A3D;
    }

    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #121640;
        --superfície: #1B2158;
        --superfície-2: #171C4E;
        --tinta: #F3F4FF;
        --silenciado: #B4B9E4;
        --azul: #8AA3FF;
        --violeta: #A6B0FF;
        --ice: #252C72;
        --grad: linear-gradient(135deg, #4A6BF0 0%, #8557F0 100%);
        --sombra: 0 1px 2px rgba(0,0,0,.25), 0 16px 34px -16px rgba(0,0,0,.6);
        --ponto: #B9A6FF;
        --blob1: rgba(74,107,240,.30);
        --blob2: rgba(147,107,240,.26);
        --ink: #F3F4FF;
      }
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html,
    body {
      height: 100%;
      background: var(--bg);
      overflow: hidden;
    }

    body {
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
      color: var(--tinta);
    }

    button {
      font-family: inherit;
    }

    #stage {
      position: absolute;
      left: 50%;
      top: 50%;
      width: 1600px;
      height: 900px;
      margin: -450px 0 0 -800px;
      transform: scale(var(--scale, 1));
      transform-origin: center;
      overflow: hidden;
      background:
        radial-gradient(640px 420px at 96% -6%, var(--blob1), transparent 70%),
        radial-gradient(760px 520px at -6% 106%, var(--blob2), transparent 70%),
        var(--bg);
    }

    .lights span {
      position: absolute;
      border-radius: 50%;
      background: var(--ponto);
      opacity: .55;
      box-shadow: 0 0 22px rgba(111,69,230,.18);
    }

    .top {
      position: absolute;
      left: 64px;
      right: 64px;
      top: 0;
      height: 76px;
      display: flex;
      gap: 12px;
      align-items: center;
      justify-content: space-between;
    }

    .seg {
      flex: 1;
      height: 6px;
      border-radius: 3px;
      background: var(--ice);
      margin-bottom: 9px;
    }

    .seg.on {
      background: var(--grad);
      opacity: .45;
    }

    .seg.cur {
      background: var(--grad);
      box-shadow: 0 0 12px var(--ponto);
    }

    .seg-label {
      font-size: 11px;
      font-weight: 700;
      margin-right: 8px;
      color: var(--silenciado);
    }

    .seg-label.cur {
      color: var(--ink);
    }

    /* restante do HTML original */
  </style>
</head>

<body>
  <div id="stage">
    <!-- conteúdo do projeto -->
  </div>

  <script>
    // JavaScript do projeto
  </script>
</body>
</html>
```0
