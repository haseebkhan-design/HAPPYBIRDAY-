<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Andleeb!</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow-x: hidden;
            padding: 20px;
            color: #333;
        }

        .birthday-card {
            max-width: 800px;
            width: 100%;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 25px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
            overflow: hidden;
            position: relative;
            padding: 30px;
            animation: cardAppear 1s ease-out;
        }

        @keyframes cardAppear {
            0% { opacity: 0; transform: translateY(50px) scale(0.9); }
            100% { opacity: 1; transform: translateY(0) scale(1); }
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
            position: relative;
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.8rem;
            color: #ff6b6b;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 10px;
            animation: titleGlow 3s infinite alternate;
        }

        @keyframes titleGlow {
            0% { text-shadow: 0 0 10px rgba(255, 107, 107, 0.5); }
            100% { text-shadow: 0 0 20px rgba(255, 107, 107, 0.8), 0 0 30px rgba(255, 107, 107, 0.6); }
        }

        .birthday-person {
            font-size: 2.2rem;
            color: #2575fc;
            font-weight: 600;
            letter-spacing: 1px;
            margin: 10px 0;
        }

        .date {
            font-size: 1.2rem;
            color: #6a11cb;
            background: rgba(106, 17, 203, 0.1);
            display: inline-block;
            padding: 8px 20px;
            border-radius: 50px;
            margin-top: 5px;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 30px;
        }

        .message-box {
            flex: 1;
            min-width: 300px;
            background: linear-gradient(to right bottom, rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.7));
            border-radius: 20px;
            padding: 25px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
        }

        .message-box h2 {
            color: #6a11cb;
            margin-bottom: 15px;
            font-size: 1.8rem;
            border-bottom: 2px dashed #6a11cb;
            padding-bottom: 8px;
        }

        .message {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #444;
        }

        .highlight {
            color: #ff6b6b;
            font-weight: 600;
        }

        .wishes {
            flex: 1;
            min-width: 300px;
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .wish-box {
            background: white;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .wish-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .wish-box i {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #6a11cb;
        }

        .wish-box h3 {
            color: #2575fc;
            margin-bottom: 8px;
        }

        .cake-container {
            text-align: center;
            margin: 30px 0;
            position: relative;
        }

        .cake {
            position: relative;
            display: inline-block;
            font-size: 4rem;
            animation: cakeFloat 4s infinite ease-in-out;
        }

        @keyframes cakeFloat {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .candle {
            position: absolute;
            top: -50px;
            left: 50%;
            transform: translateX(-50%);
            width: 10px;
            height: 40px;
            background: linear-gradient(to top, #ff6b6b, #ffd166);
            border-radius: 5px;
        }

        .flame {
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            width: 15px;
            height: 25px;
            background: #ffd166;
            border-radius: 50% 50% 20% 20%;
            animation: flameFlicker 0.5s infinite alternate;
            box-shadow: 0 0 20px #ff9e00;
        }

        @keyframes flameFlicker {
            0% { transform: translateX(-50%) scale(1); }
            100% { transform: translateX(-50%) scale(1.1); }
        }

        .interactive-section {
            text-align: center;
            margin-top: 30px;
        }

        .btn {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            border: none;
            padding: 15px 35px;
            font-size: 1.2rem;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(37, 117, 252, 0.4);
            font-weight: 600;
            letter-spacing: 1px;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(37, 117, 252, 0.6);
        }

        .btn:active {
            transform: translateY(1px);
        }

        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background-color: #f0f;
            opacity: 0;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px dashed #ccc;
            color: #666;
            font-size: 0.9rem;
        }

        .creator {
            color: #6a11cb;
            font-weight: 600;
        }

        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .heart {
            position: absolute;
            color: rgba(255, 107, 107, 0.7);
            font-size: 20px;
            opacity: 0;
            animation: floatUp 5s linear infinite;
        }

        @keyframes floatUp {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.8rem;
            }
            
            .birthday-person {
                font-size: 1.8rem;
            }
            
            .content {
                flex-direction: column;
            }
            
            .cake {
                font-size: 3rem;
            }
        }
    </style>
</head>
<body>
    <div class="birthday-card" id="birthdayCard">
        <div class="hearts" id="heartsContainer"></div>
        
        <div class="header">
            <h1>Happy Birthday!</h1>
            <div class="birthday-person">Andleeb</div>
            <div class="date">15th of this month</div>
        </div>
        
        <div class="content">
            <div class="message-box">
                <h2>Special Message</h2>
                <p class="message">
                    Dear <span class="highlight">Andleeb</span>, on your special day, I wish you endless joy, laughter, and all the happiness in the world. May this year bring you closer to your dreams and fill your life with beautiful moments. 
                    <br><br>
                    You're an amazing friend, and I'm grateful for your presence in my life. May your birthday be as wonderful as you are!
                </p>
            </div>
            
            <div class="wishes">
                <div class="wish-box">
                    <i class="fas fa-gift"></i>
                    <h3>Amazing Gifts</h3>
                    <p>May you receive all the gifts you've been dreaming of!</p>
                </div>
                
                <div class="wish-box">
                    <i class="fas fa-crown"></i>
                    <h3>Joy & Happiness</h3>
                    <p>May your day be filled with joy and unforgettable moments!</p>
                </div>
                
                <div class="wish-box">
                    <i class="fas fa-heart"></i>
                    <h3>Love & Laughter</h3>
                    <p>May love and laughter surround you today and always!</p>
                </div>
            </div>
        </div>
        
        <div class="cake-container">
            <div class="cake">
                <div class="candle">
                    <div class="flame" id="flame"></div>
                </div>
                🎂
            </div>
        </div>
        
        <div class="interactive-section">
            <button class="btn" id="celebrateBtn">
                <i class="fas fa-birthday-cake"></i> Click to Celebrate!
            </button>
        </div>
        
        <div class="footer">
            <p>Made with <i class="fas fa-heart" style="color: #ff6b6b;"></i> by <span class="creator">Muhammad Haseeb</span></p>
            <p>For my dear friend Andleeb on her special day!</p>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const birthdayCard = document.getElementById('birthdayCard');
            const celebrateBtn = document.getElementById('celebrateBtn');
            const flame = document.getElementById('flame');
            const heartsContainer = document.getElementById('heartsContainer');
            
            // Create floating hearts
            function createHearts() {
                const heartEmojis = ['❤️', '💖', '💝', '🎉', '🎁', '✨', '🥳'];
                
                for (let i = 0; i < 25; i++) {
                    const heart = document.createElement('div');
                    heart.className = 'heart';
                    heart.innerHTML = heartEmojis[Math.floor(Math.random() * heartEmojis.length)];
                    heart.style.left = `${Math.random() * 100}%`;
                    heart.style.animationDelay = `${Math.random() * 5}s`;
                    heart.style.fontSize = `${Math.random() * 20 + 15}px`;
                    heartsContainer.appendChild(heart);
                }
            }
            
            // Create confetti effect
            function createConfetti() {
                const colors = ['#ff6b6b', '#4ecdc4', '#ffd166', '#06d6a0', '#118ab2', '#ef476f'];
                
                for (let i = 0; i < 150; i++) {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
                    confetti.style.left = `${Math.random() * 100}%`;
                    confetti.style.top = `${Math.random() * 100}%`;
                    confetti.style.transform = `rotate(${Math.random() * 360}deg)`;
                    confetti.style.width = `${Math.random() * 10 + 5}px`;
                    confetti.style.height = `${Math.random() * 10 + 5}px`;
                    birthdayCard.appendChild(confetti);
                    
                    // Animate confetti
                    const animation = confetti.animate([
                        { opacity: 1, transform: `translate(0, 0) rotate(0deg)` },
                        { opacity: 1, transform: `translate(${Math.random() * 200 - 100}px, ${Math.random() * 200 + 100}px) rotate(${Math.random() * 360}deg)` }
                    ], {
                        duration: Math.random() * 1000 + 1000,
                        easing: 'cubic-bezier(0.215, 0.610, 0.355, 1)'
                    });
                    
                    // Remove confetti after animation
                    animation.onfinish = () => {
                        confetti.remove();
                    };
                }
            }
            
            // Make flame flicker more on hover
            flame.addEventListener('mouseover', function() {
                this.style.animationDuration = '0.1s';
            });
            
            flame.addEventListener('mouseout', function() {
                this.style.animationDuration = '0.5s';
            });
            
            // Celebrate button functionality
            celebrateBtn.addEventListener('click', function() {
                // Disable button temporarily
                this.disabled = true;
                this.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Celebrating!';
                
                // Create confetti
                createConfetti();
                
                // Play birthday sound (using a simple beep sound)
                playBirthdaySound();
                
                // Add cake animation
                const cake = document.querySelector('.cake');
                cake.style.animation = 'cakeFloat 0.5s ease-in-out 5';
                
                // Change background color temporarily
                document.body.style.background = 'linear-gradient(135deg, #ff6b6b 0%, #ffd166 100%)';
                
                // Show celebration message
                const messageBox = document.querySelector('.message-box');
                const originalMessage = messageBox.innerHTML;
                messageBox.innerHTML = `
                    <h2>🎉 Celebration Time! 🎉</h2>
                    <p class="message" style="text-align: center; font-size: 1.3rem;">
                        <strong>Andleeb, let's party!</strong><br><br>
                        Wishing you the happiest birthday filled with joy, laughter, and wonderful memories! 
                        May all your dreams come true this year! 🥳🎂🎁
                    </p>
                `;
                
                // Revert after 5 seconds
                setTimeout(() => {
                    document.body.style.background = 'linear-gradient(135deg, #6a11cb 0%, #2575fc 100%)';
                    cake.style.animation = 'cakeFloat 4s infinite ease-in-out';
                    messageBox.innerHTML = originalMessage;
                    celebrateBtn.disabled = false;
                    celebrateBtn.innerHTML = '<i class="fas fa-birthday-cake"></i> Click to Celebrate Again!';
                }, 5000);
            });
            
            // Simple birthday sound using Web Audio API
            function playBirthdaySound() {
                try {
                    const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                    const playNote = (frequency, duration, time) => {
                        const oscillator = audioContext.createOscillator();
                        const gainNode = audioContext.createGain();
                        
                        oscillator.connect(gainNode);
                        gainNode.connect(audioContext.destination);
                        
                        oscillator.frequency.value = frequency;
                        oscillator.type = 'sine';
                        
                        gainNode.gain.setValueAtTime(0, time);
                        gainNode.gain.linearRampToValueAtTime(0.5, time + 0.01);
                        gainNode.gain.exponentialRampToValueAtTime(0.001, time + duration);
                        
                        oscillator.start(time);
                        oscillator.stop(time + duration);
                    };
                    
                    // Play "Happy Birthday" tune
                    const notes = [392, 392, 440, 392, 523, 494];
                    const durations = [0.3, 0.3, 0.5, 0.5, 0.5, 0.8];
                    
                    let time = audioContext.currentTime + 0.1;
                    
                    for (let i = 0; i < notes.length; i++) {
                        playNote(notes[i], durations[i], time);
                        time += durations[i];
                    }
                } catch (e) {
                    console.log("Audio not supported in this browser");
                }
            }
            
            // Initialize hearts
            createHearts();
            
            // Add some random glitter effects
            setInterval(() => {
                const glitters = ['✨', '🌟', '💫'];
                const glitter = document.createElement('div');
                glitter.innerHTML = glitters[Math.floor(Math.random() * glitters.length)];
                glitter.style.position = 'absolute';
                glitter.style.left = `${Math.random() * 100}%`;
                glitter.style.top = `${Math.random() * 100}%`;
                glitter.style.fontSize = `${Math.random() * 20 + 10}px`;
                glitter.style.opacity = '0.7';
                glitter.style.zIndex = '1';
                glitter.style.pointerEvents = 'none';
                birthdayCard.appendChild(glitter);
                
                // Animate glitter
                glitter.animate([
                    { opacity: 0, transform: 'scale(0.5)' },
                    { opacity: 0.7, transform: 'scale(1)' },
                    { opacity: 0, transform: 'scale(0.5)' }
                ], {
                    duration: 1000,
                    easing: 'ease-out'
                });
                
                // Remove after animation
                setTimeout(() => glitter.remove(), 1000);
            }, 500);
        });
    </script>
</body>
</html>
