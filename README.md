* [template-package-no-tests](https://github.com/dustuu/template-package-no-tests) shows what happens when all repository variables and secrets are configured properly, but the actual Unit Test files are removed from the repository.
  * The `Build Release` workflow will fail because the user has indicated that Unit Tests are present, but they are not:
  * ![image](https://github.com/vrchat-community/template-package/assets/101824882/b3ee3a66-4494-4e04-bb00-362087376059)
  * The `Build Repo Listing` workflow will fail as expected because there are no published releases.

Both badges will be broken because there are no releases:

[![VPM Package Version](https://img.shields.io/vpm/v/com.vrchat.demo-template?repository_url=https%3A%2F%2Fdustuu.github.io%2Ftemplate-package-no-tests%2Findex.json)](https://dustuu.github.io/template-package-no-tests)

[![Code Coverage](https://dustuu.github.io/template-package-no-tests/coverage/badge_linecoverage.svg)](https://dustuu.github.io/template-package-no-tests/coverage)
