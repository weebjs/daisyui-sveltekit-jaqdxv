<head>
    <title>Login | RattleRoar</title>
    <link rel="icon" type="image/x-icon" href="/images/favicon.png">
</head>

<script>
    import { Turnstile } from 'svelte-turnstile';
    //TODO: Work on signin querry
    /**
     * @param {CustomEvent} token
     */
    const setToken = (token) => {
        console.log(token);
    }
</script>

<body>
    <div class="hero min-h-screen bg-base-200">
        <div class="hero-content">
            <h1 class="text-4xl font-bold">
                Login
            </h1>
            <p class="text-lg text-gray-500 mt-2 create-account" style="margin-top: -20px;">
                Don't have an account? <a class="link underline" href="/register">Register</a>
            </p>
            <div class="input-group">
                <label class="input input-bordered flex items-center">
                    <img src="images/email.svg" alt="fontawesome-icon" class="w-4 h-4 opacity-70" />
                    <input type="text" class="grow" placeholder="Email" />
                </label>
                <label class="input input-bordered flex items-center second-label">
                    <img src="images/password.svg" alt="fontawesome-icon" class="w-4 h-4 opacity-70" />
                    <input type="password" class="grow" placeholder="Password" />
                </label>
                <p class="text-sm text-gray-500 mt-1" style="margin-top: -10px;">
                    <a class="underline" href="/reset">Forgot your password?</a>
                </p>
                <Turnstile siteKey="0x4AAAAAAAVhwQ_4KwtEYmQ4" on:turnstile-callback={setToken} />
                <button class="btn btn-neutral text-2x bg-orange" style="color: white;">
                    Log In <ion-icon name="log-in-outline"></ion-icon>
                </button>
            </div>
        </div>
    </div>

    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>