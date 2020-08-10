<style>
  .share {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    background-color: white;
    margin: 0 0 2em 0;
    width: 300px;
    height: 80px;
    position: absolute;
    top: 300px;
    left: 30%;
    z-index: 9;
    padding: 1em;
  }
  .share-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .share-head h2 {
    font-size: 16px;
  }
  .share-content a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: black;
    font-size: 14px;
    margin: 2em 0 0 0;
  }
  .share-content i {
    color: #3b5998;
    margin: 0 0.5em 0 0;
    font-size: 20px;
  }
</style>

<div class="share">
    <div class="share-head">
        <h2>Compartir</h2>
        <span class="fas fa-times-circle" on:click></span>
    </div>
    <div class="share-content">
        <a href="https://google.com" target="_blank">
            <i class="fab fa-facebook-square"/>
            Compartir en Facebook
        </a>
    </div>
</div>