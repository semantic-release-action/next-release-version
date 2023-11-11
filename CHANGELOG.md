## [4.0.9](https://github.com/semantic-release-action/next-release-version/compare/v4.0.8...v4.0.9) (2023-11-11)


### Bug Fixes

* **deps:** update dependency semantic-release to v22 ([c264622](https://github.com/semantic-release-action/next-release-version/commit/c264622bb87bd3eb4781d17b535a37b8b6b12f9b))

## [4.0.8](https://github.com/semantic-release-action/next-release-version/compare/v4.0.7...v4.0.8) (2023-06-18)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.5 ([5555f2a](https://github.com/semantic-release-action/next-release-version/commit/5555f2a5aa725c001b0f4b81c149180520542fab))

## [4.0.7](https://github.com/semantic-release-action/next-release-version/compare/v4.0.6...v4.0.7) (2023-05-06)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.2 ([1f1a85b](https://github.com/semantic-release-action/next-release-version/commit/1f1a85b1e619510a15ee5b0b1874c32ab0757f23))

## [4.0.6](https://github.com/semantic-release-action/next-release-version/compare/v4.0.5...v4.0.6) (2023-03-25)


### Bug Fixes

* **deps:** update dependency semantic-release to v21 ([eb5bdd5](https://github.com/semantic-release-action/next-release-version/commit/eb5bdd50f77bdcb2377691027f3dbb44f4c5abce))

## [4.0.5](https://github.com/semantic-release-action/next-release-version/compare/v4.0.4...v4.0.5) (2023-02-26)


### Bug Fixes

* override plugins for each release step ([538bd6f](https://github.com/semantic-release-action/next-release-version/commit/538bd6fa821c9cec18a7cc55002454e64743e543)), closes [#11](https://github.com/semantic-release-action/next-release-version/issues/11)

## [4.0.4](https://github.com/semantic-release-action/next-release-version/compare/v4.0.3...v4.0.4) (2023-02-26)


### Bug Fixes

* use runner temp directory instead of github workspace ([ab95086](https://github.com/semantic-release-action/next-release-version/commit/ab95086fc6331ca81872c7a52cd4e36cce5497dd))

## [4.0.3](https://github.com/semantic-release-action/next-release-version/compare/v4.0.2...v4.0.3) (2023-02-25)


### Bug Fixes

* use host semantic-release configuration ([ebbae10](https://github.com/semantic-release-action/next-release-version/commit/ebbae1096f7f4fa8ef46e24f5c8108fa565b3604)), closes [#11](https://github.com/semantic-release-action/next-release-version/issues/11)

## [4.0.2](https://github.com/semantic-release-action/next-release-version/compare/v4.0.1...v4.0.2) (2023-02-22)


### Bug Fixes

* clarify step name ([608298d](https://github.com/semantic-release-action/next-release-version/commit/608298d9563d012bc4c489c8e9cc48eec18dbd5c))

## [4.0.1](https://github.com/semantic-release-action/next-release-version/compare/v4.0.0...v4.0.1) (2023-02-12)


### Bug Fixes

* upgrade semantic-release-action/next-release-version to v4 ([88fae67](https://github.com/semantic-release-action/next-release-version/commit/88fae67638b96e694cc9e369427a1606963ed6e2))

# [4.0.0](https://github.com/semantic-release-action/next-release-version/compare/v3.0.1...v4.0.0) (2023-02-12)


### Reverts

* Revert "refactor!: expose an action instead of a reusable workflow" ([4edde6d](https://github.com/semantic-release-action/next-release-version/commit/4edde6dc93308c4029bbc129ba73a4424fa78750))


### BREAKING CHANGES

* expose only a reusable workflow

## [3.0.1](https://github.com/semantic-release-action/next-release-version/compare/v3.0.0...v3.0.1) (2023-02-12)


### Bug Fixes

* correct syntax error in cp arguments ([4d18458](https://github.com/semantic-release-action/next-release-version/commit/4d18458be6d5320bbf4f9fec5b478b18f0352d10))

# [3.0.0](https://github.com/semantic-release-action/next-release-version/compare/v2.0.6...v3.0.0) (2023-02-12)


* refactor!: expose an action instead of a reusable workflow ([ba19125](https://github.com/semantic-release-action/next-release-version/commit/ba19125172d6660534da9d1e5f45595e1fba6e46)), closes [#9](https://github.com/semantic-release-action/next-release-version/issues/9)


### BREAKING CHANGES

* expose an action instead of a reusable workflow

To simplify invocation and permit use within a single job, this project
must now be invoked as an action instead of a reusable workflow.

The simplest way to use this action is now:

```yaml

## [2.0.6](https://github.com/semantic-release-action/next-release-version/compare/v2.0.5...v2.0.6) (2023-02-12)


### Bug Fixes

* git ignore the correct directory ([564e174](https://github.com/semantic-release-action/next-release-version/commit/564e174a8b2d2a1919fcdc599f294f73e598258c))

## [2.0.5](https://github.com/semantic-release-action/next-release-version/compare/v2.0.4...v2.0.5) (2023-02-12)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.1.0 ([6b92a6d](https://github.com/semantic-release-action/next-release-version/commit/6b92a6d82015d588d82cc2b3e8bc2620c6eca17a))

## [2.0.4](https://github.com/semantic-release-action/next-release-version/compare/v2.0.3...v2.0.4) (2023-01-16)


### Bug Fixes

* grant workflow write permissions to contents ([3674996](https://github.com/semantic-release-action/next-release-version/commit/3674996059bf783c65bb6d5bba1758dc037f2ee4))

## [2.0.3](https://github.com/semantic-release-action/next-release-version/compare/v2.0.2...v2.0.3) (2023-01-16)


### Bug Fixes

* only modify package.json when it exists ([0f09401](https://github.com/semantic-release-action/next-release-version/commit/0f094010e3735b1cb2c53d20ffe2290b62bef5eb))

## [2.0.2](https://github.com/semantic-release-action/next-release-version/compare/v2.0.1...v2.0.2) (2023-01-16)


### Bug Fixes

* use shared action to support copying action manifests ([7a0487a](https://github.com/semantic-release-action/next-release-version/commit/7a0487a84eefe94909d4578d64d3f3bd253d2fc2))

## [2.0.1](https://github.com/semantic-release-action/next-release-version/compare/v2.0.0...v2.0.1) (2023-01-16)


### Bug Fixes

* move workflow under .github/workflows ([b49c6d2](https://github.com/semantic-release-action/next-release-version/commit/b49c6d297147cc9aa3434e916036e2d46b11eb5d))

# [2.0.0](https://github.com/semantic-release-action/next-release-version/compare/v1.0.14...v2.0.0) (2023-01-16)


* refactor!: convert action to a workflow ([7665eca](https://github.com/semantic-release-action/next-release-version/commit/7665ecaf872b4a634f2e2b8f1915fdfd9221387e))


### BREAKING CHANGES

* convert this action to a workflow

You can now invoke this workflow as follows:

In the first workflow:

```yaml

## [1.0.14](https://github.com/semantic-release-action/next-release-version/compare/v1.0.13...v1.0.14) (2023-01-14)


### Bug Fixes

* **ci:** invoke reusable workflow correctly ([49f3078](https://github.com/semantic-release-action/next-release-version/commit/49f30780691ed7be2d6ad75492643be8fd8aebe4))
* **ci:** update semantic-release-action/github-actions to v4 ([67a426f](https://github.com/semantic-release-action/next-release-version/commit/67a426f1165557a7e54d28675326ac3531e60e83))

## [1.0.13](https://github.com/semantic-release-action/next-release-version/compare/v1.0.12...v1.0.13) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/next-release-version ([8e11762](https://github.com/semantic-release-action/next-release-version/commit/8e117626f3d235cc49f1472a65063ff6684ed51d))

## [1.0.12](https://github.com/semantic-release-extras/next-release-version/compare/v1.0.11...v1.0.12) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/github-actions ([7f21fbe](https://github.com/semantic-release-action/next-release-version/commit/7f21fbe47c33d2b2551ad9eda0b22ac50c3d827f))

## [1.0.11](https://github.com/semantic-release-action/next-release-version/compare/v1.0.10...v1.0.11) (2023-01-12)


### Bug Fixes

* **deps:** upgrade install-github-release-binary to v2 ([3aa61c0](https://github.com/semantic-release-action/next-release-version/commit/3aa61c08488392e7d9421188056ca564eb896bc3))

## [1.0.10](https://github.com/semantic-release-action/next-release-version/compare/v1.0.9...v1.0.10) (2023-01-11)


### Bug Fixes

* create directory before writing file into it ([fa36fa9](https://github.com/semantic-release-action/next-release-version/commit/fa36fa9506bbe9433920d4f9115c67e07769b279))

## [1.0.9](https://github.com/semantic-release-action/next-release-version/compare/v1.0.8...v1.0.9) (2023-01-11)


### Bug Fixes

* use temporary working directory ([24fda35](https://github.com/semantic-release-action/next-release-version/commit/24fda35cfb6029954519051467e50363750a9557))

## [1.0.8](https://github.com/semantic-release-action/next-release-version/compare/v1.0.7...v1.0.8) (2023-01-08)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.0.2 ([3f74ff9](https://github.com/semantic-release-action/next-release-version/commit/3f74ff9d088595c5600520e7765a9b3a9144b15c))

## [1.0.7](https://github.com/semantic-release-action/next-release-version/compare/v1.0.6...v1.0.7) (2023-01-08)


### Bug Fixes

* **ci:** use faster install method ([8b5435d](https://github.com/semantic-release-action/next-release-version/commit/8b5435d5bcfde14d66741d30de3602074c1645dd))

## [1.0.6](https://github.com/semantic-release-action/next-release-version/compare/v1.0.5...v1.0.6) (2023-01-07)


### Bug Fixes

* **deps:** update dependency semantic-release to v20 ([2e4f7ba](https://github.com/semantic-release-action/next-release-version/commit/2e4f7baec1332680ae8ce74cb59d89df96692b06))

## [1.0.5](https://github.com/semantic-release-action/next-release-version/compare/v1.0.4...v1.0.5) (2023-01-07)


### Bug Fixes

* restore package.json ([9d19f5f](https://github.com/semantic-release-action/next-release-version/commit/9d19f5f89ac210c99667882b76114f9006beb52a))

## [1.0.4](https://github.com/semantic-release-action/next-release-version/compare/v1.0.3...v1.0.4) (2023-01-07)


### Bug Fixes

* do not fail if semantic-release config cannot be removed ([58c4817](https://github.com/semantic-release-action/next-release-version/commit/58c481701cf1ce98fdd6fbf35c01b75bc257ee29))

## [1.0.3](https://github.com/semantic-release-action/next-release-version/compare/v1.0.2...v1.0.3) (2023-01-07)


### Bug Fixes

* import Node.js manifests before configuring Node.js ([c8a3e0e](https://github.com/semantic-release-action/next-release-version/commit/c8a3e0e7112379804fad3786178dda1e0bd212cb))

## [1.0.2](https://github.com/semantic-release-action/next-release-version/compare/v1.0.1...v1.0.2) (2023-01-06)


### Bug Fixes

* **ci:** use semantic-release-your-github-action ([95f8292](https://github.com/semantic-release-action/next-release-version/commit/95f82921806160d0b3be42b23c7554148de5e123))

## [1.0.1](https://github.com/semantic-release-action/next-release-version/compare/v1.0.0...v1.0.1) (2022-12-28)


### Bug Fixes

* **semantic-release:** move major and minor tag pointers ([814529e](https://github.com/semantic-release-action/next-release-version/commit/814529e5e49a0ba84464a3ed3cc4eb7f617dfd71))

# 1.0.0 (2022-12-28)


### Bug Fixes

* remove project's existing semantic-release configuration ([e3a8e89](https://github.com/semantic-release-action/next-release-version/commit/e3a8e895c7cfb17b39cb24ec7a902d20cb552c05))
* satisfy required schema ([ca7d06b](https://github.com/semantic-release-action/next-release-version/commit/ca7d06b494ca1039ceaa85213e6973d2ef9ff7af))
