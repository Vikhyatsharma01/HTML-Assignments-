grid-dashboard-areas.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Dashboard Areas</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .dashboard {
            display: grid;
            grid-template-areas:
                "header header"
                "sidebar main"
                "footer footer";
            grid-template-columns: 200px 1fr;
            gap: 10px;
            min-height: 100vh;
            padding: 10px;
            background: #f1f5f9;
        }

        header {
            grid-area: header;
            background: #2563eb;
            color: white;
            padding: 20px;
        }

        aside {
            grid-area: sidebar;
            background: #dbeafe;
            padding: 20px;
        }

        main {
            grid-area: main;
            background: white;
            padding: 20px;
        }

        footer {
            grid-area: footer;
            background: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }

        @media (max-width: 600px) {
            .dashboard {
                grid-template-areas:
                    "header"
                    "sidebar"
                    "main"
                    "footer";
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <div class="dashboard">
        <header>
            <h2>My Dashboard</h2>
        </header>

        <aside>
            <h3>Menu</h3>
            <p>Home</p>
            <p>Profile</p>
            <p>Settings</p>
        </aside>

        <main>
            <h2>Welcome!</h2>
            <p>This is the main dashboard area.</p>
            <p>Here you can display your content and reports.</p>
        </main>

        <footer>
            <p>My Dashboard - 2026</p>
        </footer>
    </div>

</body>
</html>
