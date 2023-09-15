# [medevs.xyz](https://medevs.xyz/) build with Astro

## Key Features

- Astro v3.0 Fast 🚀
- View Transitions from [Astro](https://docs.astro.build/en/guides/view-transitions/)
- TailwindCSS Utility classes
- Accessible, semantic HTML markup
- Responsive & SEO-friendly
- Dark / Light mode, using Tailwind and CSS variables
- [Astro Assets Integration](https://docs.astro.build/en/guides/assets/) for optimised images
- MD & [MDX](https://docs.astro.build/en/guides/markdown-content/#mdx-only-features) posts
- [Satori](https://github.com/vercel/satori) for creating open graph png images
- Pagination
- [Automatic RSS feed](https://docs.astro.build/en/guides/rss)
- Shiki code syntax styling
- Auto-generated [sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/)
- [Pagefind](https://pagefind.app/) static search library integration
- [Astro Icon](https://github.com/natemoo-re/astro-icon) svg icon component

## Commands

Replace pnpm with your choice of npm / yarn

| Command          | Action                                                         |
| :--------------- | :------------------------------------------------------------- |
| `pnpm install`   | Installs dependencies                                          |
| `pnpm dev`       | Starts local dev server at `localhost:3000`                    |
| `pnpm build`     | Build your production site to `./dist/`                        |
| `pnpm postbuild` | Pagefind script to build the static search of your blog posts  |
| `pnpm preview`   | Preview your build locally, before deploying                   |
| `pnpm sync`      | Generate types based on your config in `src/content/config.ts` |

## Configure

- `src/site.config.ts` for basic site meta data
- `astro.config.ts` site property

## Credit

starter with [Astro Theme Cactus](https://github.com/chrismwilliams/astro-theme-cactus)

## License

MIT
