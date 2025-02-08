```python
# 🚀 Developer Profile

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
            "Instagram": "Instagram: your_instagram",
            "LinkedIn": "LinkedIn: your_linkedin",
            "Gmail": "Gmail: your_email@gmail.com",
            "Discord": "Discord: your_discord_id"
        }

# 🚀 Initialize Ronaldo's Profile
ronaldo = RonaldoRodrigues()

# 🔧 Show Technologies
print(ronaldo.show_technologies())

# 🌎 Social Links
for platform, link in ronaldo.social_links().items():
    print(f"{platform}: {link}")

