# Vitejs based React TypeScript template

### Project setup steps:
- `npm init vite@latest`
  - provide `project-name`
  - select `react`
  - Select `react-ts`
  - navigate to the project folder
- `npm install`
- `npm run dev`

### Github setup steps:
- Create an empty repo in Github
- Configure base property as repo path inside [vite.config.ts](./vite.config.ts)
- Commit and push the local code base to Github repo
- Setup the CI/CD to build on every push/PR [main.yml](./.github/workflows/main.yml)
- Activate the Github pages and [https://{username}.github.io/{repo}/dist/](https://sadanandpai.github.io/vite-react-template/dist/)
