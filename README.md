<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Mezu and Knights - Manga by Irash</title>
    <meta name="description" content="Read Mezu and Knights, an epic manga written by Irash featuring funny jokes, sad moments, and epic fights of Mezu Fushira and his elemental knights!">
    <meta name="keywords" content="Mezu and Knights, Irash, Manga, Mezu Fushira, Fire Knight, Lightning Knight, Wind Knight, Water Knight">
    <meta name="author" content="Irash">

    <style>
        body {
            text-align: center;
            font-family: 'Arial Black', Gadget, sans-serif;
            background-color: #0d0d0d;
            color: white;
            margin: 0;
            padding: 20px;
        }

        /* Anime / Naruto / JJK Style එකට හැදූ මාතෘකාව */
        .anime-title {
            font-size: 55px;
            font-weight: 900;
            color: #ff3c00;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 
                -3px -3px 0 #000,  
                 3px -3px 0 #000,
                -3px  3px 0 #000,
                 3px  3px 0 #000,
                 5px  5px 0px #ffcc00,
                 8px  8px 15px rgba(0,0,0,0.8);
            margin-top: 30px;
            margin-bottom: 10px;
        }

        /* හැඳින්වීම සඳහා ස්ටයිල් එක */
        .intro-text {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 19px;
            color: #e0e0e0;
            max-width: 750px;
            margin: 0 auto 40px auto;
            line-height: 1.6;
            background-color: #1a1a1a;
            padding: 15px;
            border-radius: 8px;
            border-left: 5px solid #ff3c00;
        }

        /* උපමාතෘකා සඳහා ස්ටයිල් */
        h2 {
            color: #ffcc00;
            text-transform: uppercase;
            font-size: 28px;
            margin-top: 50px;
            border-bottom: 2px solid #ffcc00;
            display: inline-block;
            padding-bottom: 5px;
        }

        h3, h4 {
            color: #ffffff;
            font-size: 22px;
            margin-top: 15px;
            margin-bottom: 5px;
        }

        /* චරිත වල විස්තර සඳහා ස්ටයිල් */
        p {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #cccccc;
            font-size: 16px;
            margin-top: 5px;
            margin-bottom: 30px;
        }

        /* පින්තූර මැදට ගෙන ලස්සන කිරීමට */
        img {
            display: block;
            margin: 20px auto 10px auto;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(255, 60, 0, 0.3);
        }

        /* --- Rating System Styles --- */
        .rating-box {
            background-color: #1a1a1a;
            max-width: 400px;
            margin: 50px auto 30px auto;
            padding: 20px;
            border-radius: 10px;
            border: 2px solid #ffcc00;
            box-shadow: 0 0 15px rgba(255, 204, 0, 0.2);
        }

        .rating-box h3 {
            color: #ffcc00;
            margin-top: 0;
            font-family: 'Arial Black', sans-serif;
        }

        .stars {
            font-size: 40px;
            cursor: pointer;
            user-select: none;
            margin-bottom: 15px;
        }

        .star {
            color: #444;
            transition: color 0.2s ease;
        }

        .star:hover,
        .star.selected {
            color: #ffcc00;
        }

        /* Submit බටන් එකේ ස්ටයිල් */
        .submit-btn {
            background-color: #ff3c00;
            color: white;
            border: none;
            padding: 10px 25px;
            font-size: 16px;
            font-family: 'Arial Black', sans-serif;
            text-transform: uppercase;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.2s;
            box-shadow: 0 4px 10px rgba(255, 60, 0, 0.4);
        }

        .submit-btn:hover {
            background-color: #ffcc00;
            color: black;
        }

        .thank-you-msg {
            font-family: 'Segoe UI', sans-serif;
            font-size: 16px;
            color: #00ffcc;
            margin-top: 15px;
            display: none;
        }
    </style>
