<svelte:head>
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css'>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700;800&display=swap" rel="stylesheet">
</svelte:head>

<main>
    <form>
        <div class="logo">
            <img src="https://i.postimg.cc/d1B4zpzN/image-1.png" alt="logo">
            <h2>Welcome!</h2>
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
        <div class="psd"><a href="/forgot_psd">Forgot Password?</a></div>
        <button class="login-btn" type="submit">Login</button>
        <p>Or login with</p>
        <div class="socials">
            <div class="social-btn">
                <a href="/">
                    <img src="https://i.postimg.cc/Qdy15tzD/google.png" alt="google">
                </a>
            </div>
        </div>
    </form>
    <div class="word">
        <p>Don't have an account? <a href="/signup"> <strong>Sign Up</strong></a></p>
    </div>
    
</main>


<style>
     :root {
        font-size: 108%;
        font-size: 14px;
        line-height: 1.5; 
        --link: #1C89A7;
        --btn: #213267;
        }
        p{
        font-weight: bold;
        text-align: center;
        margin-top: 40px;
    }
    h1 {
        font-size: 24px;
        font-weight: bolder;
    }
    a {
        text-decoration: none;
        color: #1C89A7;
        font-weight: bolder;
    }
    a:hover {
        text-decoration: underline;
    }
    i {
        color: black
    }
    label{
        font-weight: bold;
    }
    .psd {
        text-align: right;
        padding-bottom: 10px;
    }
    .word {
        font-size: 16px;
        text-align: left;
    }
    form {
        background: rgba(255, 255, 255, 0.801);
        backdrop-filter: blur(50px);
        border-radius: 10px;
        z-index: 1;
        padding: 20px;
    }
    main {
        height: 100vh;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        font-family: 'Raleway';
    }
    form input[type="email"], form input[type="password"] {
        display: block;
        width: 100%;
        box-sizing: border-box;
        border-radius: 5px;
        border: 1px solid #CCCCCC;
        background: #FAFAFA;
        padding: 1em;
        margin-bottom: 1.25rem;
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
    .login-btn {
        display: block;
        width: 100%;
        background: var(--btn);
        color: white;
        border: none;
        border-radius: 8px;
        padding: 1rem;
        letter-spacing: 0.5px;
        font-family: 'Raleway';
        font-weight: 800;
        text-transform: uppercase;
    }
    .login-btn:hover{
        cursor: pointer;
    }
    .right .copy {
        text-align: left;
    }
    .right .copy p {
        font-size: 14px;
    }
    .logo {
        text-align: center;
        width: 100%;
        margin-bottom: 40px;
    }
    .logo img {
        width: 130px;
    }
    .logo h2 {
        font-size: 16px;
        font-weight: 600;
        line-height: 21px;
    }
</style>