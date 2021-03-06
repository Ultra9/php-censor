Changelog 1.1
=============

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to 
[Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [1.1.1 (Birdperson)](https://github.com/php-censor/php-censor/tree/1.1.1) (2019-06-15)

[Full Changelog](https://github.com/php-censor/php-censor/compare/1.1.0...1.1.1)

### Added

- `FUNDING.yml` config for GitHub.

### Fixed

- Information about versions in `README.md` file.
- Potential bug with `Symfony\Component\Process\Process::_construct` parameter `cwd`.

### Changed

- Updated dependencies.


## [1.1.0 (Birdperson)](https://github.com/php-censor/php-censor/tree/1.1.0) (2019-05-25)

[Full Changelog](https://github.com/php-censor/php-censor/compare/1.0.10...1.1.0)

**Release includes all changes from release 1.0.10 and additionally:**

### Added

- Phlint plugin. Pull request [#280](https://github.com/php-censor/php-censor/pull/280). Thanks to 
[@panosru](https://github.com/panosru).
- Phpstan plugin. Pull request [#279](https://github.com/php-censor/php-censor/pull/279). Thanks to 
[@panosru](https://github.com/panosru).
- Pahout plugin. Pull request [#278](https://github.com/php-censor/php-censor/pull/278). Thanks to 
[@panosru](https://github.com/panosru).
- Psalm plugin. Pull request [#277](https://github.com/php-censor/php-censor/pull/277). Thanks to 
[@panosru](https://github.com/panosru).
- BitbucketNotify plugin. Pull request [#302](https://github.com/php-censor/php-censor/pull/302). Thanks to 
[@EugenGanshorn](https://github.com/EugenGanshorn).
- BitBucket Server project source (Like Github, Bitbucket, etc.). Pull request 
[#286](https://github.com/php-censor/php-censor/pull/286). Thanks to [@fejal](https://github.com/fejal).
- PostgreSQL `SSLMODE` connection option. Pull request [#283](https://github.com/php-censor/php-censor/pull/283). 
Thanks to [@mikebronner](https://github.com/mikebronner).
- New build sources for rebuild from WEB and CLI with pointer to parent build. Issue 
[#272](https://github.com/php-censor/php-censor/issues/272).
- Some additional types for Github (Git type) and Bitbucket (Git and Hg types) webhooks. Issue 
[#284](https://github.com/php-censor/php-censor/issues/284).

### Fixed

- Webhook for private Bitbucket repositories. Pull request [#281](https://github.com/php-censor/php-censor/pull/281). 
Thanks to [@EduardMalik](https://github.com/EduardMalik).
- Environment variables for child processes. Issue [#212](https://github.com/php-censor/php-censor/issues/212), 
[#261](https://github.com/php-censor/php-censor/issues/261). Pull requests 
[#269](https://github.com/php-censor/php-censor/pull/269), [#250](https://github.com/php-censor/php-censor/pull/250). 
Thanks to [@jwmwalrus](https://github.com/jwmwalrus).

### Changed

- Flushing errors before executing stage `complete` to make them available for `complete` stage plugins. Pull request 
[#294](https://github.com/php-censor/php-censor/pull/294). Thanks to [@EugenGanshorn](https://github.com/EugenGanshorn).
- **Configuration section `b8.database` is deprecated. Use instead section `php-censor.database`. Issue 
[#289](https://github.com/php-censor/php-censor/issues/289)**.


## Other versions

- [0.x Changelog](/docs/CHANGELOG_0.x.md)
- [1.0 Changelog](/docs/CHANGELOG_1.0.md)
