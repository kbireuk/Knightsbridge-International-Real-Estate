<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Knightsbridge International Real Estate | London Property Experts</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #1a2e3b;
            --primary-light: #2c4a5e;
            --accent: #c5a880;
            --text-dark: #222222;
            --text-light: #666666;
            --background-light: #f8f9fa;
            --white: #ffffff;
            --shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            --radius: 12px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Inter', sans-serif;
            color: var(--text-dark);
            line-height: 1.6;
            background-color: var(--white);
        }

        /* Top Bar */
        .top-bar {
            background-color: var(--primary);
            color: var(--white);
            padding: 10px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 14px;
        }

        .top-bar a {
            color: var(--white);
            text-decoration: none;
            margin-right: 20px;
            transition: color 0.3s;
        }

        .top-bar a:hover {
            color: var(--accent);
        }

        .region-selector a {
            margin-left: 15px;
            margin-right: 0;
            font-weight: 600;
        }

        /* Navigation */
        header {
            background: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo h1 {
            font-size: 22px;
            font-weight: 700;
            color: var(--primary);
            letter-spacing: 1px;
        }

        .logo span {
            color: var(--accent);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--primary);
            font-weight: 500;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--accent);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(26, 46, 59, 0.6), rgba(26, 46, 59, 0.7)), url('https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--white);
            padding: 0 20px;
        }

        .hero h2 {
            font-size: 48px;
            font-weight: 700;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
            font-weight: 300;
        }

        /* Search Web 2.0 Component */
        .search-container {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            padding: 30px;
            border-radius: var(--radius);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 900px;
        }

        .search-tabs {
            display: flex;
            margin-bottom: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.2);
        }

        .tab {
            padding: 10px 25px;
            cursor: pointer;
            background: none;
            border: none;
            color: var(--white);
            font-size: 16px;
            font-weight: 600;
            opacity: 0.7;
            transition: all 0.3s;
        }

        .tab.active {
            opacity: 1;
            border-bottom: 3px solid var(--accent);
        }

        .search-fields {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr
