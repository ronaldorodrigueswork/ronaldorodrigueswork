```python

class RonaldoRodrigues:
    def __init__(self):
        self.name = "Ronaldo Rodrigues"
        self.role = "Python Student"
        self.tools = ["Python", "Git", "GitHub", "VS Code"]
        self.motto = "Learning something new every day! 🚀"

    def show_technologies(self):
        return f"🛠️ Technologies: {', '.join(self.tools)}"

    def social_links(self):
        return {
            "Instagram": "https://www.instagram.com/ronaldorodrz/",
            "LinkedIn": "https://www.linkedin.com/in/ronaldo-rodrigues-work",
            "Gmail": "mailto:ronaldorodrigueswork@gmail.com",
            "Discord": "https://discord.com/users/rodrizues"
        }

ronaldo = RonaldoRodrigues()

print(ronaldo.show_technologies())

for platform, link in ronaldo.social_links().items():
    print(f"{platform}: {link}")

