import time
import random

def fireworks_animation():
    fireworks = ["🎆", "🎇", "💥", "✨", "🌟"]
    for _ in range(5):
        firework = " ".join(random.choices(fireworks, k=10))
        print(firework)
        time.sleep(0.3)
    time.sleep(1)

def balloon_animation():
    balloons = ["🎈", "🎈", "🎈", "🎈", "🎈"]
    for _ in range(5):
        for balloon in balloons:
            print(balloon, end=" ")
            time.sleep(0.2)
        print()
        time.sleep(0.5)
    time.sleep(1)

def confetti_animation():
    confetti = ["🎉", "🎊", "🎈", "❤️"]
    for _ in range(5):
        for _ in range(10):
            print(random.choice(confetti), end=" ")
        print()
        time.sleep(0.5)
    time.sleep(1)

def heart_animation():
    hearts = ["❤️", "💖", "💕", "💓", "💗"]
    for _ in range(5):
        heart_line = " ".join(random.choices(hearts, k=10))
        print(heart_line)
        time.sleep(0.3)
    time.sleep(1)

def cake_animation():
    print("🎂🍰🎂🍰🎂🍰🎂🍰🎂🍰")
    print("🕯️🕯️🕯️🕯️🕯️🕯️🕯️🕯️🕯️🕯️")
    print("🎉🎈🎁🎉🎈🎁🎉🎈🎁🎉🎈🎁")
    time.sleep(1)

def birthday_song():
    print("🎶🎵 Happy Birthday to you! 🎵🎶")
    time.sleep(1)
    print("🎶🎵 Happy Birthday to you! 🎵🎶")
    time.sleep(1)
    print("🎶🎵 Happy Birthday dear niggaaaaa! 🎵🎶")
    time.sleep(1)
    print("🎶🎵 Happy Birthday to you! 🎵🎶")

def display_message():
    print("\n🎉🎈🎁 Happy Birthday mi negro favorito 🎁🎈🎉")
    print("Wishing you a horri- i meant fantastic day BECAUSE IM NOT A BITCH LIKE YOU ARE.")
    print("May all you FALL OFF THE STAI- i meant all your dreams and wishes come true ")
    print("Sending lots of lov- ewwwww and best wishes your way. Enjoy your day!")

def send_birthday_wishes(Emilia):
    fireworks_animation()
    time.sleep(1)
    balloon_animation()
    time.sleep(1)
    confetti_animation()
    time.sleep(1)
    heart_animation()
    time.sleep(1)
    cake_animation()
    time.sleep(1)
    birthday_song()
    time.sleep(1)
    display_message()

# Replace 'Emilia' with the actual name
send_birthday_wishes("Emilia")
