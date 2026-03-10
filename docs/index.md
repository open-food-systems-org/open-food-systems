
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Food Systems</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #1a1a1a;
            background-color: #faf9f7;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: center;
            padding: 4rem 1rem 2rem;
            background-color: #ffffff;
            border-bottom: 1px solid #e5e5e5;
        }
        
        h1 {
            font-size: 3rem;
            font-weight: 400;
            letter-spacing: -0.02em;
            margin-bottom: 1rem;
            color: #1a3b2f;
        }
        
        .subhead {
            font-size: 1.5rem;
            font-weight: 300;
            max-width: 800px;
            margin: 0 auto;
            color: #4a4a4a;
        }
        
        .intro {
            max-width: 800px;
            margin: 3rem auto;
            font-size: 1.25rem;
            text-align: center;
            color: #2d2d2d;
        }
        
        .pillars {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 4rem 0;
        }
        
        .pillar {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            border: 1px solid #eaeaea;
        }
        
        .pillar h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #1a3b2f;
            font-weight: 500;
        }
        
        .pillar p {
            color: #4a4a4a;
            margin-bottom: 1.5rem;
        }
        
        .pillar-link {
            color: #1a3b2f;
            text-decoration: none;
            font-weight: 500;
            border-bottom: 1px solid transparent;
            transition: border-color 0.2s;
        }
        
        .pillar-link:hover {
            border-bottom-color: #1a3b2f;
        }
        
        .core-text {
            max-width: 800px;
            margin: 4rem auto;
            padding: 2rem;
            background-color: #ffffff;
            border-radius: 12px;
            border: 1px solid #eaeaea;
        }
        
        .core-text h2 {
            font-size: 2rem;
            font-weight: 400;
            margin-bottom: 1.5rem;
            color: #1a3b2f;
        }
        
        .core-text p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
            color: #2d2d2d;
        }
        
        .values {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin: 4rem 0;
            text-align: center;
        }
        
        .value-item {
            padding: 1.5rem;
        }
        
        .value-item h4 {
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
            color: #1a3b2f;
            font-weight: 500;
        }
        
        .value-item p {
            color: #666;
            font-size: 0.95rem;
        }
        
        .sections {
            margin: 4rem 0;
        }
        
        .section-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }
        
        .section-link {
            display: block;
            padding: 1rem;
            background: white;
            border: 1px solid #eaeaea;
            border-radius: 8px;
            text-decoration: none;
            color: #1a3b2f;
            transition: all 0.2s;
        }
        
        .section-link:hover {
            background: #f0f5f2;
            border-color: #1a3b2f;
            transform: translateY(-2px);
        }
        
        .section-link small {
            display: block;
            color: #666;
            font-size: 0.85rem;
            margin-top: 0.25rem;
        }
        
        footer {
            text-align: center;
            padding: 3rem 0;
            margin-top: 3rem;
            border-top: 1px solid #e5e5e5;
            color: #666;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2.25rem;
            }
            
            .subhead {
                font-size: 1.25rem;
            }
            
            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Open Food Systems</h1>
        <div class="subhead">A humane, gradual, and inclusive evolution of how humanity produces, shares, and experiences food.</div>
    </header>
    
    <div class="container">
        <div class="intro">
            <p>Open Food Systems is a global movement rooted in dignity, care, and shared humanity. It exists to create a world where everyone has access to nourishing food, meaningful connection, and the experience of being seen and valued.</p>
        </div>
        
        <div class="pillars">
            <div class="pillar">
                <h3>Movement Overview</h3>
                <p>The philosophy and vision that guides everything—dignity, gradualism, inclusion, and respect for tradition.</p>
                <a href="docs/movement-overview" class="pillar-link">Read the overview →</a>
            </div>
            
            <div class="pillar">
                <h3>Future Food Technologies</h3>
                <p>The technological ecosystem that may support the next evolution: printers, cartridges, cultivated protein, fermentation, and more.</p>
                <a href="docs/future-food-technologies" class="pillar-link">Explore technologies →</a>
            </div>
            
            <div class="pillar">
                <h3>Adaptation Pathways</h3>
                <p>How existing industries evolve gently—farms, supermarkets, restaurants, manufacturing, and every sector of the food economy.</p>
                <a href="docs/adaptation-pathways" class="pillar-link">See the pathways →</a>
            </div>
        </div>
        
        <div class="core-text">
            <h2>What This Movement Is</h2>
            <p>Open Food Systems is a human-centered movement, a constellation of local actions, a culture of dignity and care, and a network of Community Circles. It is guided by shared practices and principles, and it lives as a living ecosystem shaped by the people within it.</p>
            
            <p>It is not an organization, a charity, or a program. There are no leaders, no ranks, no membership. The movement grows through relationships, not structures.</p>
            
            <p>The movement exists to restore dignity where it has been diminished, to address hunger through human connection, to strengthen communities through shared meals, to create spaces of belonging, to cultivate solidarity rather than charity, and to reimagine food systems through care and presence.</p>
            
            <p>Its purpose is both simple and profound: to make dignity a lived experience.</p>
        </div>
        
        <h2 style="font-size: 2rem; font-weight: 400; margin: 3rem 0 1rem; color: #1a3b2f; text-align: center;">Guiding Principles</h2>
        
        <div class="values">
            <div class="value-item">
                <h4>Dignity</h4>
                <p>Every person is worthy of respect and care.</p>
            </div>
            <div class="value-item">
                <h4>Care</h4>
                <p>Small, human acts shape the world.</p>
            </div>
            <div class="value-item">
                <h4>Humanity</h4>
                <p>Connection is essential to wellbeing.</p>
            </div>
            <div class="value-item">
                <h4>Openness</h4>
                <p>The movement belongs to everyone.</p>
            </div>
            <div class="value-item">
                <h4>Humility</h4>
                <p>The work is done without ego or hierarchy.</p>
            </div>
        </div>
        
        <div class="core-text" style="background-color: #f0f5f2;">
            <h2>Traditional Food Remains Central</h2>
            <p>The movement does <strong>not</strong> eliminate farms, vegetables, grains, legumes, fruits, herbs, spices, home cooking, cultural dishes, or family recipes. People will still cook the way they always have. Future food simply adds new options.</p>
            
            <p style="margin-top: 1.5rem;"><a href="docs/movement-overview" style="color: #1a3b2f;">Read the full Movement Overview →</a></p>
        </div>
        
        <div class="sections">
            <h2 style="font-size: 1.75rem; font-weight: 400; margin-bottom: 1rem; color: #1a3b2f;">Explore All Pages</h2>
            
            <div class="section-grid">
                <a href="docs/movement-overview" class="section-link">
                    Movement Overview
                    <small></small>
                </a>
                <a href="docs/future-food-technologies" class="section-link">
                    Future Food Technologies
                    <small></small>
                </a>
                <a href="docs/adaptation-pathways" class="section-link">
                    Adaptation Pathways
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Dedication
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Roadmap
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Mission
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Vision
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Principles
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Community
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    How It Works
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Get Involved
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Resources
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    About Us
                    <small></small>
                </a>
                <a href="docs/faq" class="section-link">
                    FAQ
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Contact
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Founders' Note
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Glossary
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Values
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Roadmap for Humanity
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Open Letter to Humanity
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Global Goals
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Foundations of the Movement
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Living Documents
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Why This Matters
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    The Movement in One Page
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    How to Contribute
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Community Principles
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Acts of Care
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Community Circles
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Global Map of Circles
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Stories of Care
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Practices
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Symbols
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Language
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Pathways of Participation
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Evolution
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Framework
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Ethos
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Invitations
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Journey
                    <small></small>
                </a>
                <a href="#" class="section-link">
                    Movement Constellation
                    <small></small>
                </a>
            </div>
        </div>
        
        <div style="text-align: center; margin: 4rem 0; padding: 2rem; background-color: #ffffff; border-radius: 12px; border: 1px solid #eaeaea;">
            <h2 style="font-size: 2rem; font-weight: 400; margin-bottom: 1rem; color: #1a3b2f;">The Movement Is an Invitation</h2>
            <p style="max-width: 600px; margin: 0 auto 2rem; font-size: 1.1rem; color: #4a4a4a;">To care, to connect, to belong, and to help build a world rooted in dignity.</p>
            
            <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1rem;">
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">share a meal</span>
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">offer a small act of care</span>
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">join a Community Circle</span>
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">read a story</span>
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">learn about food systems</span>
                <span style="background: #eaeaea; padding: 0.5rem 1rem; border-radius: 30px; font-size: 0.9rem;">create something for the movement</span>
            </div>
            
            <p style="margin-top: 2rem; color: #666;">There is no threshold. No onboarding. No permission needed.</p>
            <p style="font-style: italic; color: #1a3b2f;">The movement begins with a single human moment.</p>
        </div>
        
        <div style="text-align: center; padding: 2rem;">
            <p style="color: #666; max-width: 600px; margin: 0 auto;">Open Food Systems is not fixed. It evolves through the people who carry it, the communities that shape it, and the stories that sustain it.</p>
        </div>
    </div>
    
    <footer>
        <p>Open Food Systems — a living movement rooted in dignity and care.</p>
        <p style="margin-top: 1rem; font-size: 0.875rem;">The movement belongs to everyone. No leaders, no membership, no permission needed.</p>
    </footer>
