<template>
  <section class="header">
    <nav>
      <img src="./assets/images/Logo.svg" alt="logo" />
      <form class="srch-bar">
        <input
          class="srch"
          type="search"
          placeholder="What do you want to watch?"
        />
        <button type="submit">
          <img src="./assets/images/Icon.svg" alt="search icon" />
        </button>
      </form>
      <img src="./assets/images/Menu.svg" alt="menu" />
    </nav>
    <div class="descrip">
      <div class="descrip-text">
        <img src="./assets/images/descrip.svg" alt="" />
      </div>
      <div class="pag">
        <img src="./assets/images/pagination.svg" alt="pagination" />
      </div>
    </div>
  </section>
  <section class="main">
    <div class="feat-movs container">
      <nav>
        <h1>Featured Movie</h1>
        <a href="#">See more ></a>
      </nav>
      <div class="ftm-sub">
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5 8.25 12l7.5-7.5"
            />
          </svg>
        </button>
        <div class="ftm-cards">
          <div class="mv-cards i">
            <img
              class="thumbnails"
              src="./assets/images/Stranger.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2016 - Current</h5>
            <h3 class="mv-title">Stranger Things</h3>
            <img
              class="rating"
              src="./assets/images/ratingST.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Adventure,</h6>
          </div>
          <div class="mv-cards ii">
            <img
              class="thumbnails"
              src="./assets/images/Batman.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA,2005</h5>
            <h3 class="mv-title">Batman Begins</h3>
            <img
              class="rating"
              src="./assets/images/ratingBT.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Adventure</h6>
          </div>
          <div class="mv-cards iii">
            <img
              class="thumbnails"
              src="./assets/images/Spiderman.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2018</h5>
            <h3 class="mv-title">Spider-Man:Into The SpiderVerse</h3>
            <img
              class="rating"
              src="./assets/images/ratingSPM.svg"
              alt="rating"
            />
            <h6 class="genre">Animation, Action, Adventure</h6>
          </div>
          <div class="mv-cards iv">
            <img
              class="thumbnails"
              src="./assets/images/Dunkirk.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2017</h5>
            <h3 class="mv-title">Dunkirk</h3>
            <img
              class="rating"
              src="./assets/images/ratingDK.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Drama, History</h6>
          </div>
        </div>
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m8.25 4.5 7.5 7.5-7.5 7.5"
            />
          </svg>
        </button>
      </div>
    </div>
    <div class="new-arr container">
      <nav>
        <h1>New Arrivals</h1>
        <a href="#">See more ></a>
      </nav>
      <div class="nwa-sub">
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5 8.25 12l7.5-7.5"
            />
          </svg>
        </button>
        <div class="nwa-cards">
          <div class="mv-cards i">
            <img
              class="thumbnails"
              src="./assets/images/Dune.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2021</h5>
            <h3 class="mv-title">Dune</h3>
            <img
              class="rating"
              src="./assets/images/ratingDN.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Adventure, Drama</h6>
          </div>
          <div class="mv-cards ii">
            <img
              class="thumbnails"
              src="./assets/images/JamesB.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2021</h5>
            <h3 class="mv-title">No Time To Die</h3>
            <img
              class="rating"
              src="./assets/images/ratingJB.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Adventure, Thriller</h6>
          </div>
          <div class="mv-cards iii">
            <img
              class="thumbnails"
              src="./assets/images/ShengChi.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2021</h5>
            <h3 class="mv-title">Shang-Chi and the Lengend of the Ten Rings</h3>
            <img
              class="rating"
              src="./assets/images/ratingSC.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Adventure, Fantasy</h6>
          </div>
          <div class="mv-cards iv">
            <img
              class="thumbnails"
              src="./assets/images/Dnt.jpg"
              alt="thumbnail"
            />
            <h5 class="lct">USA, 2021</h5>
            <h3 class="mv-title">Don't Breathe 2</h3>
            <img
              class="rating"
              src="./assets/images/ratingDB.svg"
              alt="rating"
            />
            <h6 class="genre">Action, Drama, Horror</h6>
          </div>
        </div>
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m8.25 4.5 7.5 7.5-7.5 7.5"
            />
          </svg>
        </button>
      </div>
    </div>
    <div class="exclu-vids container">
      <nav>
        <h1>Exclusive Videos</h1>
        <a href="#">See more ></a>
      </nav>
      <div class="exv-sub">
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5 8.25 12l7.5-7.5"
            />
          </svg>
        </button>
        <div class="exv-cards">
          <div class="trailer-cards I">
            <img src="./assets/images/Lamb.jpg" alt="play button" />
            <h4 class="mv-title">Lamb (2021) Trailer</h4>
          </div>

          <div class="trailer-cards II">
            <img src="./assets/images/Suicide.jpg" alt="play button" />
            <h4 class="mv-title">The Suicide Squad:John Cena Interview</h4>
          </div>

          <div class="trailer-cards III">
            <img
              style="width: 100%"
              src="./assets/images/Willbethere.jpg"
              alt="play button"
            />
            <h4 class="mv-title">Will there be a new era of ho</h4>
          </div>
        </div>

        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m8.25 4.5 7.5 7.5-7.5 7.5"
            />
          </svg>
        </button>
      </div>
    </div>
    <div class="feat-cst container">
      <nav>
        <h1>Featured Casts</h1>
        <a href="#">See more ></a>
      </nav>
      <div class="ftc-sub">
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 19.5 8.25 12l7.5-7.5"
            />
          </svg>
        </button>
        <div class="ftc-cards">
          <div class="mv-cards i">
            <img
              class="thumbnails"
              src="./assets/images/Johnwick2.jpg"
              alt="Keanu Reeves"
            />
            <h4 class="mv-title">Keanu Reeves</h4>
          </div>
          <div class="mv-cards ii">
            <img
              class="thumbnails"
              src="./assets/images/Ryan.jpg"
              alt="Ryan Reynolds"
            />
            <h4 class="mv-title">Ryan Reynolds</h4>
          </div>
          <div class="mv-cards iii">
            <img
              class="thumbnails"
              src="./assets/images/Timothée.jpg"
              alt="Timothée Chalamet"
            />
            <h4 class="mv-titleth">Timothée Chalamet</h4>
          </div>
          <div class="mv-cards iv">
            <img
              class="thumbnails"
              src="./assets/images/Chloë.jpg"
              alt="thumbnail"
            />
            <h4 class="mv-title">Chloë Grace Moretz</h4>
          </div>
        </div>
        <button class="mn-btn">
          <svg
            class="btn-icon"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="m8.25 4.5 7.5 7.5-7.5 7.5"
            />
          </svg>
        </button>
      </div>
    </div>
  </section>

  <section class="footer">
    <div class="media-icn">
      <div>
        <img src="./assets/images/vector.svg" alt="facebook" />
      </div>
      <div>
        <img src="./assets/images/instagram.svg" alt="instagram" />
      </div>
      <div>
        <img src="./assets/images/twitter.svg" alt="twitter" />
      </div>
      <div>
        <img src="./assets/images/youtube.svg" alt="youtube" />
      </div>
    </div>
    <div class="about media-icn">
      <div>
        <h5>Conditions of Use</h5>
      </div>
      <div>
        <h5>Privacy & policy</h5>
      </div>
      <div>
        <h5>Press Room</h5>
      </div>
    </div>
    <div class="td-mrk media-icn">
      <div>
        <h5>&copy; 2021 MovieBox by Adriana Eka Prayudha</h5>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.header {
  min-height: 100vh;
  width: 100%;
  background-image: url("./assets/images/johnwick.jpg");
  background-position: center;
  background-size: cover;
  position: relative;
}
h5,
h3,
h4 {
  margin: 0;
}
nav {
  display: flex;
  padding: 0% 6%;
  padding-top: 20px;
  justify-content: space-between;
  align-items: center;
}
.main {
  margin-bottom: 60px;
}
.main nav {
  display: flex;
  padding: 0% 5%;
  // padding-top: 49px;
  justify-content: space-between;
  align-items: center;
  font-size: 19px;
}
nav a {
  text-decoration: none;
  color: rgb(221, 23, 106);
}
a:hover {
  /* text-decoration: underline; */
  color: #c1c3c6;
  cursor: pointer;
  transition: 0.1s;
}
.srch-bar {
  width: 400px;
  background: transparent;
  display: flex;
  align-items: center;
  border: 1px solid wheat;
  border-radius: 7px;
  padding: 4px 10px;
}
.srch {
  background-color: transparent;
  flex: 1;
  border: 0;
  outline: none;
}
::placeholder {
  color: #fff;
}
.srch-bar button {
  border: 0;
  border: 50%;
  background: transparent;
}
.descrip {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 100px;
}
.descrip-text {
  display: flex;
  justify-content: center;
  padding-left: 90px;
}
.descrip-text img {
  width: 500px;
}
.pag img {
  width: 30px;
}
/* .feat-movs{
  margin: auto;
} */
.ftm-sub,
.nwa-sub,
.exv-sub,
.ftc-sub {
  width: 97%;
  margin: auto;
  display: flex;
  align-items: center;
}
.mn-btn {
  width: 50px;
  height: 200px;
  border: none;
  border-radius: 20px;
  background-color: transparent;
  cursor: pointer;
}
.mn-btn:hover {
  background-color: #c1c3c6;
  transition: 0.2s;
}

.btn-icon {
  height: 25px;
  width: 25px;
  stroke: #c1c3c6;
  /* background-size: 50%; */
}
.mn-btn:hover .btn-icon {
  stroke: #fff;
  transition: 0.2s;
}
.ftm-cards,
.nwa-cards,
.exv-cards,
.ftc-cards {
  width: 100%;
  margin: auto;
  display: flex;
  justify-content: space-between;
}
.thumbnails,
.mv-cards {
  width: 250px;
  height: 350px;
}
.lct,
.mv-title,
.rating {
  margin-bottom: 10px;
}

.genre,
.td-mrk {
  margin: 0;
  color: grey;
}
.feat-movs,
.new-arr {
  margin-bottom: 150px;
}

.exclu-vids {
  margin-bottom: 15px;
}

.footer {
  display: flex;
  flex-direction: column;
  // align-items: center;
  // justify-content: center;
  background: rgb(251, 247, 247);
  padding: 0 0;
  color: #000;
  font-size: 16px;
  // margin-top: 20px;
  .media-icn {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
    margin-bottom: 20px;
  }
  .about {
  }
}
</style>
