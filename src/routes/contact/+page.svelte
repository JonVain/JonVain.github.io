<div id="taustakuva">
  <h1>Yhteystiedot</h1>
  <p id="yt">Jonne Vainikainen</p>
  <p>040123123</p>
  <b />
  <hr
    class="w-48 h-1 mx-auto my-4 bg-gray-100 border-0 rounded md:my-10 dark:bg-gray-700"
  />
  <p id="testink">Jätä palautetta alla olevaan kenttään.</p>

  <div class="form-floating">
    <textarea
      class="form-control"
      placeholder="Leave a comment here"
      id="floatingTextarea2"
      style="height: 100px"
    />
    <label for="floatingTextarea2">Comments</label>
  </div>
  <div>
    <button type="button" class="btn btn-primary">Lähetä</button>
    <h2>Nappi on visuaalinen</h2>
  </div>
</div>

<style>
  h2 {
    text-align: left;
  }
  h1,
  p {
    text-align: center;
  }
  button {
    align-items: center;
    width: 100px;
    text-decoration: line-through;
  }
  #testink {
    color: red;
    font-weight: bold;
    text-transform: uppercase;
    padding-left: 1vh;
    text-align: left;
  }
  #yt {
    word-wrap: break-word;
  }
  #taustakuva {
    background-image: url("https://images.pexels.com/photos/12733865/pexels-photo-12733865.png?");
    height: 200vh;
    background-size: auto;
    background-repeat: no-repeat;
  }
</style>
