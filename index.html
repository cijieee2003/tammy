<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form with Flower Rain and Fireworks</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f0f0f0, #d4f0ff);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
            transition: background-color 0.5s ease;
        }
        .login-container {
            background: linear-gradient(135deg, #ffffff, #f1f1f1);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.15);
            width: 320px;
            text-align: center;
            z-index: 10;
            transition: all 0.5s ease;
        }
        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 12px;
            margin: 12px 0;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
            font-size: 16px;
        }
        button {
            background: linear-gradient(135deg, #28a745, #218838);
            color: #fff;
            padding: 12px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background 0.3s, transform 0.3s;
        }
        button:hover {
            background: linear-gradient(135deg, #218838, #1e7e34);
            transform: scale(1.05);
        }

        .birthday-text {
            display: none; /* Hide initially */
            font-size: 24px;
            color: #ff5733;
            cursor: pointer;
            text-align: center;
            font-weight: bold;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 5;
            transition: color 0.3s, transform 0.3s;
        }

        .birthday-text:hover {
            color: #ff704d;
            transform: translate(-50%, -50%) scale(1.05);
        }

        .flower {
            position: absolute;
            font-size: 30px;
            opacity: 0.8;
            animation: fall linear forwards;
        }

        @keyframes fall {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }

        .firework {
            position: absolute;
            border-radius: 50%;
            opacity: 0.8;
            animation: explode 1s ease-out forwards;
        }

        @keyframes explode {
            0% {
                width: 0;
                height: 0;
                opacity: 1;
            }
            100% {
                width: 100px;
                height: 100px;
                opacity: 0;
            }
        }

        .birthday-message {
            display: none; /* Hidden initially */
            position: absolute;
            top: 60%; /* Adjust as needed */
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 20px;
            color: #4caf50;
            text-align: center;
            z-index: 5;
        }

        /* Loading Spinner */
        .loading-spinner {
            display: none; /* Initially hidden */
            border: 8px solid #f3f3f3;
            border-radius: 50%;
            border-top: 8px solid #3498db;
            width: 50px;
            height: 50px;
            animation: spin 2s linear infinite;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 10;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Quiz Styles */
        .quiz-container {
            display: none; /* Hidden initially */
            position: absolute;
            top: 50%; /* Adjust as needed */
            left: 50%;
            transform: translate(-50%, -50%);
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.15);
            padding: 20px;
            width: 300px;
            z-index: 10;
        }

        .quiz-question {
            font-size: 18px;
            margin: 10px 0;
        }

        .quiz-answer {
            display: block;
            margin: 5px 0;
            cursor: pointer;
            background: #e0e0e0;
            padding: 10px;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .quiz-answer:hover {
            background: #d0d0d0;
        }

        .result-message {
            font-size: 20px;
            color: #4caf50;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="login-container" id="loginContainer">
        <h2>Login</h2>
        <input type="text" id="username" placeholder="Username"><br>
        <input type="password" id="password" placeholder="Password"><br>
        <button onclick="login()">Log In</button>
    </div>

    <!-- Loading Spinner -->
    <div class="loading-spinner" id="loadingSpinner"></div>

    <!-- Quiz Container -->
    <div class="quiz-container" id="quizContainer">
        <div class="quiz-question" id="quizQuestion"></div>
        <div class="quiz-answer" onclick="selectAnswer(0)" id="answer0"></div>
        <div class="quiz-answer" onclick="selectAnswer(1)" id="answer1"></div>
        <div class="quiz-answer" onclick="selectAnswer(2)" id="answer2"></div>
        <div class="result-message" id="resultMessage"></div>
    </div>

    <div class="birthday-text" id="birthdayText" onclick="startFlowerRain(); startFireworks();">
         Happy Birthday Loveeee !!! 
    </div>

    <div class="birthday-message" id="birthdayMessage">
        "Happy 21st Birthday! You mean the world to me, and I'm so grateful to celebrate this special day with you. I love you!"
    </div>
    
    <div class="birthday-message" id="secondBirthdayMessage">
        "Cheers to many more adventures together! Let's make this year unforgettable!"
    </div>

    <div class="birthday-message" id="thirdBirthdayMessage">
        "On your special day, I wish you all the happiness in the world. You deserve it and so much more!"
    </div>

    <div class="birthday-message" id="fourthBirthdayMessage">
        "May your day be filled with love, laughter, and all the things that bring you joy. Happy Birthday!"
    </div>

    <script>
    let currentMessageIndex = 0; // To track which message is currently displayed
    const messages = [
        'birthdayMessage',
        'secondBirthdayMessage',
        'thirdBirthdayMessage',
        'fourthBirthdayMessage'
    ];

    let clickCounter = 0; // To track how many times 'Happy Birthday Loveeee' is clicked
    const maxClicks = 10; // Maximum number of clicks before reset

    // Quiz Questions
    const quizQuestions = [
        {
            question: "What is the name of our first dog?",
            answers: ["Coco", "Tammy", "Oreo"],
            correct: 1 // Index of the correct answer
        },
        {
            question: "What is your favorite animal?",
            answers: ["Dog", "Cat", "Bird"],
            correct: 0 // Index of the correct answer
        },
        {
            question: "What is your favorite food?",
            answers: ["Bread", "Fish", "Burger"],
            correct: 2 // Index of the correct answer
        }
    ];

    let currentQuizIndex = 0;

    function login() {
        const correctUsername = 'jizame';
        const correctPassword = '10-22-03';

        const username = document.getElementById('username').value;
        const password = document.getElementById('password').value;

        if (username === correctUsername && password === correctPassword) {
            document.getElementById('loginContainer').style.display = 'none';
            showLoadingSpinner(); // Show loading spinner before quiz
            setTimeout(() => {
                hideLoadingSpinner();
                showQuiz(); // Show quiz after loading spinner
            }, 2000); // Simulate 2-second loading
        } else {
            alert('Incorrect username or password. Try again.');
        }
    }

    function showLoadingSpinner() {
        document.getElementById('loadingSpinner').style.display = 'block';
    }

    function hideLoadingSpinner() {
        document.getElementById('loadingSpinner').style.display = 'none';
    }

    function startFlowerRain() {
        const flowerCount = 30; // Reduced number of flowers for better arrangement
        for (let i = 0; i < flowerCount; i++) {
            const flower = document.createElement('div');
            flower.classList.add('flower');
            flower.innerHTML = "🌸";
            flower.style.left = `${Math.random() * 100}vw`; // Random horizontal position
            flower.style.top = `${Math.random() * -50}px`; // Start from above the viewport
            flower.style.animationDuration = `${Math.random() * 3 + 2}s`; // Random duration
            document.body.appendChild(flower);

            // Remove flower after animation completes
            flower.addEventListener('animationend', () => {
                flower.remove();
            });
        }
    }

    function startFireworks() {
        const fireworkCount = 5; // Number of fireworks
        for (let i = 0; i < fireworkCount; i++) {
            const firework = document.createElement('div');
            firework.classList.add('firework');
            firework.style.left = `${Math.random() * 100}vw`;
            firework.style.top = `${Math.random() * 100}vh`;
            firework.style.backgroundColor = `rgba(255, ${Math.random() * 255}, 0, 1)`; // Random color
            firework.style.animationDuration = `${Math.random() * 1 + 1}s`; // Random duration
            document.body.appendChild(firework);

            // Remove firework after animation completes
            firework.addEventListener('animationend', () => {
                firework.remove();
            });
        }
    }

    function showQuiz() {
        document.getElementById('quizContainer').style.display = 'block';
        loadQuizQuestion();
    }

    function loadQuizQuestion() {
        const question = quizQuestions[currentQuizIndex];
        document.getElementById('quizQuestion').innerText = question.question;
        document.getElementById('answer0').innerText = question.answers[0];
        document.getElementById('answer1').innerText = question.answers[1];
        document.getElementById('answer2').innerText = question.answers[2];
        document.getElementById('resultMessage').innerText = ''; // Reset message
    }

    function selectAnswer(index) {
        const question = quizQuestions[currentQuizIndex];
        const isCorrect = index === question.correct;
        document.getElementById('resultMessage').innerText = isCorrect ? "Correct!" : "Wrong answer!";

        if (!isCorrect) {
            // If the answer is wrong, reset the quiz
            currentQuizIndex = 0;
            setTimeout(() => {
                document.getElementById('quizContainer').style.display = 'none'; // Hide quiz
                alert("Incorrect answer! Starting over...");
                showQuiz(); // Restart quiz
            }, 2000); // Show message for 2 seconds before restarting
        } else {
            // Move to the next question or finish the quiz
            currentQuizIndex++;
            if (currentQuizIndex < quizQuestions.length) {
                setTimeout(loadQuizQuestion, 2000); // Load next question after 2 seconds
            } else {
                // Show birthday message after all questions are answered correctly
                setTimeout(() => {
                    document.getElementById('quizContainer').style.display = 'none'; // Hide quiz
                    showBirthdayMessage(); // Show birthday message
                }, 2000); // Show message for 2 seconds before revealing birthday message
            }
        }
    }

    function showBirthdayMessage() {
        if (currentMessageIndex < messages.length) {
            const messageId = messages[currentMessageIndex];
            const messageElement = document.getElementById(messageId);
            messageElement.style.display = 'block';
            messageElement.style.opacity = 1;
            messageElement.style.transition = 'opacity 0.5s ease-in';

            const randomEffect = Math.random() < 0.5 ? startFlowerRain : startFireworks;
            randomEffect();

            setTimeout(() => {
                messageElement.style.opacity = 0;
                setTimeout(() => {
                    messageElement.style.display = 'none';
                    currentMessageIndex++;
                    showBirthdayMessage(); // Show next message after hiding the current one
                }, 500); // Match this with transition duration
            }, 3000); // Display for 3 seconds
        } else {
            // Show the birthday text after all messages
            document.getElementById('birthdayText').style.display = 'block';
        }
    }

    // Add a click event to track clicks on the birthday text
    document.getElementById('birthdayText').addEventListener('click', () => {
        clickCounter++; // Increment the click counter

        if (clickCounter >= maxClicks) {
            // If clicked 10 times, reset the messages and click counter
            clickCounter = 0;
            currentMessageIndex = 0; // Reset message index
            document.getElementById('birthdayText').style.display = 'none'; // Hide the birthday text
            showBirthdayMessage(); // Start showing messages again
        }
    });
</script>

</body>
</html>
