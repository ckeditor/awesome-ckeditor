# Awesome CKEditor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Star CKEditor](https://img.shields.io/github/stars/ckeditor/ckeditor5?style=social)](https://github.com/ckeditor/ckeditor5)
[![Subscribe on YouTube](https://img.shields.io/badge/Subscribe-YouTube-red?logo=youtube)](https://www.youtube.com/c/CKEditor)
[![LinkedIn](https://raw.githubusercontent.com/terrytangyuan/terrytangyuan/f6cd62c/imgs/linkedin.svg)](https://www.linkedin.com/company/ckeditor)

> A curated list of awesome projects and resources related to [CKEditor 5](https://ckeditor.com), an open source rich text editing component.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/ckeditor_logo_white.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/ckeditor_logo.png">
  <img alt="CKEditor logo" src="./assets/ckeditor_logo.png" align="right" width="30%" height="30%">
</picture>

CKEditor is a modern JavaScript rich-text editor with MVC architecture, custom data model, and virtual DOM, written from scratch in TypeScript with support for modern bundlers. It provides every type of WYSIWYG editing solution imaginable with extensive collaboration support. From editors similar to Google Docs and Medium to Slack or Twitter-like applications, all is possible within a single editing component.

## Contents <!-- omit from toc -->

- [Integrations](#integrations)
- [Plugins](#plugins)
- [Developer tools](#developer-tools)
- [Showcases](#showcases)
- [Guides](#guides)
- [Licensing](#licensing)

---

## Integrations

- [React](https://github.com/ckeditor/ckeditor5-react) - Official CKEditor rich text editor component for React.
- [Angular](https://github.com/ckeditor/ckeditor5-angular) - Official CKEditor rich text editor component for Angular.
- [Vue.js](https://github.com/ckeditor/ckeditor5-vue) - Official CKEditor rich text editor component for Vue.js.
- [Drupal](https://ckeditor.com/drupal) - Official CKEditor integration for the Drupal content management system.
  - [CKEditor Free plugin pack module](https://www.drupal.org/project/ckeditor5_plugin_pack) - Official set of free plugins adding emoji, find-and-replace, fonts, and more to Drupal.
  - [CKEditor Premium features module](https://www.drupal.org/project/ckeditor5_premium_features) - Integration of official Premium plugins into Drupal.
- [TYPO3](https://docs.typo3.org/c/typo3/cms-rte-ckeditor/main/en-us/Introduction/Index.html#what-does-it-do) - Official rich text editor integration for the TYPO3 CMS backend and frontend.
  - [TYPO3 CKEditor Pack](https://extensions.typo3.org/extension/rte_ckeditor_pack) - Extension providing a modern CKEditor build with accessibility tools and AI assistance.
- [Strapi](https://market.strapi.io/plugins/@ckeditor-strapi-plugin-ckeditor) - Official plugin for the Strapi headless CMS.
- [Phoenix / Elixir](https://github.com/Mati365/ckeditor5-phoenix) - CKEditor integration for Phoenix and LiveView applications.
- [Livewire / PHP](https://github.com/Mati365/ckeditor5-livewire) - Lightweight CKEditor integration for Laravel Livewire components.
- [Symfony / PHP](https://github.com/Mati365/ckeditor5-symfony) - CKEditor integration for Symfony applications.
- [Ruby on Rails](https://github.com/Mati365/ckeditor5-rails) - Ruby gem for integrating CKEditor into Rails applications via web components.
- [Redaxo CMS](https://github.com/FriendsOfREDAXO/cke5) - CKEditor integration with customizable profiles and media management for Redaxo.
- [Django CMS](https://github.com/django-cms/djangocms-text-ckeditor5) - CKEditor rich text editor frontend for the djangocms-text package.
- [Django](https://github.com/hvlads/django-ckeditor-5) - CKEditor form field and widget for Django applications.
- [Cosmos CMS](https://github.com/MoonriseSoftwareCalifornia/CosmosCMS) - Open source .NET content management system built for Microsoft Azure.
- [Laravel Nova](https://github.com/mostafaznv/nova-ckeditor) - CKEditor field with enhanced media management for Laravel Nova.
- [Vaadin Flow Java](https://github.com/wontlost-ltd/vaadin-litelement-ckeditor) - CKEditor integration for Vaadin Flow Java web applications.

## Plugins

- [Mermaid](https://github.com/ckeditor/ckeditor5-mermaid) - Plugin for embedding and displaying Mermaid diagrams.
- [CKEditor footnotes](https://www.npmjs.com/package/ckeditor5-footnotes) - Plugin for adding footnote references and content to documents.
- [Math equations](https://github.com/isaul32/ckeditor5-math) - TeX-based plugin for inserting mathematical equations via MathJax or KaTeX.
- [AI agent](https://github.com/dxpr/ckeditor5-ai-agent) - Plugin for integrating AI-assisted text generation using various models.
- [Line height](https://github.com/rickx81/ckeditor5-line-height) - Plugin for adjusting text line spacing in the editor.
- [Video uploader](https://github.com/alikhosravidev/ckeditor5-video-uploader) - Plugin for uploading and embedding videos directly in the editor.

## Developer tools

- [CKEditor Builder](https://ckeditor.com/ckeditor-5/builder/) - Online tool to configure and generate custom CKEditor builds.
- [CKEditor Package Generator](https://ckeditor.com/docs/ckeditor5/latest/framework/develpment-tools/package-generator/using-package-generator.html) - CLI tool for scaffolding CKEditor plugin packages.
- [CKEditor Inspector](https://ckeditor.com/docs/ckeditor5/latest/framework/develpment-tools/inspector.html) - Browser DevTools extension for debugging CKEditor internals.

## Showcases

- [CKEditor Official demos](https://github.com/ckeditor/ckeditor5-demos) - Official demos sources.
- [CKEditor Collaboration Features Decomposed](https://github.com/ckeditor/devrel-collaboration-features-decomposed) - Demo showing iterative implementation of comments, track changes, and real-time editing.
- [CKEditor Collaboration Samples](https://github.com/ckeditor/ckeditor5-collaboration-samples) - A collection of various configurations of the collaborations features in various frameworks.
- [CKEditor AI](https://github.com/ckeditor/devrel-ckeditor-ai-showcase-react) - React app demonstrating AI feature configuration and customization.
- [Advanced CKEditor features](https://github.com/ckeditor/devrel-mlh-workshops-aug-2025) - Workshop project demonstrating custom plugins and template functionality.
- [CKEditor Official Tutorials](https://github.com/ckeditor/ckeditor5-tutorials-examples) - Official tutorials sources.
- [Plotly.js](https://github.com/Simply007/ckeditor5-plotly-widget-showcase) - Chart library demo persisting data in the editor content and rendering charts as a CKEditor widgets.

## Guides

- [Vanilla JS](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/quick-start.html) - Quick start guide for plain JavaScript projects.
- [Next.js](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/next-js.html) - Guide for Next.js.
- [Nuxt](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/nuxt.html) - Guide for Nuxt applications using the official Vue.js component.
- [Svelte](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/svelte.html) - Guide for Svelte applications.
- [Laravel](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/laravel.html) - Guide for Laravel (PHP)) applications.
- [.NET](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/dotnet.html) - Guide for ASP.NET Core.
- [Salesforce](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/salesforce.html) - Guide for Salesforce integration via Visualforce page.
- [Spring Boot](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/spring-boot.html) - Guide for Java Spring Boot applications.
- [Electron](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/electron.html) - Guide for Electron applications.
- [jQuery](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/jquery.html) - Guide for jQuery-based web applications.

## Licensing

Released under the [CC0 1.0 Universal](LICENSE) license.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
