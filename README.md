body {
  padding: 0;
  margin: 0;
  background-color: #2887e3;
}
.piano-container {
  display: flex;
  position: absolute;
  transform: translate(-50%, -50%);
  left: 50%;
  top: 50%;
  padding: 4em 1em 1em 1em;
  border-radius: 0.62em;
  background-color: #24272e;
  box-shadow: 0 2em 4em rgba(7, 0, 53, 0.25);
}
.white-key {
  width: 4.37em;
  height: 17.5em;
  background-color: #ffffff;
  border-radius: 0 0 0.3em 0.3em;
  border: 2px solid #24272e;
  box-sizing: border-box;
  cursor: pointer;
}
.white-key:hover {
  background-color: #ebebeb;
}
.black-key {
  width: 2.5em;
  height: 10em;
  border-radius: 0 0 0.3em 0.3em;
  box-sizing: border-box;
  position: absolute;
  background-color: #070a0f;
  cursor: pointer;
}
.black-key:hover {
  background-color: #24272e;
}
.black-key:nth-child(1) {
  left: 4em;
}
.black-key:nth-child(2) {
  left: 8.37em;
}
.black-key:nth-child(3) {
  left: 17.12em;
}
.black-key:nth-child(4) {
  left: 21.5em;
}
.black-key:nth-child(5) {
  left: 25.87em;
}
.black-key:nth-child(6) {
  left: 34.62em;
}
.black-key:nth-child(7) {
  left: 39em;
}
.black-key:nth-child(8) {
  left: 47.75em;
}
.black-key:nth-child(9) {
  left: 52.12em;
}
.black-key:nth-child(10) {
  left: 56.5em;
}

@media screen and (max-width: 1000px) {
  .piano-container {
    font-size: 0.7em;
  }
}
@media screen and (max-width: 700px) {
  .piano-container {
    font-size: 0.5em;
  }
}
@media screen and (max-width: 500px) {
  .piano-container {
    font-size: 0.3em;
  }
}

