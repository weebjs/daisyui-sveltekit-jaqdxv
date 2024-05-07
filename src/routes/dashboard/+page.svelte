<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RattleRoar</title>
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js" nomodule></script>
</head>

<dialog id="my_modal_1" class="modal">
    <div class="modal-box w-9/9 max-w">
        <aside class="flex flex-col items-center h-screen sticky top-0 overflow-y-auto space-y-4  py-6 px-4 bg-base-100 rounded-xl ">
            <!-- Logo -->
        
            <img alt="Profile" src="https://cdn.gilcdn.com/ContentMediaGenericFiles/0fd43894688704e3b129d64fac4bd441-Full.webp?Expires=1715053235&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4uZ2lsY2RuLmNvbS8qIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNzE1MDUzMjM1fSwiSXBBZGRyZXNzIjp7IkFXUzpTb3VyY2VJcCI6IjE2NS4xNTUuMTcyLjEifX19XX0_&Signature=LMV1MopsMAopv5MeLriqFIqvHJE0zjSBzV7Oo3QSfx6l5vwenBi0uNKuznXpdEWe5twMaCZXPht90aINq7vx118TVbh3NS2oMzvyfiwBIkNywWv05tDiF9fKmKeLMp9etT-OkOuD4SbRzftaVQ12kPtz2ykV7pkoO2enGnmlW9hDZcKIfsOMm0%7E6osVkny5jWb9tVVuZmlU1Ir1NknOhbqcwJSYnFzJX-it9LQQZzhLzy7Zak%7EVMCNL1cUwU4UXYdQd0rmHED2u%7EpnTBqLzCsOegmivwcaVJXLCGOs6JyhrAVaoXxxX78JXxqU5zy0FM8aHNaXBU2NnU1X7ypaXOng__&Key-Pair-Id=K1FFKFZRWAZSB" class="w-32 rounded-full"/>
        
            <h2 class="font-bold text-lg">Default</h2>
        
            <span class="text-sm text-accent">username@email.com</span>
        
            <ul class="menu menu-lg w-full">
                <li>
                    <a>
                        <i class="fa-solid fa-inbox fa-fw"></i>
                        Inbox
                    </a>
                </li>
                <li>
                    <a class="active">
                        <i class="fa-solid fa-user fa-fw"></i>
                        Accounts
                    </a>
                </li>
                <li>
                    <a>
                        <i class="fa-solid fa-gear fa-fw"></i>
                        Settings
                    </a>
                </li>
            </ul>
        </aside>
        <form method="dialog">
            <button class="btn btn-sm btn-circle btn-ghost absolute right-2 top-2">✕</button>
          </form>
        </dialog>

<div class="dropdown">
    <div tabindex="0" role="button" class="btn btn-square mb-1 ml-3 mt-2 ">
        <ion-icon name="ellipsis-vertical-outline"></ion-icon>
    </div>

    <ul tabindex="0" class="dropdown-content z-[1] menu p-2 shadow bg-base-200 rounded-box w-52">
        <li><a onclick="my_modal_1.showModal()">View profile</a></li>
        <li><a>Settings</a></li>
        <div class="divider my-0"></div>
        <li><a>Help</a></li>
        <li><a>Sign out</a></li>
    </ul>
</div>