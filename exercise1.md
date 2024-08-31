For this task I picked Rust as the language.

For Rust, it seems that the most common choice for a linter is called Clippy. Clippy is a Cargo crate with over 700 linter rules. Cargo crates are what dependencies are called by the Cargo build tool, which is shipped with Rust. Cargo seems to be very popular and acts as the de facto build tool and package manager, and would be used as the build tool in a CI/CD scenario.
And as an added bonus, Cargo is also a test runner, and a pretty popular one at that.

All the major public cloud providers have a CI offering, such as Azure DevOps, AWS CodePipelines and GCP Cloud Build. There are also other products that focus mostly on CI, such as CircleCI and Travis. GitLab, which is one of the leading competitors of GitHub, also offers a CI/CD platform that is tightly integrated to their other GitLab offerings.

I think having a CI/CD pipeline for Rust would be easier in the cloud. It may not be a natively supported language in all services, but seems to be in some. Nevertheless having basically one tool for building, testing (and also linting via a dependency) seems like an easy scenario that could be implemented in a cloud-based CI/CD pipeline.
