# Applitools Example: Image Tester

This is the example project for the [Image Tester tutorial](https://devtst.applitools.com/tutorials/quickstart/screenshots/cli/images).
It shows how to start automating visual tests
with [Applitools Eyes](https://applitools.com/platform/eyes/) using the [Image Tester](https://github.com/applitools/ImageTester) CLI tool. 

Image Tester is able to run tests on both PDFs and image files.

To run this example project, you'll need:

1. An [Applitools account](https://auth.applitools.com/users/register), which you can register for free
2. [Java Runtime Environment](https://www.oracle.com/java/technologies/downloads/) version 8 or higher

To execute Image Tester tests, set the `APPLITOOLS_API_KEY` environment variable
to your [account's API key](https://applitools.com/tutorials/guides/getting-started/registering-an-account).

To run the Image Tester:
1. Clone this repository

```
https://github.com/valandi/example-imagetester-cli
```
2. Change your working directory to example-imagetester-cli
```
cd example-imagetester-cli
```
3. Execute Image Tester

```
java -jar ImageTester_3.1.0.jar -f images_and_pdfs/
```

**For full instructions on running this project, take our
[Image Tester tutorial](https://devtst.applitools.com/tutorials/quickstart/screenshots/cli/images)!**