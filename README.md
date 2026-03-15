1) Stage 1 completed
no changes 

2) Stage 2 completed- Additional Character Pages

In this stage, three new character pages were added using GenAI. Each character has a separate page and a link from the main page.  

Characters added:

**Oh Il-nam / Player 001**  
   - Separate page: `src/routes/oh-il-nam/+page.svelte`  
   - Includes an `<h1>` with the character name and player number.  
   - Short description generated using GenAI.  

**Kang Sae-byeok / Player 067**  
   - Separate page: `src/routes/kang-sae-byeok/+page.svelte`  
   - Includes an `<h1>` with the character name and player number.  
   - Short description generated using GenAI.  

**Seong Gi-hun / Player 456**  
   - Separate page: `src/routes/seong-gi-hun/+page.svelte`  
   - Includes an `<h1>` with the character name and player number.  
   - Short description generated using GenAI.  
 
3) Stage 3 completed -  Merchandise and FAQ Pages

## Stage 3 – Merchandise and FAQ Pages

In this stage, two new pages were added to the project: a **Merchandise page** and a **FAQ page**, along with their corresponding navigation links.

### Merchandise Page:
- Route created at `/merchandise`
- Navigation link added in `Nav.svelte`
- 6 merchandise items added:
  1. Pink Guard Mask - $24.99
  2. Gold VIP Mask - $34.99
  3. Squid Game Hoodie - $49.99
  4. Playing Card Set - $14.99
  5. Squid Game T-Shirt - $29.99
  6. Limited Edition Poster - $19.99

### FAQ Page:
- JSON data file created at `src/data/faq.json` with 8 FAQ entries
- Route created at `/faq`
- Navigation link added in `Nav.svelte`
- FAQ page displays questions and answers in an accordion-style expandable list
