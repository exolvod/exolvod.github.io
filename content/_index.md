---
title: "Home"
---

<!-- Hero Section -->
<section id="hero">
    <div class="container">
        <h1>{{ .Site.Data.hero.content.title }}</h1>
        <p>{{ .Site.Data.hero.content.text }}</p>
        <a href="{{ .Site.Data.hero.content.buttonPrimary.url }}" class="btn btn-primary">{{ .Site.Data.hero.content.buttonPrimary.label }}</a>
        <a href="{{ .Site.Data.hero.content.buttonSecondary.url }}" class="btn btn-secondary">{{ .Site.Data.hero.content.buttonSecondary.label }}</a>
    </div>
</section>

<!-- Portfolio Section -->
<section id="portfolio">
    <div class="container">
        <h2>{{ .Site.Data.portfolio.content[0].pretitle }}</h2>
        <h3>{{ .Site.Data.portfolio.content[0].title }}</h3>
        <p>{{ .Site.Data.portfolio.content[0].text }}</p>
        <div class="portfolio-buttons">
            <a href="{{ .Site.Data.portfolio.content[0].buttons[0].url }}" class="btn btn-primary">{{ .Site.Data.portfolio.content[0].buttons[0].label }}</a>
            <a href="{{ .Site.Data.portfolio.content[0].buttons[1].url }}" class="btn btn-secondary">{{ .Site.Data.portfolio.content[0].buttons[1].label }}</a>
        </div>
    </div>
</section>

<!-- Services Section -->
<section id="services">
    <div class="container">
        <h2>Our Services</h2>
        <div class="services-list">
            {{ range .Site.Data.services.content }}
            <div class="service">
                <h3>{{ .title }}</h3>
                <p>{{ .description }}</p>
            </div>
            {{ end }}
        </div>
    </div>
</section>

<!-- CTA Section -->
<section id="cta">
    <div class="container">
        <h2>{{ .Site.Data.cta.content.title }}</h2>
        <img src="{{ .Site.Data.cta.content.image }}" alt="CTA Image">
        <a href="{{ .Site.Data.cta.content.button.url }}" class="btn btn-primary">{{ .Site.Data.cta.content.button.label }}</a>
    </div>
</section>

