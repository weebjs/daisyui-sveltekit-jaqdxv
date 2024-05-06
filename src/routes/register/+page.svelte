<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Register | RattleRoar</title>
</head>
<body>
  <div class="flex justify-center items-center h-screen">
      <div class="flex flex-col gap-4 rounded-box bg-base-100 p-6 max-w-md">
          <h1 class="text-3xl font-bold self-center">Create an account</h1>

          <span class="self-center">
              Already have an account?
              <a class="link underline" href="/login">Log in</a>
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
              </div>
              <input type="password" class="input input-bordered" />
          </label>

          <label class="form-control">
              <div class="label">
                  <span class="label-text">Confirm password</span>
              </div>
              <input type="password" class="input input-bordered" />
          </label>

          <div class="form-control">
              <label class="cursor-pointer label self-start gap-2">
                  <input type="checkbox" class="checkbox" />
                  <span class="label-text">
                      I accept the
                      <a class="link underline">Terms and Conditions</a>
                  </span>
              </label>
          </div>

          <button class="btn bg-orange">Create
            <ion-icon name="create-outline"></ion-icon>
          </button>
      </div>
  </div>

  <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js" nomodule></script>
</body>