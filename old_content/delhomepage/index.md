---
title: "Home"
type: "homepage"
---

<!-- Hero Section -->
{{ with .Site.Data.hero }}
<section id="{{ .id }}">
    <div class="container">
        <h1>{{ .content.title }}</h1>
        <p>{{ .content.text }}</p>
        <div class="buttons">
            <a href="{{ .content.buttonPrimary.url }}" class="btn btn-primary">{{ .content.buttonPrimary.label }}</a>
            <a href="{{ .content.buttonSecondary.url }}" class="btn btn-secondary">{{ .content.buttonSecondary.label }}</a>
        </div>
    </div>
</section>
{{ end }}

<!-- Portfolio Section -->
{{ with .Site.Data.portfolio }}
<section id="{{ .id }}">
    <div class="container">
        <h2>{{ .content[0].pretitle }}</h2>
        <h3>{{ .content[0].title }}</h3>
        <p>{{ .content[0].text }}</p>
        <div class="portfolio-image">
            <img src="{{ .content[0].image }}" alt="Portfolio Image">
        </div>
        <div class="buttons">
            <a href="{{ .content[0].buttons[0].url }}" class="btn btn-primary">{{ .content[0].buttons[0].label }}</a>
            <a href="{{ .content[0].buttons[1].url }}" class="btn btn-secondary">{{ .content[0].buttons[1].label }}</a>
        </div>
    </div>
</section>
{{ end }}

<!-- Call to Action Section -->
{{ with .Site.Data.cta }}
<section id="{{ .id }}">
    <div class="container text-center">
        <h2>{{ .content.title }}</h2>
        <a href="{{ .content.button.url }}" class="btn btn-primary">{{ .content.button.label }}</a>
        <div class="cta-image">
            <img src="{{ .content.image }}" alt="Call to Action Image">
        </div>
    </div>
</section>
{{ end }}

<!-- Additional Sections -->
<!-- You can add more sections here as needed -->
