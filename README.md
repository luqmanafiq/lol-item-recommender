# lol-item-recommender

League of Legends Item Recommender
An AI-powered semantic search tool for finding the perfect League of Legends items based on natural language descriptions.

🎯 Features in Colab Version:
✅ Live Data Fetching - Gets current champions/items from Riot API
✅ Semantic Similarity - Uses cosine similarity with feature vectors
✅ Visual Analytics - Matplotlib charts for recommendation analysis
✅ Champion Comparison - Compare builds between champions
✅ Game Phase Optimization - Different recommendations per game phase

🚀 Demo
Try these example searches:

Modify the feature weights in calculate_similarity(),
Add more champion characteristics,
Include counter-pick logic,
Add team composition analysis

🛠️ Technology Stack

API: Riot Games Data Dragon API
AI/ML: Custom semantic embeddings with cosine similarity
Hosting: GitHub Pages ready

📁 Project Structure
lol-item-recommender/
├── main.py              # Main application file
├── README.md              # This file
🎮 How It Works

Data Loading: Fetches current item data from Riot's Data Dragon API
Embedding Generation: Creates feature vectors for each item based on:


Query Processing: Converts user queries into the same vector space
Similarity Matching: Uses cosine similarity to find most relevant items
Results Display: Shows items ranked by relevance with confidence scores

🚀 Getting Started
Quick Start

Clone this repository:
bashgit clone https://github.com/yourusername/lol-item-recommender.git
cd lol-item-recommender

Copy this code on your github and 'BAM' you get the item for your champion!

GitHub Pages Deployment

Fork this repository
Go to Settings → Pages
Select "Deploy from a branch" and choose main
Your app will be available at https://yourusername.github.io/lol-item-recommender

🔧 Development
Local Development
No build process required! This is a vanilla JavaScript application that runs directly in the browser.
Adding Features

More Advanced Embeddings: Implement TF-IDF or use external embedding APIs
Champion Integration: Add champion-specific item recommendations
Build Paths: Show complete item build sequences
Meta Analysis: Include current meta trends and win rates
Patch Notes: Highlight recently changed items

📊 Algorithm Details
The recommendation system uses a simple but effective approach:

Feature Extraction: Each item is analyzed for key features:

Damage potential (AD, crit, lethality)
Magic power (AP, magic pen)
Defensive stats (armor, MR, health)
Mobility (movement speed, attack speed)
Sustain (lifesteal, healing)
Utility (CDR, actives)


Vector Representation: Items and queries are converted to 6-dimensional vectors
Similarity Calculation: Cosine similarity determines relevance:
similarity = (A · B) / (||A|| × ||B||)

Ranking: Results sorted by similarity score with confidence percentages

🤝 Contributing
Contributions are welcome! Here are some ways to help:

Bug Reports: Found an issue? Open a GitHub issue
Feature Requests: Have an idea? Let's discuss it!
Code Contributions:

Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request


Development Guidelines

Keep it simple - vanilla JS preferred
Maintain the gaming aesthetic
Ensure mobile responsiveness
Add comments for complex logic
Test with various query types

📋 Roadmap

 Champion-specific recommendations
 Item build path suggestions
 Integration with champion.gg or similar APIs for meta data
 Advanced embedding models (Word2Vec, BERT)
 User preference learning
 Patch notes integration
 Multi-language support

⚖️ Legal
This project is not affiliated with Riot Games. League of Legends is a trademark of Riot Games, Inc.
Item data is provided by Riot Games through their Data Dragon API under their Legal Jibber Jabber.
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgments

Inspired by the Semantic Book Recommender tutorial
Built with Riot Games' Data Dragon API
Thanks to the League of Legends community for inspiration

📧 Contact
Have questions or suggestions? Feel free to:

Open an issue on GitHub
Reach out on social media
Join the discussion in our community


⭐ Star this repository if you found it helpful! ⭐
