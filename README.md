<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ηλεκτρολόγος Ρέθυμνο - Κωνσταντίνος Βλάχος</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0d47a1, #1976d2);
            color: white;
            padding: 50px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        .container {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        h2 {
            color: #0d47a1;
            text-align: center;
        }

        .services, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .box {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            text-align: center;
        }

        .box img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        @media (max-width: 600px) {
            .box {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Κωνσταντίνος Βλάχος</h1>
        <p>Ηλεκτρολόγος στο Ρέθυμνο</p>
    </header>

    <div class="container">
        <h2>Υπηρεσίες</h2>
        <div class="services">
            <div class="box">
                <img src="https://images.unsplash.com/photo-1600508771377-144c1f76d8cd?auto=format&fit=crop&w=800&q=60" alt="Βλάβες">
                <h3>Βλάβες</h3>
                <p>Άμεση αποκατάσταση ηλεκτρολογικών προβλημάτων.</p>
            </div>
            <div class="box">
                <img src="https://images.unsplash.com/photo-1581093588401-7b5ded8d8d1b?auto=format&fit=crop&w=800&q=60" alt="Εγκαταστάσεις">
                <h3>Εγκαταστάσεις</h3>
                <p>Ηλεκτρολογικές εγκαταστάσεις κατοικιών και επιχειρήσεων.</p>
            </div>
            <div class="box">
                <img src="https://images.unsplash.com/photo-1581090700227-1e8b9b6c03dc?auto=format&fit=crop&w=800&q=60" alt="Πιστοποιητικά ΔΕΔΔΗΕ">
                <h3>Πιστοποιητικά</h3>
                <p>Έκδοση πιστοποιητικών ΔΕΔΔΗΕ για κάθε χρήση.</p>
            </div>
        </div>

        <h2>Επικοινωνία</h2>
        <div class="contact">
            <div class="box">
                <img src="https://images.unsplash.com/photo-1525186402429-b4ff38bedec6?auto=format&fit=crop&w=800&q=60" alt="Τηλέφωνο">
                <h3>Τηλέφωνο</h3>
                <p>6979397503</p>
            </div>
            <div class="box">
                <img src="https://images.unsplash.com/photo-1588702547923-7093a6c3ba33?auto=format&fit=crop&w=800&q=60" alt="Email">
                <h3>Email</h3>
                <p>vldinos12@gmail.com</p>
            </div>
        </div>
    </div>
</body>
</html>
