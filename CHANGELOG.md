## [3.0.2](https://github.com/trustedshops-public/circleci-orb-ansible/compare/3.0.1...3.0.2) (2023-06-29)


### Bug Fixes

* Use github-utils orb for rewriting git clone url ([97e37e3](https://github.com/trustedshops-public/circleci-orb-ansible/commit/97e37e34ae81a989312dc546ab934d2b65009c09))

## [3.0.1](https://github.com/trustedshops-public/circleci-orb-ansible/compare/3.0.0...3.0.1) (2023-06-29)


### Bug Fixes

* Add token as username to github access token ([b8e7c0b](https://github.com/trustedshops-public/circleci-orb-ansible/commit/b8e7c0be56239861ab1dc7c49678f057c5897b56))

# [3.0.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/2.0.0...3.0.0) (2023-05-26)

# [2.0.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.4.0...2.0.0) (2022-01-18)


### Features

* **#4:** Add no_output_timeout to run-playbook ([#5](https://github.com/trustedshops-public/circleci-orb-ansible/issues/5)) ([2fe228e](https://github.com/trustedshops-public/circleci-orb-ansible/commit/2fe228e524929ce3e7d9779e1d22f6b47d324e70)), closes [#4](https://github.com/trustedshops-public/circleci-orb-ansible/issues/4)


### BREAKING CHANGES

* **#4:** Default timeout for provision set to 15 minutes instead of 10min as used by CircleCI

# [1.4.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.3.1...1.4.0) (2021-12-10)


### Features

* **#2:** Add diff and check parameter to provision job ([c77afb9](https://github.com/trustedshops-public/circleci-orb-ansible/commit/c77afb98d0bc8986b1c4996b069e2e08882a64e5)), closes [#2](https://github.com/trustedshops-public/circleci-orb-ansible/issues/2)
* **#2:** Add support for check parameter ([37d88bf](https://github.com/trustedshops-public/circleci-orb-ansible/commit/37d88bf3fdd811ca736f48623e96c6534019248d)), closes [#2](https://github.com/trustedshops-public/circleci-orb-ansible/issues/2)
* **#2:** Add support for diff parameter ([0321293](https://github.com/trustedshops-public/circleci-orb-ansible/commit/0321293f5976dbd0ff44e389ba6feb4e30dafef1)), closes [#2](https://github.com/trustedshops-public/circleci-orb-ansible/issues/2)

## [1.3.1](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.3.0...1.3.1) (2021-11-22)


### Bug Fixes

* Fix limit parameter ([5fc5a4d](https://github.com/trustedshops-public/circleci-orb-ansible/commit/5fc5a4de69dfa77535ffca4c3b18c5b74703e015))

# [1.3.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.2.0...1.3.0) (2021-11-22)


### Features

* Add env vars for default executor ([#1](https://github.com/trustedshops-public/circleci-orb-ansible/issues/1)) ([e5cbe11](https://github.com/trustedshops-public/circleci-orb-ansible/commit/e5cbe1198da3292464e3749c1f29582900e08577))

# [1.2.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.1.2...1.2.0) (2021-11-17)


### Features

* Add check for already installed mitogen and ansible ([e5e9f24](https://github.com/trustedshops-public/circleci-orb-ansible/commit/e5e9f2414cb1e91f9570638ac8867f8e310c6c3a))

## [1.1.2](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.1.1...1.1.2) (2021-11-17)


### Bug Fixes

* Fix install move for mitogen ([b491679](https://github.com/trustedshops-public/circleci-orb-ansible/commit/b491679ac3e0a4505daed204c414dfad02bcf0e6))

## [1.1.1](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.1.0...1.1.1) (2021-11-17)


### Bug Fixes

* Fix role install ([32e44aa](https://github.com/trustedshops-public/circleci-orb-ansible/commit/32e44aae4bb65c3b03b6646417dcf89967e286cb))

# [1.1.0](https://github.com/trustedshops-public/circleci-orb-ansible/compare/1.0.0...1.1.0) (2021-11-17)


### Features

* Add provision as dedicated command ([398f8fa](https://github.com/trustedshops-public/circleci-orb-ansible/commit/398f8fabbcc19e929042e85d7b1341426e3ee1b9))

# 1.0.0 (2021-11-17)


### Features

* Add initial orb sources ([38eb22c](https://github.com/trustedshops-public/circleci-orb-ansible/commit/38eb22cbeaafb47afbc5e4574ef403e1be84150e))
