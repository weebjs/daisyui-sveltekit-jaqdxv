
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login | RattleRoar</title>
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
    <div class="flex justify-center items-center h-screen">
        <div class="flex flex-col gap-4 rounded-box bg-base-100 p-6 max-w-md mt-[0rem]">
            <h1 class="text-3xl font-bold self-center">Log in</h1>
            
            <span class="self-center">
                Don't have an account?
                <a class="link underline" href="/register">Register</a>
            </span>
            
            <label class="form-control">
                <div class="label">
                    <span class="label-text">Email</span>
                </div>
            
                <input class="input input-bordered" />
            </label>
            
            <label class="form-control">
                <div class="label">
                    <span class="label-text">Password</span>
                    <a class="label-text link underline" href="/reset">Forgot password?</a>
                </div>
            
                <input type="password" class="input input-bordered" />
            </label>
            
            <div class="form-control">
                <label class="cursor-pointer label self-start gap-2">
                    <input type="checkbox" class="checkbox" />
                    <span class="label-text">Remember me</span>
                </label>
            </div>
            
            
            <button class="btn bg-orange">Log in
                <ion-icon name="log-in-outline"></ion-icon>
            </button>
        </div>
    </div>

    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
</body>
