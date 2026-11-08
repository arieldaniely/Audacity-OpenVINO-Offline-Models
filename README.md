# Audacity OpenVINO Models

Automated downloader and GitHub Release publisher for:

* HTDemucs v4 music separation
* DeepFilterNet2 noise suppression
* DeepFilterNet3 noise suppression

## Usage

1. Create a public GitHub repository.
2. Upload the contents of this project.
3. Open Actions.
4. Select Download and Publish Audacity Models.
5. Click Run workflow.
6. Keep version as v1.0.0.
7. Run workflow.

The workflow downloads the original Intel model files,
checks SHA256 hashes and publishes a GitHub Release.

The GitHub-hosted runner must have access to Hugging Face.
No Hugging Face access is required on your local computer.

Original model files and their respective licenses remain
the property of their original authors.