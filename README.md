# Test Svelte


## Úkoly

- v **+page.svelte** vytvoř tlačítko **+**
  - po kliknutí na tlačítko se přidá 1 do počítadla
- aktuální počet kliknutí se zobrazí v připraveném `<p>` ve **+page.svelte**
- vytvoř druhé tlačítko s emoji 🙂
  - po kliknutí na tlačítko s emoji se emoji přepne na 😢
  - po opětovném kliknutí se přepne zpět na 🙂
    -- do správné složky vytvoř komponent **Heading.svelte**
  - uvnitř komponentu je nadpis `<h2>` s textem, který komponent přijímá pomocí **props**
- do **+page.svelte** přidej 3x komponent **Heading**
  - do **prvního** komponentu pošli text **"Svelte"** pomocí _props_
  - do **druhého** komponentu pošli text **"je"** pomocí _props_
  - do **třetího** komponentu pošli text **"brnkačka"** pomocí _props_
- uprav logiku HTML tak, aby se komponenty **Heading** zobrazily až poté, co je počet kliknutí 5 nebo vyšší
- uprav tlačítko s emoji
  - pokud je emoji 🙂, při kliku na tlačítko `+` se počet kliknutí **přičítá**
  - pokud je emoji 😢, při kliku na tlačítko `+` se počet kliknutí **odečítá**

CSS není potřeba upravovat

[Klikni sem pro gif s ukázkou požadované funkcionality](https://github.com/user-attachments/assets/1565f3db-c47b-4424-b75a-f807ea3555a8)


![image](https://github.com/user-attachments/assets/929c7e2e-a8f5-4cf0-9df8-74ccf7cae55e)



Nápověda pro syntax props: `let { ukazka } = $props()`

### Počet bodu: ?/100
