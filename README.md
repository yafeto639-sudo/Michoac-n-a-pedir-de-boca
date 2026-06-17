<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Michoacán a pedir de boca - Order Online</title>
    <style>
        :root {
            --primary-pink: #e21b79;
            --secondary-orange: #ff7a00;
            --dark-brown: #3d1c06;
            --light-bg: #fff5f8;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--light-bg);
            color: var(--dark-brown);
        }

        header {
            background: linear-gradient(135deg, var(--primary-pink), var(--secondary-orange));
            color: var(--white);
            text-align: center;
            padding: 3rem 1rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.2rem;
            font-weight: 300;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .intro-text {
            text-align: center;
            margin-bottom: 3rem;
            font-size: 1.1rem;
        }

        .store-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
        }

        .store-card {
            background-color: var(--white);
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.06);
            border-top: 5px solid var(--primary-pink);
            transition: transform 0.3s ease;
        }

        .store-card:hover {
            transform: translateY(-5px);
        }

        .store-info {
            padding: 1.5rem;
        }

        .store-name {
            font-size: 1.4rem;
            color: var(--primary-pink);
            margin-bottom: 0.5rem;
        }

        .store-address, .store-phone {
            font-size: 0.95rem;
            margin-bottom: 0.4rem;
            color: #666;
        }

        .order-section {
            background-color: #fafafa;
            padding: 1.5rem;
            border-top: 1px solid #eee;
        }

        .order-title {
            font-size: 1rem;
            font-weight: 600;
            margin-bottom: 1rem;
            text-transform: uppercase;
            color: var(--dark-brown);
            letter-spacing: 0.5px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 0.75rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            font-size: 0.95rem;
            transition: opacity 0.2s ease;
        }

        .btn:hover {
            opacity: 0.9;
        }

        .btn:last-child {
            margin-bottom: 0;
        }

        .doordash {
            background-color: #FF3008;
            color: white;
        }

        .ubereats {
            background-color: #06C167;
            color: white;
        }

        .grubhub {
            background-color: #f6343f;
            color: white;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: var(--dark-brown);
            color: var(--white);
            margin-top: 4rem;
            font-size: 0.9rem;
        }

        @media (max-width: 600px) {
            header h1 { font-size: 2rem; }
            .store-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Michoacán a pedir de boca</h1>
        <p>¡Paletas, Helados y Antojitos Mexicanos Auténticos!</p>
    </header>

    <div class="container">
        <p class="intro-text">Select your nearest location below to view contact details or order directly through your favorite delivery platform.</p>
        
        <div class="store-grid">

            <!-- STORE 1: LAWRENCEVILLE -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">Lawrenceville, GA</h2>
                    <p class="store-address">📍 1685 Old Norcross Rd, Lawrenceville, GA 30046</p>
                    <p class="store-phone">📞 Phone: Contact Info Online</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://www.doordash.com/store/michoacan-a-pedir-de-boca-lawrenceville-24987936/" target="_blank" class="btn doordash">Order on DoorDash</a>
                    <a href="https://order.online/store/michoacan-a-pedir-de-boca-old-norcross-rd-24987936" target="_blank" class="btn ubereats">Order via Uber Eats / Direct</a>
                </div>
            </div>

            <!-- STORE 2: CONYERS -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">Conyers, GA</h2>
                    <p class="store-address">📍 1820 Hwy 20, Ste 138, Conyers, GA 30013</p>
                    <p class="store-phone">📞 Phone: Contact Info Online</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://www.doordash.com/store/michoacan-a-pedir-de-boca-conyers-35369635/" target="_blank" class="btn doordash">Order on DoorDash</a>
                    <a href="https://www.ubereats.com/store/michoacan-a-pedir-de-boca-conyers/N_Qufg3KRJiDfAwVs9QdMg" target="_blank" class="btn ubereats">Order on Uber Eats</a>
                </div>
            </div>

            <!-- STORE 3: FORT WORTH -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">Fort Worth, TX</h2>
                    <p class="store-address">📍 1920 Ephriham Ave, Fort Worth, TX 76164</p>
                    <p class="store-phone">📞 Phone: (817) 420-9422</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://www.grubhub.com/restaurant/michoacan-a-pedir-de-boca-1920-ephriham-ave-fort-worth/1721021" target="_blank" class="btn grubhub">Order on Grubhub</a>
                    <a href="https://www.ubereats.com/store/michoacan-a-pedir-de-boca/FnOGeJi_VHaW2xOYqIBVpQ" target="_blank" class="btn ubereats">Order on Uber Eats</a>
                </div>
            </div>

            <!-- STORE 4: THOUSAND OAKS -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">Thousand Oaks, CA</h2>
                    <p class="store-address">📍 1044 E Avenida De Los Arboles, Thousand Oaks, CA 91360</p>
                    <p class="store-phone">📞 Phone: See Yelp/Store Info</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://www.doordash.com/store/michoac%C3%A1n-a-pedir-de-boca-thousand-oaks-31077547/" target="_blank" class="btn doordash">Order on DoorDash</a>
                    <a href="https://www.ubereats.com/store/michoacan-a-pedir-de-boca/Mt4pkKBkTW2y-UVnEixOFA" target="_blank" class="btn ubereats">Order on Uber Eats</a>
                </div>
            </div>

            <!-- STORE 5: BOERNE -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">Boerne, TX</h2>
                    <p class="store-address">📍 109 Waterview Pkwy Ste 102, Boerne, TX 78006</p>
                    <p class="store-phone">📞 Phone: (830) 331-4073</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://doordash.com" target="_blank" class="btn doordash">Order on DoorDash</a>
                    <a href="https://www.ubereats.com/store/michoacan-a-pedir-de-boca-boerne-109-waterview-pkwy/TUmrh0hsVxm_FOe1RFDxsg" target="_blank" class="btn ubereats">Order on Uber Eats</a>
                </div>
            </div>

            <!-- STORE 6: EAST MEADOW -->
            <div class="store-card">
                <div class="store-info">
                    <h2 class="store-name">East Meadow, NY (Long Island)</h2>
                    <p class="store-address">📍 342 Newbridge Rd, East Meadow, NY 11554</p>
                    <p class="store-phone">📞 Phone: (516) 519-6130</p>
                </div>
                <div class="order-section">
                    <p class="order-title">Order Delivery</p>
                    <a href="https://www.doordash.com/" target="_blank" class="btn doordash">Check Local DoorDash</a>
                    <a href="https://www.ubereats.com/" target="_blank" class="btn ubereats">Check Local Uber Eats</a>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2026 Michoacán a pedir de boca Directory. All links point to official marketplace store handles.</p>
    </footer>

</body>
</html>
