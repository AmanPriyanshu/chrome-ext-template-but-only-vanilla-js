# Buat Ekstensi Chrome (.crx)

![Pratinjau crx](/docs/img/crx-preview.png)
[![Status OSCS](https://www.oscs1024.com/platform/badge/guocaoyi/create-chrome-ext.svg?size=small)](https://www.oscs1024.com/project/guocaoyi/create-chrome-ext?ref=badge_small)
[![npm](https://img.shields.io/npm/v/create-chrome-ext?logo=npm)](https://www.npmjs.com/package/create-chrome-ext)
[![Unduh npm](https://img.shields.io/npm/dw/create-chrome-ext)](https://www.npmjs.com/package/create-chrome-ext)
![Jumlah Bahasa GitHub](https://img.shields.io/github/languages/count/guocaoyi/create-chrome-ext)
[![Penerbitan npm](https://github.com/guocaoyi/create-chrome-ext/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/guocaoyi/create-chrome-ext/actions/workflows/npm-publish.yml)

> Membentuk ekstensi Chrome Anda, dengan dukungan berbagai boilerplate!

- 🚀 HMR Cepat (menggunakan [Vite4](https://vitejs.dev))
- 🥡 Siap Pakai
- 🌈 Mendukung Berbagai Framework Frontend ([React](https://reactjs.org) · [Vue](https://vuejs.org) · [Svelte](https://svelte.dev) · [Preact](https://preactjs.com) · [Solid](https://www.solidjs.com) · [Alpine](https://alpinejs.dev) · [Lit](https://lit.dev) · [Inferno](https://www.infernojs.org) · [Stencil](https://stenciljs.com) · [Vanilla](http://vanilla-js.com))
- 🥢 Mendukung Berbagai Bahasa ([JavaScript](https://www.javascript.com/) · [TypeScript](https://www.typescriptlang.org/))
- 🧶 Pembangunan Teroptimasi (Latar Belakang · Konten · Popup · Opsi · Panel Sisi · Panel Devtools)

[English](../README.md) · [简体中文](./README.zh-CN.md) · [French](./README.fr-FR.md) · [한국어](./README.ko-KR.md) · [Indonesian](./README.id-ID.md) · [Русский](./README.ru-RU.md) · [Deutsch](./README.de-DE.md) · [日本語](./README.ja-JP.md) (Translated by ChatGPT)

## Instalasi

> Node >= 14.18.0

```bash
# Gunakan perintah npm-create, atau gunakan pnpm atau yarn
λ npm create chrome-ext

# atau gunakan perintah npx
λ npx create-chrome-ext

# atau gunakan perintah npm-init
λ npm init chrome-ext
```

## Penggunaan

Anda juga dapat langsung menentukan nama proyek dan templat yang ingin Anda gunakan melalui opsi baris perintah tambahan. Misalnya, untuk membentuk proyek Vite + Svelte, jalankan:

```bash
# npm 6.x
λ npm create chrome-ext@latest my-crx-app --template svelte-js

# atau npm 7+, perlu tambahan tanda dua lini:
λ npm create chrome-ext@latest my-crx-app -- --template react-ts

# atau gunakan yarn
λ yarn create chrome-ext my-crx-app --template vue-ts

# atau pnpm
λ pnpm create chrome-ext my-crx-app --template vanilla-ts
```

Anda juga dapat membuat proyek dengan perintah baris `crx`, jalankan:

```bash
λ npm install create-chrome-ext --global

# dan kemudian
λ crx my-crx-app
# atau
λ crx my-crx-app --template preact-js
# atau gunakan create-chrome-exe (lingkungan global)
λ create-chrome-ext my-crx-app
```

## Pratinjau

![crx-berjalan](/docs/img/crx-run.png)
![crx-pasang](/docs/img/crx-install.png)
![crx-bangun](/docs/img/crx-build.png)
