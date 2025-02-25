<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vente de l'APK Streaming</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Style global */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212; /* Thème noir */
            color: #ffffff; /* Texte en blanc */
            margin: 0;
            padding: 0;
        }

        /* Header */
        header {
            text-align: center;
            padding: 40px;
            background-color: #1f1f1f;
        }

        header h1 {
            font-size: 3em;
            color: #f39c12; /* Or */
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* Sections */
        section {
            padding: 40px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5em;
            color: #f39c12;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        /* Liste de paiement */
        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 10px 0;
        }

        /* Boutons */
        .btn {
            display: inline-block;
            background-color: #f39c12; /* Bouton or */
            color: #fff;
            padding: 12px 30px;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .btn:hover {
            background-color: #e67e22; /* Hover effet orange */
            transform: translateY(-5px); /* Élément qui se soulève légèrement */
        }

        /* Section FAQ */
        #faq p {
            font-size: 1.1em;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: #1f1f1f;
            color: #aaa;
            padding: 20px;
            text-align: center;
        }

        footer a {
            color: #f39c12;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            color: #e67e22;
        }
    </style>
</head>
<body>
    <header>
        <h1>Profitez de votre APK de Streaming à Vie !</h1>
    </header>

    <section id="presentation">
        <h2>Découvrez une application comme Netflix, disponible à vie !</h2>
        <p>Profitez de milliers de films et séries sans abonnement mensuel.</p>
    </section>

    <section id="paiement">
        <h2>Achetez votre APK maintenant</h2>
        <p>Prix unique : <strong>7 000 F CFA</strong></p>
        <p>Paiement disponible via :</p>
        <ul>
            <li>
                <a href="https://checkout.stripe.com/pay/cs_test_12345?success_url=https://wa.me/763170419" target="_blank" class="btn">
                    Payer avec Stripe (Carte VISA / MasterCard)
                </a>
            </li>
            <li><a href="https://wa.me/768189410?text=Je%20souhaite%20effectuer%20un%20paiement%20de%207000%20F%20CFA%20via%20Wave.%20Pouvez-vous%20m'aider%20à%20finaliser%20le%20paiement%20sur%20l'application%20Wave%20?" target="_blank" class="btn">Payer via Wave</a></li>
            <li><a href="https://wa.me/776414182?text=Je%20souhaite%20effectuer%20un%20paiement%20de%207000%20F%20CFA%20via%20Orange%20Money.%20Pouvez-vous%20m'aider%20à%20finaliser%20le%20paiement%20sur%20l'application%20Orange%20Money%20?" target="_blank" class="btn">Payer via Orange Money</a></li>
        </ul>
        <p>Après le paiement, contactez-moi sur WhatsApp pour activer votre abonnement.</p>
        <a href="https://wa.me/763170419" class="btn">Me contacter sur WhatsApp</a>
    </section>

    <section id="fonctionnalites">
        <h2>Fonctionnalités de l’APK</h2>
        <ul>
            <li>Films et séries illimités</li>
            <li>Aucune publicité</li>
            <li>Compatible Android et iPhone</li>
            <li>Qualité HD et 4K</li>
        </ul>
    </section>

    <section id="faq">
        <h2>FAQ</h2>
        <p><strong>Comment obtenir l’APK ?</strong> Après paiement, vous recevrez un lien de téléchargement.</p>
        <p><strong>Quels moyens de paiement ?</strong> Stripe (Carte VISA / MasterCard), Wave, et Orange Money.</p>
        <p><strong>Comment activer l’abonnement ?</strong> Contactez-moi sur WhatsApp après achat.</p>
    </section>

    <footer>
        <p>Contact : <a href="https://wa.me/763170419">WhatsApp</a></p>
    </footer>
</body>
</html>
