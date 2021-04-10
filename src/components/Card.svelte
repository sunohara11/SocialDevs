<script>
    import Comments from "./Comments.svelte";
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://i.imgur.com/XquZ30d.jpg" alt="">
                <h2>
                    React.diploma
                    <span>El Salvador</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class="far fa-ellipsis-h"/>
            </div>
            
            <div class="Card-photo">
                <figure>
                    <img src="https://i.imgur.com/XquZ30d.jpg" alt="">
                </figure>
            </div>
            <div class="Card-icons">
                <div class="Card-icons-first">
                    <i class="far fa-heart"></i>
                    <i class="fas fa-paper-plane"/>
                </div>
                <div class="Card-icons-second">
                    <i class="fas fabookmark"/>
                </div>
            </div>
            <div class="Card-description">
                <h3>suno</h3>
                <span>Go ahead!</span>
            </div>
            <Comments/>
        </div>
    </div>
</div>