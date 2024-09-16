<html>
  <head>
    <title>Weather Ap</title>
    <style>
      body {
        font-family: Helvetica, Arial, sans-serif;
      }

      .weather {
        max-width: 300px;
        margin: 0 auto;
      }

      h1,
      h2 {
        font-weight: 900;
        font-size: 34px;
        line-height: 48px;
        margin: 0;
      }

      h1 {
        color: blue
        #c5264b;
        text-align: center;
      }

      h2 {
        text-align: center;
        color: #272044;
        font-weight: 400;
      }

      p {
        font-size: 18px;
        opacity: 0.7;
        text-align: center;
        font-family: monospace;
      }

      ul {
        margin: 30px 0;
        padding: 0;
      }

      li {
        list-style: none;
        border-radius: 10px;
        transition: all 200ms ease-in-out;
        text-align: center;
      }

      li:hover {
        background: #fffbef;
      }

      button {
        border-radius: 25px;
        text-align: center;
        display: block;
        margin: 20px auto;
        border: 1px solid #c5264b;
        background: #c5264b;
        color: #fff;
        font-size: 16px;
        line-height: 22px;
        padding: 16px 24px;
        text-decoration: none;
        transition: all 200ms ease;
        box-shadow: rgba(37, 39, 89, 0.08) 0px 8px 8px 0;
      }

      button:hover {
        cursor: pointer;
        background: #881b34;
      }
    </style>
  </head>

  <body>
    <div class="weather">
      <h1>
        🌤<br />
        Today in Pretoria 
      </h1>
      <h2>13° / <strong>23°</strong></h2>
      <ul>
        <li>
          <h3>
            🌧Tomorrow
          </h3>
          <p>10° / <strong>24°</strong></p>
        </li>
        <li>
          <h3>
            🌥 Saturday
          </h3>
          <p>15° / <strong>20°</strong></p>
        </li>
        <li>
          <h3>
            ☀️ Sunday
          </h3>
          <p>25° / <strong>30°</strong></p>
        </li>
      </ul>
      <button>
        Change city
      </button>
      <p>
        Coded by Johannah Mathe     </p>
    </div>
  </body>
</html>
