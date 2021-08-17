# CHANGELOG

## 2.3.0.1 (2021-08-17)

- Transitioning development lead back to doug@unlikelysource.com
- Moved repository back to https://github.com/dbierer
- Updated documentation to correct a couple of links

## 2.3.0 (2018-05-25)

- Adds a new translation (Slovenian - Thanks to Ervin ervin.bizjak@gmail.com).

## 2.2.0 (2018-02-23)

- Fixes issue #16 - Language overrides do not work in SEF 1.8.9 and Joomla 3.6.5.
- Fixes all functional tests by having them run on the Sauce Labs Selenium Server.
- Fixes a minor issue with the upload error messages.

## 2.1.0 (2017-12-22)

- Fixes issue #15 - Allow users to configure an automated reply email to those submitting the form.
- Fixes issue #18 - Getting error of missing closing DIV.
- Fixes issue #22 - Allow to easily modify SEF's rendering by using its internal methods.
- Sets JForm as Simple Email Form's default mode.
- Offers a complete API documentation for developers.

## 2.0.1 (2017-02-24)

- Fixes issue #17 - JForm translations not explained well enough in documentation.
- Makes the module compliant with PHP-PDS 1.0 standards.
- Fixes a minor issue concerning the extension.xml file.

## 2.0.0 (2017-01-28)

- Fixes issue #3 - Make the module compliant to Joomla standards (https://joomla.github.io/coding-standards/).
- Fixes issue #4 - Make the module more compliant to PSR-2 standards.
- Fixes issue #5 - Isolate initialization and library code from the module's main implementation.
- Fixes issue #6 - Replace all direct usage of global variables by the appropriate Joomla objects.
- Fixes issue #7 - Replace all hard-coded form elements by the JForm element objects.
- Fixes issue #8 - Refactor language support in order to give the user the option of using the built-in Joomla language capabilities.
- Fixes issue #9 - Get unit test code coverage up to at least 70%.
- Fixes issue #10 - Use Git version control and phpDocumentor to generate the project's User Guide and Developer Documentation.
- Fixes issue #11 - Add a Required/Optional selector to the upload field settings.
- Fixes issue #13 - Warn the administrator before saving if "Send Results To" field is empty or invalid.
- Adds a new translation (Belarusian - Thanks to Yury <y.sapozhkov@gmail.com>).
- Makes the module compliant with the new JED requirements of the 10th of January 2017 (https://extensions.joomla.org/support/knowledgebase/item/joomla-update-system-requirement).
- DEPRECATED : Simple Email Form's Classic form.  It will be removed in version 3.0.0.

## 1.8.9 (2016-07-23)

- Fixes issue #2 - Confirmation messages when uploading more than one file.
- Fixes issue #12 - File uploaded in spite of wrong captcha.

## 1.8.8 (2016-07-04)

- Fixes issue #1 - Error messages are displayed to the user when leaving
  some upload fields empty on form submission.
