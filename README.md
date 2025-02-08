refactor: update license text to point to angular.dev
- Update license text to point to angular.dev instead of angular.io

feat(list): Add filtering functionality to the employee list

- Implemented a new filter feature to allow users to filter employees by department.
- Updated the UI to include a dropdown for department selection.
- Refactored the employee service to support filtering.
- Closes #123

refactor(dialog): Improve form validation in the leave request dialog

- Added custom validators for date and time fields.
- Improved error messages for better user experience.
- Refactored form initialization logic for better readability.
- Related to #456

fix(detail): Correct date formatting issue in the employee detail view

- Fixed an issue where dates were displayed in the wrong format.
- Updated the date pipe to use the correct locale settings.
- Added unit tests to cover the date formatting logic.
- Fixes #789

docs: Update README with new setup instructions

- Added instructions for setting up the development environment.
- Included steps for running the application locally.
- Updated the list of dependencies and their versions.

style: Apply consistent formatting to dialog component

- Reformatted the dialog-papeletas-de-salida.component.ts file for better readability.
- Ensured consistent use of single quotes and indentation.
- No functional changes.

refactor(dialog): Shorten service injection names and improve method definitions

- Renamed injected service variables for brevity and clarity.
- Added 'private' access modifier to methods that should not be publicly accessible.
- Specified 'void' return type for methods that do not return a value.
