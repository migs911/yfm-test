# Test grids

<style scoped>
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
    grid-gap: 20px;
}

.card {
    display: grid;
    grid-template-rows: max-content 200px 1fr;
}

.card img {
    object-fit: cover;
    width: 100%;
    height: 100%;
}
</style>

<div class="cards">
    <article class="card">
        <header>
            <h2>A short heading</h2>
        </header>    
        <img src="https://mdn.github.io/css-examples/css-cookbook/balloons.jpg" alt="Hot air balloons">
        <div class="content">
            <p> The idea of reaching the North Pole by means of balloons appears to have been entertained many years ago. </p>
        </div>            
    </article>            
     <article class="card">
        <header>
            <h2>A short heading</h2>
        </header>    
        <img src="https://mdn.github.io/css-examples/css-cookbook/balloons2.jpg" alt="Hot air balloons">
        <div class="content">
            <p>Short content.</p>
        </div>
    </article>
    <article class="card">
        <header>
            <h2>A longer heading in this card</h2>
        </header>
        <img src="https://mdn.github.io/css-examples/css-cookbook/balloons.jpg" alt="Hot air balloons">
        <div class="content">
            <p>In a curious work, published in Paris in 1863 by Delaville Dedreux, there is a
                suggestion for reaching the North Pole by an aerostat.</p>
        </div>
        <footer>I have a footer!</footer>
    </article>
    <article class="card">
        <header>
            <h2>A short heading</h2>
        </header>
        <img src="https://mdn.github.io/css-examples/css-cookbook/balloons2.jpg" alt="Hot air balloons">
        <div class="content">
            <p> The idea of reaching the North Pole by means of balloons appears to have been entertained many
                years ago. </p>
        </div>
    </article>
</div>
            
    

test
