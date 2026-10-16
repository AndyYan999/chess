# Afterhours Chess

**Play: https://andyyan999.github.io/chess/**

This public repository contains only the deployed website: `index.html`, this README and `.nojekyll`. The development repository and local GPT bridge are not published here. The browser-side HTML/CSS/JavaScript is public, just as it is when served by any website. No OAuth credentials or API keys are included.

## Play a friend

Open the website, choose **Online → Create room**, and send your friend the **full invitation link**. They open it on their own device. Private rooms, synchronized moves, clocks, friend chat, reconnects, draws, resignations and consensual rematches use a separate Cloudflare room service. GitHub Pages itself is static hosting; both the website and the room service must be reachable on the players' networks.

You can also choose **Two players** for same-device play. Themes, board colors, piece styles, sound, premoves and focus settings remain available.

GPT-6.1 Sol low is a separate local-only feature, not a public chatbot. This deployment cannot use the developer's personal ChatGPT account.

## Connection security

Use HTTPS. Do not bypass a browser certificate/privacy warning. A different frontend domain does not repair a device clock, untrusted certificate chain, or a network blocking the separate room service. If the webpage opens but online rooms cannot connect, record the failing hostname/error and check with the network owner.

## AI-assisted authorship

I chose the product requirements and requested the GitHub Pages address. Hermes Agent (Nous Research), using GPT-6.1 Sol, wrote the code and ran automated/browser checks. Product direction is mine; implementation and verification were AI-assisted. No competitive chess rating is claimed.

## Third-party license

The webpage embeds chess.js 1.4.0 under its BSD-2-Clause license. The complete notice is retained inside `index.html`.