</head>
<body>

    <h1 class="anime-title">Mezu and Knights</h1>
    
    <div class="intro-text">
        This is an manga written by <strong>Irash</strong>. It has funny jokes, sad moments, and epic fights! The main character of this manga is <strong>Mezu Fushira</strong>.
    </div>

    <h2>Mezu and his knights</h2>
    
    <img src="mezu.png" alt="Mezu Fushira - Main Character of Mezu and Knights" width="400">
    <h3>This is Mezu</h3>
    
    <img src="goki.png" alt="Goki the Fire Knight - Mezu and Knights" width="400">
    <h4>Goki is the Fire Knight</h4>
    <p>His weapon is a sword. He can control fire.</p>
    
    <img src="raisen.png" alt="Raisen the Lightning Knight - Mezu and Knights" width="400">
    <h4>Raisen is the Lightning Knight</h4>
    <p>He has a nunchaku. He can control lightning.</p>

    <img src="gale.png" alt="Gale the Wind Knight - Mezu and Knights" width="400">
    <h4>Gale is the Wind Knight</h4>
    <p>He has a wind bow and arrows. He can control wind.</p>

    <img src="torrent.png" alt="Torrent the Water Knight - Mezu and Knights" width="400">
    <h4>Torrent is the Water Knight</h4>
    <p>He has water knives. He can control water.</p>

    <div class="rating-box">
        <h3>Rate this Manga!</h3>
        <div class="stars" id="star-container">
            <span class="star" data-value="1">★</span>
            <span class="star" data-value="2">★</span>
            <span class="star" data-value="3">★</span>
            <span class="star" data-value="4">★</span>
            <span class="star" data-value="5">★</span>
        </div>
        <button class="submit-btn" id="submit-rating">Submit</button>
        <div class="thank-you-msg" id="thank-you">Rating Submitted! Thank you! ⭐</div>
    </div>

    <script>
        const stars = document.querySelectorAll('.star');
        const submitBtn = document.getElementById('submit-rating');
        const thankYouMsg = document.getElementById('thank-you');
        let selectedRating = 0;

        stars.forEach(star => {
            star.addEventListener('mouseover', function() {
                highlightStars(this.getAttribute('data-value'));
            });

            star.addEventListener('mouseout', function() {
                resetStars();
            });

            star.addEventListener('click', function() {
                selectedRating = this.getAttribute('data-value');
                stars.forEach((s, index) => {
                    if (index < selectedRating) {
                        s.classList.add('selected');
                    } else {
                        s.classList.remove('selected');
                    }
                });
            });
        });

        function highlightStars(value) {
            stars.forEach((star, index) => {
                star.style.color = (index < value) ? '#ffcc00' : '#444';
            });
        }

        function resetStars() {
            stars.forEach((star, index) => {
                star.style.color = (index < selectedRating) ? '#ffcc00' : '#444';
            });
        }

        // Google Form Submission
        submitBtn.addEventListener('click', function() {
            if (selectedRating === 0) {
                alert("Please select a star rating first!");
                return;
            }

            // ඔයාගේ Google Form එකේ ID සහ Entry ID එක මෙතනට ඇතුළත් කරලා තියෙන්නේ
            const formID = "1FAIpQLSeIHHynFhG2uI9H7fH06OWTAqXG-JXzJMqKqOJux0IPtnNRvQ"; 
            const entryID = "entry.451870787"; 

            const formUrl = `https://docs.google.com/forms/d/e/${formID}/formResponse`;
            
            const formData = new FormData();
            formData.append(entryID, selectedRating);

            fetch(formUrl, {
                method: 'POST',
                mode: 'no-cors',
                body: formData
            }).then(() => {
                submitBtn.style.display = 'none';
                document.getElementById('star-container').style.pointerEvents = 'none'; 
                thankYouMsg.style.display = 'block';
            }).catch(err => {
                alert("Something went wrong. Try again!");
            });
        });
    </script>

</body>
</html>
