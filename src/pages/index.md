---
layout: ../layouts/Main.astro
title: Home
---

<div class="avatar-container">
  <img src="/assets/headshot.jpg" alt="Jesus Gil headshot"/>
</div>

# Jesus Gil

I'm a software developer based in Chicago. I am interested in many technologies including Next.js, Astro, and Supabase to build dynamic, and accessible applications.

<br>
<br>
<br>

## Open Source

Current projects I am currently contributing to:

<div class="list-grid">
  <a class="open-source-link" href="https://github.com/snowpackjs/astro" target="_blank" rel="noopener noreferrer">Astro</a>
  <a class="open-source-link" href="https://github.com/quick-lint/quick-lint-js" target="_blank" rel="noopener noreferrer">quick-lint-js</a>
</div>

<style>
  .avatar-container {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    overflow: hidden;
  }

  .avatar-container > img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .open-source-link {
    padding: var(--space-sm) var(--space-md);
    border: 1px solid var(--color-primary);
    border-radius: var(--radius-sm);
    text-align: center;
  }

  .open-source-link:hover {
    color: var(--color-secondary);
    background-color: var(--color-primary);
  }

  .list-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: var(--space-md);
  }

  @media (prefers-color-scheme: dark) {
    .open-source-link {
      border: 1px solid var(--color-secondary);
    }

    .open-source-link:hover {
      color: var(--color-primary);
      background-color: var(--color-secondary);
    }
  }
</style>