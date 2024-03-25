# My name is Micha
## I love CSS.

### My hobbies are

- sports
- drawing
- everything around the house and garden 


>I also like listening to music and traveling a lot. I romp around with my daughter and plan projects with my wife

---
### That's me
![me an i!](https://avatars.githubusercontent.com/u/996455?v=4)

---

```html
<html>
  <head></head>
  <body>
    <div class="coffee-cup">
      <div class="vapour">
        <span style="--v: 1"></span>
        <span style="--v: 2"></span>
        <span style="--v: 5"></span>
        <span style="--v: 4"></span>
        <span style="--v: 6"></span>
        <span style="--v: 19"></span>
        <span style="--v: 7"></span>
        <span style="--v: 8"></span>
        <span style="--v: 9"></span>
        <span style="--v: 10"></span>
        <span style="--v: 11"></span>
        <span style="--v: 18"></span>
      </div>
      <div class="cup"></div>
      <div class="handle"></div>
    </div>
  </body>
</html>
```

```CSS 
body {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        margin: 0;
        background: #28292e;
      }

      .coffee-cup {
        width: 150px;
        height: 200px;
        position: relative;
        cursor: pointer;
        display: block;
      }

      .cup {
          border-radius: 0 0 5px 5px;
          width: 150px;
          height: 200px;
          position: absolute;
          bottom: 0;
          background: linear-gradient(
              left,
              rgba(38, 38, 38, 0.8),
              #e6e6e6 25%,
              #ffffff 38%,
              #c5c5c5 63%,
              #f7f7f7 87%,
              rgba(38, 38, 38, 0.8)
          );

          background: -webkit-linear-gradient(
              left,
              rgba(38, 38, 38, 0.7),
              #e6e6e6 25%,
              #ffffff 38%,
              rgba(0, 0, 0, 0.55) 63%,
              #e6e6e6 87%,
              rgba(38, 38, 38, 0.8)
          );
        }

        .cup:before {
          content: '';
          width: 150px;
          height: 10px;
          left: 3px;
          bottom: 0;
          margin: 0;
          z-index: -1;
          position: absolute;
          -moz-border-radius:	 0 0 6px 6px; /* FF1+ */
          -webkit-border-radius:	0 0 6px 6px; /* Saf3+, Chrome */
          border-radius:	0 0 6px 6px; /* Opera 10.5, IE 9 */
          -moz-box-shadow: 0px 5px 6px rgba(0,0,0,.4); /* FF3.5+ */
          -webkit-box-shadow: 0px 5px 6px rgba(0,0,0,.4); /* Saf3.0+, Chrome */
          box-shadow: 0px 5px 6px rgba(0,0,0,.4); /* Opera 10.5, IE 9.0 */
          clip: rect(0 950px 30px -3px);
        }

      .handle {
        position: absolute;
        width: 80px;
        height: 40px;
        rotate: 90deg;
        left: 97%;
        top: 38px;
      }

      .handle::before {
        position: absolute;
        content: "";
        width: inherit;
        height: inherit;
        border: 15px solid rgba(255, 255, 255, 0.2);

        border-bottom: none;
        border-top-left-radius: 75px;
        border-top-right-radius: 175px;
        background: linear-gradient(
          top,
          rgba(38, 38, 38, 1) 100%,
          rgba(0, 0, 0, 0.25) 63%,
          #e6e6e6 87%,
          rgba(38, 38, 38, 0.4)
        ) 100%;

        background: -webkit-linear-gradient(
          top,
          rgba(38, 38, 38, 1) 100%,
          rgba(0, 0, 0, 0.25) 63%,
          #e6e6e6 87%,
          rgba(38, 38, 38, 0.4)
        ) 100%;
      }

      .handle::after {
        position: absolute;
        content: "";
        width: inherit;
        height: inherit;
        border: 15px solid #28292e;
        background: #28292e;
        border-bottom: none;
        border-top-left-radius: 75px;
        border-top-right-radius: 175px;
        width: 55px;
        height: 24px;
        top: 15px;
        left: 13px;
      }

      .vapour {
        position: relative;
        display: flex;
        padding: 0 20px;
        justify-content: center;
        transform: translate3d(0, -40px);
      }

      .vapour span {
        position: relative;
        bottom: 50px;
        display: block;
        margin: 0 2px 50px;
        min-width: 8px;
        height: 120px;
        background: #fff;
        border-radius: 50%;
        animation: animate 5s linear infinite;
        opacity: 0;
        filter: blur(10px);
        animation-delay: calc(var(--v) * -0.5s);
      }

```

```javascript

  console.log(nothing to show!)

```
