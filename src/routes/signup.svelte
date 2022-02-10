<svelte:head>
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css'>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700;800&display=swap" rel="stylesheet">
</svelte:head>

<main>
    <div class="head">
        <div class="sect1">
            <a href="#a">
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAJpJREFUSEvtk8ENgCAMAI8N3ERH0BGcxBV0IzfQEXQTRzBNfBA+LRUSH/rF3JUDApW/UJnPL1ALfzJRA0zAoo4P2Ycs8A3oHsGsSXISxfAT6IGrlMAFF7llB264RfAKbhXsQAscwGDpHp+LNZFbYhHIQJLKJbEK3JIcQSoZgbXUO4g5kksemQq33CJtQHU9N5EKTH/4BWqy6oluh2weGSJzuSQAAAAASUVORK5CYII="/>    
            </a>
        </div>
        <div class="sect2">
            <h2>Create your account</h2>
        </div>
        <div class="sect3">
            <i class="fi fi-rr-eye"></i>
        </div>
    </div>
    
    <form>
        <div class="input-select">
            <label for="perfix">Prefix</label>
            <select name="prefixs" id="prefix">
                <option value="default">Select prefix</option>
                <option value="Mr">Mr</option>
                <option value="Mrs">Mrs</option>
            </select>
        </div>
        
        <div class="input-container name">
            <label for="fname">First Name</label>
            <input type="text" id="fname" name="fname" placeholder="First Name">
        </div>
        <div class="input-container name">
            <label for="lname">Last Name</label>
            <input type="text" id="lname" name="lname" placeholder="Last Name">
        </div>
        <div class="input-container name">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Email">
        </div>
        <div class="input-container-password">
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Password">
            <a href="/">
                <i class="fi fi-rr-eye"></i>
            </a>
        </div>
        <div class="input-container-password">
            <label for="password">Re-enter Password</label>
            <input type="password" id="password" name="password" placeholder="Password">
            <a href="/">
                <i class="fi fi-rr-eye"></i>
            </a>
        </div>
        <button class="signup-btn" type="submit">Signup</button>
        <p>Or login with</p>
        <div class="socials">
            <div class="social-btn">
                <a href="/">
                    <img src="https://i.postimg.cc/Qdy15tzD/google.png" alt="google">
                </a>
            </div>
        </div>
        <div class="word">
            <p>By continuing, you agree to our <a href="/signup"> <strong>Term of Use</strong></a></p>
        </div>
    </form>
</main>


<style>
    main {
        width: 100%;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        font-family: 'Raleway';
    }
    a {
        text-decoration: none;
        color: #1C89A7;
        font-weight: bolder;
    }
    .head {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        margin-top: 20px;
    }
    .sect1 {
        display: flex;
        justify-content: flex-start;
        padding-left: 20px;
    }
    .sect2 {
        display: flex;
        text-align: center;
    }
    .sect2 h2 {
        text-align: center;
        font-size: 16px;
        font-weight: 600;
    }
    .sect3 {
        padding-right: 20px;
    }
    i {
        color: white;
    }
    form {
        background: rgba(255, 255, 255, 0.801);
        backdrop-filter: blur(50px);
        border-radius: 10px;
        z-index: 1;
        padding: 20px;
    }
    form input[type="email"], form input[type="text"], form input[type="password"] {
        display: block;
        width: 100%;
        box-sizing: border-box;
        border-radius: 5px;
        border: 1px solid #CCCCCC;
        background: #FAFAFA;
        padding: 1em;
        margin-bottom: 1.25rem;
        margin-top: 10px;
    }
    select {
        display: block;
        width: 100%;
        box-sizing: border-box;
        border-radius: 5px;
        border: 1px solid #CCCCCC;
        background: #FAFAFA;
        padding: 1em;
        margin-bottom: 1.25rem;
        margin-top: 10px;
    }
    ::placeholder{
        font-family: 'Raleway';
    }
    .input-container-password {
        position: relative;
    }
    .input-container-password i {
        position: absolute;
        top: 54%;
        right: 18px;
    }
    .socials {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .socials img {
        width: 18px;
    }
    .social-btn {
        background: #F4F4F4;
        display: flex;
        padding: 10px;
        border-radius: 50%;
        width: 20px;
        height: 20px;
        justify-content: center;
        margin: 0 6px;
    }
    .signup-btn {
        display: block;
        width: 100%;
        background: #213267;
        color: white;
        border: none;
        border-radius: 8px;
        padding: 1rem;
        letter-spacing: 0.5px;
        font-family: 'Raleway';
        font-weight: 800;
        text-transform: uppercase;
    }
    .signup-btn:hover{
        cursor: pointer;
    }
    p{
        text-align: center;
    }
    .word {
        font-size: 16px; 
    }
</style>