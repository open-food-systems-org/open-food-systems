
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Food Systems</title>
    <style>
        :root {
            --primary-color: #1a3b2f;
            --secondary-color: #4a4a4a;
            --light-color: #faf9f7;
            --accent-color: #e8f0ed;
            --text-color: #2d2d2d;
            --border-color: #eaeaea;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.7;
            color: var(--text-color);
            background-color: var(--light-color);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        header {
            text-align: center;
            padding: 4rem 0 3rem;
            background-color: white;
            margin-bottom: 2rem;
            border-bottom: 1px solid var(--border-color);
        }

        h1 {
            font-size: 3rem;
            font-weight: 300;
            color: var(--primary-color);
            margin-bottom: 1rem;
            letter-spacing: -0.03em;
        }

        .subhead {
            font-size: 1.5rem;
            color: var(--secondary-color);
            max-width: 800px;
            margin: 0 auto;
            font-weight: 300;
        }

        .intro {
            max-width: 800px;
            margin: 3rem auto;
            text-align: center;
            font-size: 1.2rem;
            color: var(--secondary-color);
        }

        .section {
            background-color: white;
            border-radius: 12px;
            padding: 3rem;
            margin: 3rem 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            border: 1px solid var(--border-color);
        }

        .section h2 {
            font-size: 2rem;
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            font-weight: 400;
            text-align: center;
        }

        .section p {
            font-size: 1.1rem;
            margin-bottom: 1.5rem;
            color: var(--text-color);
        }

        .principles-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .principle-card {
            text-align: center;
            padding: 1.5rem;
            background-color: var(--accent-color);
            border-radius: 8px;
        }

        .principle-card h4 {
            font-size: 1.2rem;
            color: var(--primary-color);
            margin-bottom: 0.75rem;
            font-weight: 500;
        }

        .principle-card p {
            color: var(--secondary-color);
            font-size: 0.95rem;
        }

        .highlight-box {
            background-color: var(--accent-color);
            border-left: 4px solid var(--primary-color);
            padding: 2rem;
            margin: 3rem 0;
            border-radius: 8px;
        }

        .highlight-box h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        .highlight-box p {
            margin-bottom: 1rem;
            color: var(--text-color);
        }

        .invitation {
            text-align: center;
            padding: 4rem 2rem;
            background-color: white;
            border-radius: 12px;
            margin: 3rem 0;
            border: 1px solid var(--border-color);
        }

        .invitation h2 {
            font-size: 2.2rem;
            color: var(--primary-color);
            margin-bottom: 1.5rem;
            font-weight: 300;
        }

        .invitation p {
            font-size: 1.1rem;
            color: var(--secondary-color);
            max-width: 600px;
            margin: 0 auto 2rem;
        }

        .tags {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 0.75rem;
            margin: 2rem 0;
        }

        .tag {
            background-color: var(--border-color);
            color: var(--secondary-color);
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 3rem 0;
            margin-top: 3rem;
            border-top: 1px solid var(--border-color);
            color: var(--secondary-color);
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            .subhead {
                font-size: 1.2rem;
            }
            .section {
                padding: 2rem 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Open Food Systems</h1>
            <div class="subhead">
                A humane, gradual, and inclusive evolution of how humanity produces, shares, and experiences food.
            </div>
        </div>
    </header>

    <div class="container">
        <div class="intro">
            <p>
                Open Food Systems is a global movement rooted in dignity, care, and shared humanity.
                It exists to create a world where everyone has access to nourishing food, meaningful connection,
                and the experience of being seen and valued.
            </p>
        </div>

        <div class="section">
            <h2>What This Movement Is</h2>
            <p>
                Open Food Systems is a human-centered movement, a constellation of local actions, a culture of dignity and care,
                and a network of Community Circles. It is guided by shared practices and principles, and it lives as a living
                ecosystem shaped by the people within it.
            </p>
            <p>
                It is not an organization, a charity, or a program. There are no leaders, no ranks, no membership.
                The movement grows through relationships, not structures.
            </p>
            <p>
                The movement exists to restore dignity where it has been diminished, to address hunger through human
                connection, to strengthen communities through shared meals, to create spaces of belonging, to cultivate
                solidarity rather than charity, and to reimagine food systems through care and presence.
            </p>
            <p>
                Its purpose is both simple and profound: to make dignity a lived experience.
            </p>
        </div>

        <div class="section">
            <h2>Guiding Principles</h2>
            <div class="principles-grid">
                <div class="principle-card">
                    <h4>Dignity</h4>
                    <p>Every person is worthy of respect and care.</p>
                </div>
                <div class="principle-card">
                    <h4>Care</h4>
                    <p>Small, human acts shape the world.</p>
                </div>
                <div class="principle-card">
                    <h4>Humanity</h4>
                    <p>Connection is essential to wellbeing.</p>
                </div>
                <div class="principle-card">
                    <h4>Openness</h4>
                    <p>The movement belongs to everyone.</p>
                </div>
                <div class="principle-card">
                    <h4>Humility</h4>
                    <p>The work is done without ego or hierarchy.</p>
                </div>
            </div>
        </div>

        <div class="highlight-box">
            <h3>Traditional Food Remains Central</h3>
            <p>
                The movement does <strong>not</strong> eliminate farms, vegetables, grains, legumes, fruits, herbs, spices,
                home cooking, cultural dishes, or family recipes. People will still cook the way they always have.
                Future food simply adds new options.
            </p>
        </div>

        <div class="invitation">
            <h2>The Movement Is an Invitation</h2>
            <p>
                To care, to connect, to belong, and to help build a world rooted in dignity.
            </p>
            <div class="tags">
                <span class="tag">share a meal</span>
                <span class="tag">offer a small act of care</span>
                <span class="tag">join a Community Circle</span>
                <span class="tag">read a story</span>
                <span class="tag">learn about food systems</span>
                <span class="tag">create something for the movement</span>
            </div>
            <p>
                There is no threshold. No onboarding. No permission needed.
            </p>
            <p style="font-style: italic; color: var(--primary-color);">
                The movement begins with a single human moment.
            </p>
        </div>

        <div style="text-align: center; margin: 4rem 0; color: var(--secondary-color);">
            <p>
                Open Food Systems is not fixed. It evolves through the people who carry it,
                the communities that shape it, and the stories that sustain it.
            </p>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>Open Food Systems — a living movement rooted in dignity and care.</p>
            <p style="margin-top: 1rem; font-size: 0.9rem;">
                The movement belongs to everyone. No leaders, no membership, no permission needed.
            </p>
        </div>
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
[Economic Benefits →](economic-benefits.md)
