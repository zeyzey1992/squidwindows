<script>
    import faqData from '../../data/faq.json';
    
    let faqs = faqData.faqs;
    let openIndex = -1;
    
    function toggleFAQ(index) {
        openIndex = openIndex === index ? -1 : index;
    }
</script>

<svelte:head>
    <title>Squid Game - FAQ</title>
</svelte:head>

<main>  
    <h1>FREQUENTLY ASKED QUESTIONS</h1>
    
    <div class="faq-container">
        {#each faqs as faq, index}
            <div class="faq-item">
                <button 
                    class="faq-question" 
                    onclick={() => toggleFAQ(index)}
                    class:active={openIndex === index}
                >
                    {faq.question}
                    <span class="icon">{openIndex === index ? '−' : '+'}</span>
                </button>
                {#if openIndex === index}
                    <div class="faq-answer">
                        <p>{faq.answer}</p>
                    </div>
                {/if}
            </div>
        {/each}
    </div>
</main>

<style>
    main {
        max-width: 800px;
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

    .faq-container {
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }

    .faq-item {
        background: rgba(0, 0, 0, 0.7);
        border: 2px solid #e30a5a;
        border-radius: 10px;
        overflow: hidden;
    }

    .faq-question {
        width: 100%;
        padding: 1.5rem;
        background: transparent;
        border: none;
        color: white;
        font-family: "Lato", sans-serif;
        font-size: 1.1rem;
        text-align: left;
        cursor: pointer;
        display: flex;
        justify-content: space-between;
        align-items: center;
        transition: background 0.3s;
    }

    .faq-question:hover {
        background: rgba(233, 30, 99, 0.2);
    }

    .faq-question.active {
        background: rgba(233, 30, 99, 0.3);
    }

    .icon {
        font-size: 1.5rem;
        color: gold;
    }

    .faq-answer {
        padding: 1rem 1.5rem;
        background: rgba(0, 0, 0, 0.5);
        border-top: 1px solid #e30a5a;
    }

    .faq-answer p {
        font-family: "Lato", sans-serif;
        font-size: 1rem;
        line-height: 1.7;
        color: #ccc;
        margin: 0;
    }

    @media (max-width: 768px) {
        h1 {
            font-size: 2rem;
        }

        .faq-question {
            font-size: 1rem;
            padding: 1rem;
        }
    }
</style>
