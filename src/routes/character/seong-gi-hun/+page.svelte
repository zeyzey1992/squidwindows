<script>
</script>

<svelte:head>
    <title>Squid Game - Seong Gi-hun (Player 456)</title>
</svelte:head>

<main>
    <div class="character-container">
        <div class="character-image">
            <img src="/images/SeongGi-hun.jpg" alt="Seong Gi-hun">
        </div>
        
        <div class="character-info">
            <h1>SEONG GI-HUN</h1>
            <h2>PLAYER 456</h2>
            
            <div class="details">
                <p><strong>Age:</strong> Mid-to-late 30s</p>
                <p><strong>Status:</strong> Alive</p>
                <p><strong>Occupation:</strong> Driver, formerly</p>
                <p><strong>Reason for joining:</strong> Massive debt and financial struggles</p>
            </div>
            
            <div class="description">
                <h3>BACKGROUND</h3>
                <p>
                    Seong Gi-hun is the main protagonist of Squid Game and the final winner of the deadly competition. 
                    He is a struggling father who is deeply in debt due to gambling and making bad financial decisions. 
                    His life changes when he is recruited to participate in the Squid Game, where he must survive 
                    a series of deadly children's games to win the ₩45.6 billion prize.
                </p>
                
                <h3>KEY MOMENTS</h3>
                <ul>
                    <li>Player 456 - the last player to join the games</li>
                    <li>Won the first game (Red Light, Green Light) by recognizing the song</li>
                    <li>Formed close friendships with Player 001 (Oh Il-nam) and Player 067 (Kang Sae-byeok)</li>
                    <li>Won the final game against Oh Il-nam in Squid Game</li>
                    <li>Became the sole survivor and winner of ₩45.6 billion</li>
                </ul>
                
                <h3>CHARACTER ARC</h3>
                <p>
                    Throughout the series, Gi-hun transforms from a selfish, irresponsible man who neglects his 
                    daughter into a more compassionate and morally upright individual. His experiences in the 
                    games force him to confront the harsh realities of society and the class disparity that 
                    drives people to desperate measures. In the end, despite winning the money, he chooses not 
                    to spend it, instead dedicating himself to exposing the organizers of the game.
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
