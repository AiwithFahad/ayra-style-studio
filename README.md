# 👗 AYRA — AI Personal Stylist & Virtual Try-On

**Your wardrobe, styled by AI.** AYRA catalogs the clothes you already own, suggests outfit combinations from your own items, and lets you **virtually try looks on your own photo** — so you can see how an outfit suits you before you get dressed.

[![Live App](https://img.shields.io/badge/Live%20App-ayra--style--studio.lovable.app-success?style=for-the-badge)](https://ayra-style-studio.lovable.app)
[![AI](https://img.shields.io/badge/AI-Multimodal%20Generative%20AI-blueviolet?style=for-the-badge)](#-ai-technique)
[![Privacy](https://img.shields.io/badge/Wardrobe-Private%20per%20user-blue?style=for-the-badge)](#-key-features)

> 🌐 **Live web app:** https://ayra-style-studio.lovable.app

---

## ❌ The Problem

People own clothes they forget about. Items sit in the wardrobe unworn because styling them into outfits takes effort — and there's no easy way to see how a combination would actually look on *you* before wearing it.

## ✅ The Solution

A personal stylist app that:

1. **Catalogs your wardrobe** from photos
2. **Suggests outfit combinations** using AI — from *only your own items*
3. **Virtually tries them on your photo** using generative AI, so you see the result on yourself first

## ✨ Key Features

- 📸 **Smart wardrobe upload** — upload clothing photos and the AI auto-detects the item's **category** (e.g. men's/kids' shirt, jacket) and **colour**
- 🔒 **Private wardrobe per user** — secure sign-up/login; every user sees only their own items, displayed newest first, stored privately in the cloud
- ✨ **"Style Me"** — one tap and the AI suggests **3 outfits from only your items**, each with specific reasons why the combination works
- 🪞 **Virtual Try-On, three ways:**
  - **Live camera** view
  - **Photo upload**
  - **Video** — the app automatically picks the best frame
- 🛍️ **Storefront** — homepage with categories and product pages, with **Buy Now** and **"Try It On"** so shoppers can preview store items on themselves too

## 🧠 AI Technique

**Deep learning — multimodal generative AI**, in two parts:

| Stage | What happens |
|---|---|
| **Understanding** | A **vision-language model** reads each clothing photo and detects its category and colours, and generates the outfit suggestions |
| **Try-on generation** | A **generative image-editing model** produces a realistic try-on result — it keeps your **face, pose and background unchanged** and changes **only the clothing** |

## 🔌 APIs & Platform

| API / Service | Used for |
|---|---|
| **Lovable AI Gateway** | Access to the vision-language and image-editing models |
| **Browser Camera / Media API** | The live virtual try-on view |
| **Cloud storage** | Private storage of each user's wardrobe photos |

## 🔁 How It Works

1. **Sign up / log in** — your wardrobe is private to your account
2. **Upload** photos of your clothes — AI tags category + colour automatically
3. **Tap "Style Me"** — get 3 outfit ideas built only from your items, with reasons
4. **Try it on** — camera, photo or video; generative AI renders the look on you, changing only the clothes
5. **Shop the storefront** — browse categories and products, Buy Now, or Try It On first

## 🎯 Final Outcome

A complete AI-powered personal stylist app that turns your existing wardrobe into styled outfits — and lets you see yourself wearing them before getting dressed.

---

*This repository presents the AYRA project and its documentation; the app itself runs live at [ayra-style-studio.lovable.app](https://ayra-style-studio.lovable.app).*

*Built by [Fahad Ahmed Shanawar](https://github.com/AiwithFahad) — Agentic AI Architect · AI Agents · n8n · RAG · Voice AI*
