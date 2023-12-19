<!-- App.vue -->
<template>
  <nav
    class="navbar fixed-top shadow-sm navbar-expand-lg bg-light navbar-light py-3 py-lg-0 px-lg-5"
  >
    <a href="index.html" class="navbar-brand ml-lg-3">
      <h1 class="m-0 display-5">Jovet<span class="text-dark">Kei</span></h1>
    </a>
    <button
      type="button"
      class="navbar-toggler"
      data-toggle="collapse"
      data-target="#navbarCollapse"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse px-lg-3" id="navbarCollapse">
      <div class="navbar-nav m-auto py-0">
        <a href="#home" class="nav-item nav-link active">Home</a>
        <a href="#about" class="nav-item nav-link">About</a>
        <a href="#qualification" class="nav-item nav-link">Experience</a>
        <a href="#skill" class="nav-item nav-link">Skill</a>
        <a href="#service" class="nav-item nav-link">Service</a>
        <a href="#contact" class="nav-item nav-link">Contact</a>
      </div>
    </div>
  </nav>
  <div
    class="container-fluid d-flex align-items-center mb-5 py-5"
    id="home"
    style="min-height: 100vh"
  >
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-5 px-5 pl-lg-0 pb-5 pb-lg-0">
          <img
            class="img-fluid w-100 rounded-circle shadow-sm"
            src="./assets/img/profile.jpg"
            alt=""
          />
        </div>
        <div class="col-lg-7 text-center text-lg-left">
          <h3 class="text-white font-weight-normal mb-3">I'm</h3>
          <h1
            class="display-3 text-uppercase text-dark mb-2"
            style="-webkit-text-stroke: 2px #ffffff"
          >
            Jovet Quillan
          </h1>
          <h1
            class="typed-text-output d-inline font-weight-lighter text-white"
          ></h1>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="about">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-Dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          About
        </h1>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-5 pb-4 pb-lg-0">
          <img
            class="img-fluid rounded w-100"
            src="./assets/img/about.jpg"
            alt=""
          />
        </div>
        <div class="col-lg-7">
          <h3 class="mb-4">Full Stack Developer</h3>
          <p>
            The Person Who is more handsome Than me Haven't born yet. The More
            girl you get The more you will get lucky so Have more girl.
          </p>
          <div class="row mb-3">
            <div class="col-sm-6 py-2">
              <h6>Name: <span class="text-muted">Jovet Quillan</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Birthday: <span class="text-muted">April 20, 1998</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Degree: <span class="text-muted">Data Analyst</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Experience: <span class="text-muted">12 Decades</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Phone: <span class="text-muted">09519333776</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Email: <span class="text-muted">jovet1st@gmail.com</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>
                Address:
                <span class="text-muted">Camolinas Poblacion Cordova Cebu</span>
              </h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="qualification">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          Experience
        </h1>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-6">
          <h3 class="mb-4">My Education</h3>
          <div class="border-left border-danger pt-2 pl-4 ml-2">
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">Elementary</h5>
              <p class="mb-2">
                <strong>Cordova Elementary School</strong> |
                <small>2007 - 2013</small>
              </p>
              <p>
                The more that you read, the more things you will know. The more
                that you learn, the more places you'll go.
              </p>
            </div>
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">High School</h5>
              <p class="mb-2">
                <strong>Cordova Catholic Cooperative School</strong> |
                <small>2013 - 2020</small>
              </p>
              <p>
                You have brains in your head. You have feet in your shoes. You
                can steer yourself any direction you choose.
              </p>
            </div>
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">College</h5>
              <p class="mb-2">
                <strong>Cordova Public College</strong> |
                <small>2020 - 2024</small>
              </p>
              <p>
                Do not wait; the time will never be 'just right.' Start where
                you stand, and work with whatever tools you may have at your
                command, and better tools will be found as you go along.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <h3 class="mb-4">My Expericence</h3>
          <div class="border-left border-danger pt-2 pl-4 ml-2">
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">Web Designer</h5>
              <p class="mb-2">
                <strong>Practice</strong> | <small>2020 - 2023</small>
              </p>
              <p>
                In the world of web design, your creations are not just pixels
                on a screen; they are gateways to experiences. Every line of
                code, every color choice, and every interaction is an
                opportunity to engage, captivate, and enrich the user's journey.
                Design isn't just about making things look good; it's about
                crafting an immersive narrative that users can navigate with
                ease and delight.
              </p>
            </div>
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">
                Business Logic & Database Logic
              </h5>
              <p class="mb-2">
                <strong>School</strong> | <small>2020 - 2023</small>
              </p>
              <p>
                In the digital age, the heartbeat of business is synchronized
                with the rhythm of database logic. Efficient data management
                isn't just a necessity; it's the strategic pulse that drives
                informed decisions and fuels organizational success.
              </p>
            </div>
            <div class="position-relative mb-4">
              <i
                class="far fa-dot-circle text-danger position-absolute"
                style="top: 2px; left: -32px"
              ></i>
              <h5 class="font-weight-bold mb-1">Full Stack</h5>
              <p class="mb-2">
                <strong>Freelancing</strong> | <small>2020 - 2023</small>
              </p>
              <p>
                A full-stack developer is a creative mind with the strategic
                prowess to architect entire ecosystems, from the user interface
                to the server infrastructure, crafting digital experiences that
                seamlessly connect the dots in the vast landscape of code.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="skill">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          Skills
        </h1>
      </div>
      <div class="row align-items-center">
        <div class="col-12">
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">HTML</h6>
              <h6 class="font-weight-bold">90%</h6>
            </div>
            <div class="progress">
              <div
                class="progress-bar bg-Danger"
                role="progressbar"
                style="width: 90%"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">CSS</h6>
              <h6 class="font-weight-bold">90%</h6>
            </div>
            <div class="progress">
              <div
                class="progress-bar bg-Danger"
                role="progressbar"
                style="width: 90%"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">PHP</h6>
              <h6 class="font-weight-bold">60%</h6>
            </div>
            <div class="progress">
              <div
                class="progress-bar bg-warning"
                role="progressbar"
                style="width: 60%"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">Javascript</h6>
              <h6 class="font-weight-bold">50%</h6>
            </div>
            <div class="progress">
              <div
                class="progress-bar bg-danger"
                role="progressbar"
                style="width: 50%"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">Database Query</h6>
              <h6 class="font-weight-bold">50%</h6>
            </div>
            <div class="progress">
              <div
                class="progress-bar bg-danger"
                role="progressbar"
                style="width: 50%"
                aria-valuenow="100"
                aria-valuemin="0"
                aria-valuemax="100"
              ></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid pt-5" id="service">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          Service
        </h1>
      </div>
      <div class="row pb-3">
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i
              class="fa fa-2x fa-laptop service-icon bg-danger text-white mr-3"
            ></i>
            <h4 class="font-weight-bold m-0">Web Design</h4>
          </div>
          <p>
            Web design is a symphony of aesthetics and functionality. It's the
            careful orchestration of visual elements, user experience, and
            technological prowess. A great web designer doesn't just create
            websites;
          </p>
        </div>
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i
              class="fa fa-2x fa-laptop-code service-icon bg-danger text-white mr-3"
            ></i>
            <h4 class="font-weight-bold m-0">Web Development</h4>
          </div>
          <p>
            As web developers, we don't just write code; we sculpt digital
            landscapes, where each line is a contour, and every function is a
            pathway for users to explore the boundless terrain of the online
            world.
          </p>
        </div>
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i
              class="fab fa-2x fa-android service-icon bg-danger text-white mr-3"
            ></i>
            <h4 class="font-weight-bold m-0">Database Logic</h4>
          </div>
          <p>
            Database logic is the silent architect of business efficiency. It
            transforms chaotic streams of information into a symphony of
            structured data, enabling businesses to harmonize their operations,
            orchestrate insights, and compose success in the ever-evolving
            business landscape.
          </p>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="contact">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          Contact
        </h1>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="contact-form text-center">
            <div id="success"></div>
            <form name="sentMessage" id="contactForm" novalidate="novalidate">
              <div class="form-row">
                <div class="control-group col-sm-6">
                  <input
                    type="text"
                    class="form-control p-4"
                    id="name"
                    placeholder="Your Name"
                    required="required"
                    data-validation-required-message="Please enter your name"
                  />
                  <p class="help-block text-danger"></p>
                </div>
                <div class="control-group col-sm-6">
                  <input
                    type="email"
                    class="form-control p-4"
                    id="email"
                    placeholder="Your Email"
                    required="required"
                    data-validation-required-message="Please enter your email"
                  />
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              <div class="control-group">
                <input
                  type="text"
                  class="form-control p-4"
                  id="subject"
                  placeholder="Subject"
                  required="required"
                  data-validation-required-message="Please enter a subject"
                />
                <p class="help-block text-danger"></p>
              </div>
              <div class="control-group">
                <textarea
                  class="form-control py-3 px-4"
                  rows="5"
                  id="message"
                  placeholder="Message"
                  required="required"
                  data-validation-required-message="Please enter your message"
                ></textarea>
                <p class="help-block text-danger"></p>
              </div>
              <div>
                <button
                  class="btn btn-outline-danger"
                  type="submit"
                  id="sendMessageButton"
                >
                  Send Message
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
  <hr />
  <div class="container-fluid py-5" id="application">
    <div class="container">
      <div
        class="position-relative d-flex align-items-center justify-content-center"
      >
        <h1
          class="display-1 text-uppercase text-dark"
          style="-webkit-text-stroke: 1px #dee2e6"
        >
          Application
        </h1>
      </div>

      <div class="tic-tac-toe">
        <div v-for="(row, rowIndex) in board" :key="rowIndex" class="row">
          <div
            v-for="(cell, cellIndex) in row"
            :key="cellIndex"
            class="cell"
            @click="cellClick(rowIndex, cellIndex)"
          >
            <span
              :class="{ 'blue-text': cell === 'X', 'red-text': cell === 'O' }"
              >{{ cell }}</span
            >
          </div>
        </div>
        <div v-if="winner" class="winner-message">
          <p>Congratulations! {{ winner }} wins!</p>
        </div>
        <button class="btn btn-primary mt-2 bg-danger" @click="resetBoard">Reset</button>
      </div>
    </div>
  </div>
  <div class="container-fluid bg-dark text-white mt-5 px-sm-3 px-md-5">
    <div class="container text-center py-5">
      <div class="d-flex justify-content-center mb-4">
        <a
          class="btn btn-light bg-primary text-danger btn-social mr-2"
          href="https://www.facebook.com/jovet.quillan"
          ><i class="fab fa-facebook-f"></i
        ></a>
        <a class="btn btn-light btn-social bg-primary text-danger" href="https://www.instagram.com/obito4_20/?hl=en"
          ><i class="fab fa-instagram"></i
        ></a>
      </div>
      <div class="d-flex justify-content-center mb-3">
        <a class="text-white" href="#">Privacy</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">Terms</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">FAQs</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">Help</a>
      </div>
      <p class="m-0">
        &copy; <span class="text-danger">Jovet Kei Quillan</span>. All
        Rights Reserved. Designed by Shinigami Jovet Kei Quillan
        <a class="text-white font-weight-bold" href="https://htmlcodex.com"
          >HTML Codex</a
        >
      </p>
    </div>
  </div>
