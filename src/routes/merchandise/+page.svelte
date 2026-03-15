<script>
</script>

<svelte:head>
    <title>Squid Game - Merchandise</title>
</svelte:head>

<main>
    <h1>SQUID GAME MERCHANDISE</h1>
    
    <div class="merch-grid">
        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/background.png" alt="Pink Mask">
            </div>
            <h3>Pink Guard Mask</h3>
            <p class="price">$24.99</p>
            <p class="description">Official Pink Guard mask from Squid Game. Perfect for cosplay or collection.</p>
            <button>Add to Cart</button>
        </div>

        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/goldmasks.jpg" alt="Gold Mask">
            </div>
            <h3>Gold VIP Mask</h3>
            <p class="price">$34.99</p>
            <p class="description">Luxurious gold mask inspired by the VIP characters. Premium quality.</p>
            <button>Add to Cart</button>
        </div>

        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/gamemaster.jpg" alt="Squid Game Hoodie">
            </div>
            <h3>Squid Game Hoodie</h3>
            <p class="price">$49.99</p>
            <p class="description">Comfortable hoodie with the iconic frontman logo. Available in multiple sizes.</p>
            <button>Add to Cart</button>
        </div>

        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/game2.jpg" alt="Playing Card Set">
            </div>
            <h3>Playing Card Set</h3>
            <p class="price">$14.99</p>
            <p class="description">Official Squid Game themed playing cards. Includes all player numbers.</p>
            <button>Add to Cart</button>
        </div>

        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/title.png" alt="T-Shirt">
            </div>
            <h3>Squid Game T-Shirt</h3>
            <p class="price">$29.99</p>
            <p class="description">Cotton t-shirt featuring the iconic triangle symbol. Multiple colors available.</p>
            <button>Add to Cart</button>
        </div>

        <div class="merch-item">
            <div class="merch-image">
                <img src="/images/SeongGi-hun.jpg" alt="Poster">
            </div>
            <h3>Limited Edition Poster</h3>
            <p class="price">$19.99</p>
            <p class="description">High-quality print poster featuring the main characters. Frame not included.</p>
            <button>Add to Cart</button>
        </div>
    </div>
</main>

<style>
    main {
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem;
    }

    h1 {
        font-family: "Megrim", system-ui;
        font-size: 3cqw;
        color: #e30a5a;
        text-align: center;
        margin-bottom: 2rem;
        letter-spacing: 0.3rem;
    }

    .merch-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 2rem;
    }

    .merch-item {
        background: rgba(0, 0, 0, 0.7);
        border: 2px solid #e30a5a;
        border-radius: 10px;
        padding: 1rem;
        text-align: center;
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .merch-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 0 20px rgba(233, 30, 99, 0.5);
    }

    .merch-image {
        width: 100%;
        height: 200px;
        overflow: hidden;
        border-radius: 5px;
        margin-bottom: 1rem;
    }

    .merch-image img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    h3 {
        font-family: "Megrim", system-ui;
        color: gold;
        font-size: 1.5cqw;
        margin: 0.5rem 0;
    }

    .price {
        font-family: "Lato", sans-serif;
        font-size: 1.5rem;
        color: #e30a5a;
        font-weight: bold;
        margin: 0.5rem 0;
    }

    .description {
        font-family: "Lato", sans-serif;
        font-size: 0.9rem;
        color: #ccc;
        margin-bottom: 1rem;
    }

    button {
        background: #e30a5a;
        color: white;
        border: none;
        padding: 0.8rem 1.5rem;
        font-family: "Lato", sans-serif;
        font-size: 1rem;
        border-radius: 5px;
        cursor: pointer;
        transition: background 0.3s;
    }

    button:hover {
        background: #c0084a;
    }

    @media (max-width: 768px) {
        h1 {
            font-size: 2rem;
        }

        h3 {
            font-size: 1.2rem;
        }
    }
</style>
