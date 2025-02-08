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

    def github_status(self):
        return {
            "stats": "![GitHub Stats](https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=radical)",
            "languages": "![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=radical)"
        }

    def social_links(self):
        return {
            "Instagram": "[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/your_instagram)",
            "LinkedIn": "[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/your_linkedin)",
            "Gmail": "[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your_email@gmail.com)",
            "Discord": "[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/your_discord_id)"
        }

# 🚀 Initialize Ronaldo's Profile
ronaldo = RonaldoRodrigues()

# 🔧 Show Technologies
print(ronaldo.show_technologies())

# 📊 GitHub Stats
print(ronaldo.github_status()["stats"])
print(ronaldo.github_status()["languages"])

# 🌎 Social Links
for platform, link in ronaldo.social_links().items():
    print(f"{platform}: {link}")

