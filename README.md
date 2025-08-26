/* Sets the vintage-themed color palette */
:root {
  --sepia-brown: #704214;
  --muted-gold: #b8860b;
  --dusty-rose: #bc8f8f;
  --creamy-white: #f8f0e3;
  --content-paper: #fffaf0;
  --charcoal-gray: #36454f;
}

/* Overall page styling */
body {
    background-color: var(--creamy-white); 
    color: var(--charcoal-gray);
    font-family: Georgia, serif; 
    margin: 0;
    padding: 0;
}

/* Header and Banner Styling */
header {
    width: 100%;
    text-align: center;
}

header img {
    max-width: 100%;
    height: auto;
}

/* Main title styling */
h1 {
    color: var(--sepia-brown); 
    text-align: center;
    font-family: 'Times New Roman', Times, serif; 
    font-size: 2.5rem;
    margin-top: 20px;
}

/* Main content container */
main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: var(--content-paper); 
    border: 1px solid #c0b299; 
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
}

/* Individual chemist sections */
section {
    margin-bottom: 25px;
    padding-bottom: 15px;
    border-bottom: 2px solid var(--sepia-brown); 
}

/* Scientist names */
h2 {
    color: var(--muted-gold); 
    text-align: center;
    font-family: 'Times New Roman', Times, serif; 
}

/* Scientist images */
img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 10px auto;
    border: 5px solid var(--muted-gold); 
}
