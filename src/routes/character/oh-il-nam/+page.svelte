<script>
</script>

<svelte:head>
    <title>Squid Game - Oh Il-nam (Player 001)</title>
</svelte:head>

<main>
    <div class="character-container">
        <div class="character-image">
            <img src="/images/Oh_Il-nam.jpg" alt="Oh Il-nam">
        </div>
        
        <div class="character-info">
            <h1>OH IL-NAM</h1>
            <h2>PLAYER 001</h2>
            
            <div class="details">
                <p><strong>Age:</strong> Late 70s</p>
                <p><strong>Status:</strong> Deceased</p>
                <p><strong>Occupation:</strong> Former bank employee</p>
                <p><strong>Reason for joining:</strong> Terminal brain tumor</p>
            </div>
            
            <div class="description">
                <h3>BACKGROUND</h3>
                <p>
                    Oh Il-nam is the oldest participant in the Squid Game. He is a elderly man suffering from 
                    a terminal brain tumor who joins the games hoping to win the prize money for his family.
                    Despite his age and health condition, he manages to survive several rounds.
                </p>
                
                <h3>KEY MOMENTS</h3>
                <ul>
                    <li>Player 001 - the first player to enter the games</li>
                    <li>Befriended Seong Gi-hun (Player 456) during the competition</li>
                    <li>Revealed to be the creator/founder of the Squid Game</li>
                    <li>Died in the final game after losing to Seong Gi-hun</li>
                </ul>
                
                <h3>TRIVIA</h3>
                <p>
                    Oh Il-nam is revealed to be the mysterious VIP known as "The Host" who watches the games 
                    from behind the scenes. He is also the one who created the games as a form of entertainment 
                    for the wealthy, seeking to give people with financial troubles a chance to win big.
                </p>
            </div>
        </div>
    </div>
</main>

<style>
    .character-container {
        display: flex;
        gap: 3rem;
        padding: 2rem;
        max-width: 1200px;
        margin: 0 auto;
    }

    .character-image {
        flex: 1;
        min-width: 300px;
    }

    .character-image img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        box-shadow: 0 0 20px rgba(233, 30, 99, 0.5);
    }

    .character-info {
        flex: 2;
    }

    h1 {
        font-family: "Megrim", system-ui;
        font-size: 3cqw;
        color: #e30a5a;
        margin-bottom: 0.5rem;
        letter-spacing: 0.2rem;
    }

    h2 {
        font-family: "Megrim", system-ui;
        font-size: 2cqw;
        color: gold;
        margin-bottom: 1.5rem;
    }

    .details {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 0.5rem;
        margin-bottom: 2rem;
        padding: 1rem;
        background: rgba(233, 30, 99, 0.2);
        border-radius: 10px;
    }

    .details p {
        font-family: "Lato", sans-serif;
        font-size: 1cqw;
        margin: 0;
    }

    .description h3 {
        font-family: "Megrim", system-ui;
        font-size: 1.5cqw;
        color: #e30a5a;
        margin-top: 1.5rem;
        margin-bottom: 0.5rem;
    }

    .description p {
        font-family: "Lato", sans-serif;
        font-size: 1.2cqw;
        line-height: 1.7;
    }

    .description ul {
        font-family: "Lato", sans-serif;
        font-size: 1.2cqw;
        line-height: 1.7;
        padding-left: 1.5rem;
    }

    @media (max-width: 768px) {
        .character-container {
            flex-direction: column;
            padding: 1rem;
        }

        h1, h2 {
            font-size: 2rem;
        }

        .details p, .description p, .description ul {
            font-size: 1rem;
        }

        .description h3 {
            font-size: 1.2rem;
        }
    }
</style>
