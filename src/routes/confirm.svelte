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
            <h2>Forgot Password?</h2>
        </div>
        <div class="sect3">
            <i class="fi fi-rr-eye"></i>
        </div>
    </div>
    
    <form>
        <h1>Recovery Email Sent</h1>
        <p>An email has bee sent to you with a link to recover your password</p>
        <a href="login">
            <button class="continue-btn" type="submit">Go back to login</button>
        </a>
        
    </form>

    <div class="word">
        <p>Remember? <a href="/signup"> <strong>continue</strong></a></p>
    </div>
</main>

<style>
    main {
        width: 100%;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        font-family: 'Raleway';
        justify-content: space-between;
    }
    .head {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        margin-top: 20px;

    }
    .word {
        bottom: 0;
        text-align: center;
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
    a {
        text-decoration: none;
        color: #1C89A7;
        font-weight: bolder;
    }
    label{
        font-weight: bold;
    }
    form {
        padding: 0 20px;
    }
    form input[type="email"] {
        display: block;
        width: 100%;
        box-sizing: border-box;
        border-radius: 5px;
        border: 1px solid #CCCCCC;
        background: #FAFAFA;
        padding: 1em;
        margin-bottom: 1.25rem;
        margin-top: 10px;
        height: 48px;
    }
    .continue-btn {
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
        height: 56px;
    }
    .continue-btn:hover{
        cursor: pointer;
    }
    h1 {
        font-weight: 700;
        font-size: 24px;
    }
    p {
        font-weight: 500;
        font-size: 14px;
        margin-bottom: 30px;
    }
</style>
