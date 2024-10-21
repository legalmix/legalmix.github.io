<h1 align=center>Astro + Tailwind CSS + TypeScript Starter and Boilerplate</h1>

## 🔗 Integrations

- astro/react
- astro/sitemap
- astro/tailwind

## 🚀 Getting Started

### 📦 Dependencies

- astro v4.12+
- node v20.10+
- npm v10.2+
- tailwind v3.4+

### 👉 Install Dependencies

```bash
npm install
```

### 👉 Development Command

```bash
npm run dev
```

### 👉 Build Command

```bash
npm run build
```

### 👉 Publish to GitHub Pages

- In the repository, under `Settings > Pages`, make sure to select `GitHub Actions` under `Build and deployment > Source`.
- You can then run the workflow manually on the default branch.

It will create a new environment called `github-pages`, in which the deployment will run.

### 👉 Build and Run With Docker

```bash
docker build -t astroplate .
# or
# docker --build-arg INSTALLER=npm build -t astroplate .
# or
# docker --build-arg INSTALLER=pnpm build -t astroplate .

docker run -p 3000:80 astroplate
# or
# docker run --rm -p 3000:80 astroplate
```

To access the shell within the container:

```bash
docker run -it --rm astroplate ash
```

<!-- licence -->

## 📝 License

Released under the MIT license.