</template>
<script setup>
import { ref } from "vue";

const boardSize = 3;
const board = ref(
  Array.from({ length: boardSize }, () => Array(boardSize).fill(""))
);
const currentPlayer = ref("X");
const winner = ref(null);
const moves = ref(0);

const checkWinner = () => {
  // Check rows, columns, and diagonals for a winner
  // (remaining code remains unchanged)
};

const cellClick = (row, col) => {
  if (!winner.value && board.value[row][col] === "") {
    board.value[row][col] = currentPlayer.value;
    currentPlayer.value = currentPlayer.value === "X" ? "O" : "X";
    moves.value += 1;
    checkWinner();
  }
};

const resetBoard = () => {
  for (let i = 0; i < boardSize; i++) {
    for (let j = 0; j < boardSize; j++) {
      board.value[i][j] = "";
    }
  }
  winner.value = null;
  currentPlayer.value = "X";
  moves.value = 0;
};
</script>
<style>
.blue-text {
  color: blue;
}

.red-text {
  color: red;
}
.tic-tac-toe {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: Arial, sans-serif;
}

.row {
  display: flex;
}

.cell {
  width: 200px;
  height: 150px;
  border: 1px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 24px;
  cursor: pointer;
}

.winner-message {
  margin-top: 20px;
  font-size: 18px;
}
</style>