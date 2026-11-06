---
layout: essay
type: essay
title: "Final Project Idea"
# All dates must be YYYY-MM-DD format!
date: 2026-11-04
published: true
labels:
  - Software Engineering
  - Nextjs
  - Campus Community
  - ICS 314
---

## Project: UH Flowers and Plants (UH FAPS)

**Proposers:**

- Chicco Ray Marquez (chicco@hawaii.edu)
- Rocky Acasio (rocky99@hawaii.edu)
- Rodemar Cadiz (rcadiz24@hawaii.edu)

## Overview

**The Problem:** Students and visitors may walk past native Hawaiian flowers, shrubs, and trees on and around the UH Mānoa campus without knowing their names, why they matter, or where to find them again. Learning about Hawaii's indigenous plants and flowers is important to know, in order to preserve native culture. 90% of Hawaii's native flowering plants are endemic, and they exist only here. Even when someone recognizes a plant and wants to grow it at home, it can be hard to know how much sunlight and water it needs or what kind of soil it grows best in.

**The Solution:** A web application with an interactive campus map and a searchable guide to native Hawaiian plants. Users can explore gardens and plant locations on and near campus, then open a plant profile to see photos, Hawaiian and scientific names, and a short explanation of the plant’s ecological or cultural significance. Each profile includes guidance on sunlight, watering, and soil. A student who spots a flower on the way to class can use the map to see what grows nearby, compare photos, and learn how to care for the plant at home.

## Approach

The site will use Next.js, React, Bootstrap 5, Prisma with PostgreSQL, and GitHub. The directory will use Bootstrap cards and filters to make plants easy to browse on a phone while walking around campus. Prisma will store plant profiles, observation locations, and user bookmarks. Each plant can appear at multiple locations, so admins can update its care instructions in one place.

For the first version, we’ll start with a small set of plants whose campus locations we can verify. Each profile will include a photo, plant names, care guidance, and its cultural and historical significance, with links to the sources used. Visitors can browse the directory and map without logging in. Users who sign in can save plants they want to find or grow later.

## Roles

- **Visitors:** Browse the map and plant directory, search and filter plants, and read plant profiles without an account.
- **Registered Users:** Save plants to a favorites list and return to their profiles for locations and care instructions.
- **Admins:** Add and edit plant profiles, update photos and source links, and manage plant locations on the map.

## Mockup Page Ideas

- **Landing Page:** Introduces the guide and gives users two ways to start exploring, through the plant directory or the campus map.
- **Plant Directory:** Displays plant cards with photos and names. Users can search by Hawaiian or scientific name and filter by plant type, such as flowers, shrubs, or trees.
- **Campus Map:** Shows markers for plants and gardens. Selecting a marker shows what users can find there and links to the relevant profiles.
- **Plant Detail Page:** Shows photos, plant names, campus locations, ecological or cultural significance, and care instructions with source links.
- **My Saved Plants:** Lists a signed-in user’s favorite plants with links to their profiles and map locations.
- **Admin Dashboard:** Lets admins add or edit plant profiles and manage where they appear on the map.

## Use Case Ideas

- A student sees a flower near a building on the way to class, opens the campus map, and compares photos of plants listed nearby.
- A visitor searches for a plant by its Hawaiian name and opens its profile to see where it grows on campus.
- A user looking for a plant to grow at home compares the sunlight, watering, and soil needs of two plants, then saves one to their favorites.
- An admin verifies that a plant is growing in a second campus garden and adds that location to its existing profile.
- An admin updates a plant’s care instructions and adds a source link so users can read more.

## Beyond the Basics

- **QR codes** that open a plant’s profile from a sign.
- **Community submissions** that let signed-in users suggest new sightings or location corrections for admins to review.
- **Care reminders** that let users set their own watering reminders for plants they’re growing.
- **Plant care Q&A** that answers questions using the guide’s reviewed profiles and links users to the entries it used.
- **Stories and Legends** of the plants and flowers and their role in the culture of indigenous Hawai'i.
