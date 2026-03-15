<script>
</script>

<svelte:head>
    <title>Squid Game - Kang Sae-byeok (Player 067)</title>
</svelte:head>

<main>
    <div class="character-container">
        <div class="character-image">
            <img src="/images/HoYeonJung.jpg" alt="Kang Sae-byeok">
        </div>
        
        <div class="character-info">
            <h1>KANG SAE-BYEOK</h1>
            <h2>PLAYER 067</h2>
            
            <div class="details">
                <p><strong>Age:</strong> Late 20s</p>
                <p><strong>Status:</strong> Deceased</p>
                <p><strong>Origin:</strong> North Korea</p>
                <p><strong>Reason for joining:</strong> To rescue her mother from loan sharks</p>
            </div>
            
            <div class="description">
                <h3>BACKGROUND</h3>
                <p>
                    Kang Sae-byeok is a North Korean defector who participated in the Squid Game. She is a skilled 
                    and resourceful player who was forced to leave her home country. In South Korea, she works 
                    various jobs while trying to earn enough money to bring her mother over and escape from 
                    loan sharks who control her family.
                </p>
                
                <h3>KEY MOMENTS</h3>
                <ul>
                    <li>Player 067 - entered the games to win money for her family</li>
                    <li>Won the marble game by using a clever distraction technique</li>
                    <li>Formed an alliance with Seong Gi-hun and became close allies</li>
                    <li>Was killed during the glass tile game (Hexagon) by Jang Deok-su</li>
                </ul>
                
                <h3>SKILLS & PERSONALITY</h3>
                <p>
                    Sae-byeok is portrayed as intelligent, quick-thinking, and adaptable. She has excellent 
                    observation skills and is able to analyze situations quickly. Despite her tough exterior, 
                    she cares deeply for her family, especially her younger brother Sae-byeol who is in an 
                    orphanage. Her North Korean background gives her a unique perspective and survival skills 
                    that help her in the games.
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
