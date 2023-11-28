---
layout: docs
title: Typography
description: Typography
---

# Typography

* TOC
{:toc}

## Base

```scss
@font-size__xs: @3;
@font-size__sm: @3-5;
@font-size__base: @4;
@font-size__lg: @4-5;
@font-size__xl: @5;
@font-size__2xl: @6;
@font-size__3xl: @7-5;
@font-size__4xl: @9;
@font-size__5xl: @12;

@line-height__xs: @4;
@line-height__sm: @5;
@line-height__base: @6;
@line-height__lg: @7;
@line-height__xl: @7;
@line-height__2xl: @8;
@line-height__3xl: @9;
@line-height__4xl: @10;
@line-height__5xl: 1;

@font-sans:  ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
@font-serif: ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
@font-mono:  ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
```

## Text

```scss
@base__font-family: @font-sans;
@base__font-size: @font-size__base;
@base__line-height: @line-height__base;
@base__text-color: @gray-900;
@base__text-alpha: 1;
```

## Headings

```scss
@headings__font-family: false;
@headings__text-transform: false;
@headings__text-color: var(--base-color);
@headings__text-alpha: 1;

@h1__font-size: @font-size__4xl;
@h1__font-weight: bold;
@h1__line-height: @line-height__4xl;
@h1__text-transform: false;
@h1__letter-spacing: false;
@h1__margin-top: @8;
@h1__margin-bottom: @4;

@h2__font-size: @font-size__3xl;
@h2__font-weight: 600;
@h2__line-height: @line-height__3xl;
@h2__text-transform: false;
@h2__letter-spacing: false;
@h2__margin-top: @8;
@h2__margin-bottom: @4;

@h3__font-size: @font-size__2xl;
@h3__font-weight: 600;
@h3__line-height: @line-height__2xl;
@h3__text-transform: false;
@h3__letter-spacing: false;
@h3__margin-top: @4;
@h3__margin-bottom: @2;

@h4__font-size: @font-size__xl;
@h4__font-weight: 600;
@h4__line-height: @line-height__xl;
@h4__text-transform: false;
@h4__letter-spacing: false;
@h4__margin-top: false;
@h4__margin-bottom: @1;

@h5__font-size: false;
@h5__font-weight: false;
@h5__line-height: false;
@h5__text-transform: false;
@h5__letter-spacing: false;
@h5__margin-top: false;
@h5__margin-bottom: @1;

@h6__font-size: false;
@h6__font-weight: false;
@h6__line-height: false;
@h6__text-transform: false;
@h6__letter-spacing: false;
@h6__margin-top: false;
@h6__margin-bottom: @1;
```

## Links

```scss
@link__text-decoration: none;
@link__hover__text-decoration: underline;
@link__text-color: var(--blue);
@link__text-alpha: .85;
```

## Prose

> Prose styles are used at the CMS pages.

```scss
@prose__font-size: @font-size__lg;
@prose__line-height: @line-height__lg;
```
