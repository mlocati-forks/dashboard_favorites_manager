# Publishing a new version

1. Update the `PACKAGE_VERSION` constant in the main `controller.php` (eg `PACKAGE_VERSION = '1.2.3'`)
2. Create a tag with the same version (eg `'1.2.3`')
3. Push the tag
4. The [`create-draft-release.yml`](https://github.com/concrete5-community/dashboard_favorites_manager/actions/workflows/create-draft-release.yml) will create a draft release, attaching to it the distribution .zip file
5. Go to to the [releases page](https://github.com/concrete5-community/dashboard_favorites_manager/releases), edit and publish that release
