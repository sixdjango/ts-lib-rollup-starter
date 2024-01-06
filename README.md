## ts-lib-rollup-starter

本项目是一个基于 rollup、ts、tslib、vitepress、pnpm 构建的快速启动项目，主要针对存ts的lib库

> 如果是需要组件库的搭建，请使用vite进行搭建

### ci

> 当把`tag` push到远程仓库（github）时，会自动触发 ci cd

- 自动 publish 到 `npm` 如果 `package.json` 中的 `version` 属性与 `npm` 中的版本重复，则取消这次部署
- 自动生成 `release` 版本
