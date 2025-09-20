import random

def generate_score():
    # Home team အတွက် ဂိုး 0-5 အတွင်း random
    home_goals = random.randint(0, 5)
    # Away team အတွက် ဂိုး 0-5 အတွင်း random
    away_goals = random.randint(0, 5)
    return home_goals, away_goals

def main():
    home, away = generate_score()
    print(f"Home Team {home} - {away} Away Team")

if __name__ == "__main__":
    main()# Foodball-lucky
