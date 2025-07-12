# nam nguyen vN file daaaaaa
Initial commit: Thêm README.md
import random
import time

def get_fake_weather():
    cities = ['Hanoi', 'Ho Chi Minh City', 'Da Nang', 'Hue', 'Can Tho']
    weather_conditions = ['Sunny', 'Cloudy', 'Rainy', 'Stormy', 'Foggy']
    return [{
        'city': city,
        'temperature': round(random.uniform(22.0, 35.0), 1),
        'condition': random.choice(weather_conditions)
    } for city in cities]

def display_weather(data):
    print("📡 Weather Forecast")
    print("=" * 25)
    for item in data:
        pr