</body>
</html>

## Status
This site is in its early stages. More pages will be added soon.

[Learn about the movement →](movement.html)
[Dedication →](dedication.html)
[Roadmap →](roadmap.html)
[Mission →](mission.html)
[Vision →](vision.html)
[Principles →](principles.html)
[Community →](community.html)
[How It Works →](how-it-works.html)
[Get Involved →](get-involved.html)
[Resources →](resources.html)
[About Us →](about-us.html)
[FAQ →](faq.html)
[Contact →](contact.html)
[Founders’ Note →](founders-note.html)
[Glossary →](glossary.html)
[Values →](values.html)
[Roadmap for Humanity →](roadmap-for-humanity.html)
[Open Letter to Humanity →](open-letter-to-humanity.html)
[Global Goals →](global-goals.html)
[Foundations of the Movement →](foundations-of-the-movement.html)
[Living Documents →](living-documents.html)
[Why This Matters →](why-this-matters.html)
[The Movement in One Page →](the-movement-in-one-page.html)
[How to Contribute →](how-to-contribute.html)
[Community Principles →](community-principles.html)
[Acts of Care →](acts-of-care.html)
[Community Circles →](community-circles.html)
[Global Map of Circles →](global-map-of-circles.html)
[Stories of Care →](stories-of-care.html)
[Movement Practices →](movement-practices.html)
[Movement Symbols →](movement-symbols.html)
[Movement Language →](movement-language.html)
[Pathways of Participation →](pathways-of-participation.html)
[Movement Evolution →](movement-evolution.html)
[Movement Framework →](movement-framework.html)
[Movement Ethos →](movement-ethos.html)
[Movement Invitations →](movement-invitations.html)
[Movement Journey →](movement-journey.html)
[Movement Constellation →](movement-constellation.html)
[Movement Overview →](movement-overview.html)
[Explore Future Food Technologies →](future-food-technologies.md)
[Adaptation Pathways →](adaptation-pathways.md)
