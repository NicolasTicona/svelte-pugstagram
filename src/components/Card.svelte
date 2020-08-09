<script>
    import Comments from './Comments.svelte';
</script>


<div class="card">
    <div class="card-container">
        <div class="card-header">
            <div class="card-user">
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
                <h2>Elmo.pug</h2>
                <span>Lima, Perú</span>
            </div>

            <div class="card-settings">
                <span><i class="fas fa-ellipsis-h"/></span>
            </div>
        </div>
        <div class="card-photo">
            <figure>
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
            </figure>
        </div>
        <div class="card-icons">
            <div class="card-icons-firsts">
                <span><i class="fas fa-heart"/></span>
                <span><i class="fas fa-paper-plane"/></span>
            </div>

            <div class="card-icons-second">
                <span><i class="fas fa-bookmark"/></span>
            </div>
        </div>

        <div class="card-description">
            <h3>elmo.pug</h3>
            <span>Hola!</span>
        </div>

        <Comments />
    </div>
</div>