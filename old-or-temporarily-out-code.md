  <nav>
        <h1 id="spacey-heading-or-main-title">SPACEY</h1>
        <!-- goes to top -->
        <a href="Homepage.com" class="nav-link">HOME</a>
        <!-- goes to top -->
        <a href="Aboutpage.com" class="nav-link">ABOUT</a>
        <!-- goes to tickets -->
        <a href="Tickets" class="nav-link">TICKETS</a>
        <!-- goes to tickets -->
        <a href="Rockets" class="nav-link">ROCKETS</a>
        <!-- goes to top -->
        <a href="Pricing" class="nav-link">PRICING</a>
      </nav>

    <main>
      <section id="section1">
        <h3>RECENT LAUNCH</h3>
        <h1>SHIPFLIGHT VIDEO</h1>
        <!-- goes to top -->
        <a href="Homepage.com" class="nav-link-up">READ MORE</a>
      </section>
      <section id="section2">
        <h3>BUY TICKETS</h3>
        <h1>YOU CAN GO TO SPACE!</h1>
        <!-- goes to top -->
        <a href="Homepage.com" class="nav-link-up">READ MORE</a>
      </section>
      <section id ="section3">
        <h3>SPACE TRAVEL DEALS</h3>
        <h1>YOU MIGHT NOT HAVE TO SELL A KIDNEY!</h1>
        <!-- goes to top -->
        <a href="Homepage.com" class="nav-link-up">READ MORE</a>
      </section>
    </main>

---

- {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  }

body {
color: white;
font-family: sans-serif;
outline: 1px, solid, red;
/_ could have the font upper case setting here but note the footer is in lower case and upper _/
}

header {
background-color: blue;
display: inline-block;
}

h1 {
background-color: aqua;
}

nav {
background-color: transparent;
display: inline;
z-index: 1000;
position: relative;
}

.nav-link {
background-color: azure;
}

main {
background-color: black;
}

section {
background-color: aquamarine;
}

h2 {
background-color: lightblue;
}

h3 {
background-color: lightseagreen;
}

.section {
background-repeat: no-repeat;
background-position: 0px;
background-attachment: fixed;
background-origin: padding-box;
background-size: 100vw 100vh;
/_ background-clip: border-box; _/
}

#section1 {
background-image: url("https://spacey-kappa.vercel.app/assets/galaxy-5803c9f1.jpg");
}

#section2 {
background-image: url("https://images.unsplash.com/photo-1610296669228-602fa827fc1f?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8c3BhY2V8ZW58MHx8MHx8fDI%3D");
}

#section3 {
background-image: url("https://images.unsplash.com/photo-1537420327992-d6e192287183?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8c3BhY2V8ZW58MHx8MHx8fDI%3D");
}

.link2 {
color: white;
border-style: solid;
border-width: 5px;
border-color: white;
background-color: transparent;
}

.nav-link-up {
border-style: solid;
border-width: 5px;
border-color: white;
background-color: transparent;
}

footer {
background-color: navy;
}
