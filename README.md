# PhpMeetJS
PHP 8 utility library mirroring JavaScript collection APIs (including *Lodash.js*) for seamless full-stack development

## Context

### Problem
As a full-stack developer, one of the most significant pain points is regularly switching between environments. While using stacks that share common principles like OOP or design pattern approaches can ease this transition, it's not always the case. Beyond architectural considerations, **API differences between stacks present additional and major challenges**. **This library aims to address this specific pain point**.

### Solution
The goal of this library is to provide a utility library that shares the same API as Lodash.js. 

**Why Lodash?**

1. It's one of the primary utility libraries used by the JavaScript developer community.
2. Another library called 'underscore' has already been mirrored (see: underscore-php).

**Mirroring Recent Native JavaScript Collection API**

Another key point is that the library will also integrate some well-established native JavaScript collection APIs.
We will prioritize the most recent additions to ECMAScript, starting with ES2015 features.

## Roadmap Strategy
The development will undergo several phases:

1. **0.0.0.alpha-nightly**: *unstable / private* - This version will consist of regular additions without a clear vision path. The goal is to implement the first elements and learn from them to gradually iterate with the experience gained. The second most important aspect of this version is to provide an embryonic implementation of two crucial parts of a utility library: tests (quality) and documentation.

2. **0.0.0.beta-nightly**: *unstable / protected* - This version will be partially opened to restricted observers to ensure an external point of view early on and to verify that the design is community-compatible.

3. **0.x.y**: *unstable / public* - The source code is public but not open to code contributions, only suggestions. A roadmap is provided outlining the different API elements to be integrated until release.

4. **1.0.0.beta-nightly**: *unstable / public* - The version has a complete test suite and required API methods. The source code is open to contributions for refactoring and bug fixes. This version will remain in beta until all API members are stable and the documentation website is ready.

5. **1.0.0.rc**: *stable / public* - The first stable, releasable version, recommended for development and production environment usage. This version will remain RC until at least one third-party major project uses it, or a minimum star count is reached.

6. **1.0.0**: *stable / public* - The first Gold stable version. The version is open to contributions for new features, fixes, and refactoring. A new roadmap for the next major version is being developed.

## Constraints

### Technical Constraints
Below are the development technical and project constraints we will be following:

- **Performance**: Ensuring the API has the lowest time complexity.
- **Quality**: Ensuring the code has the highest test coverage.
- **Scalability**: Ensuring the design allows the library to easily evolve over time.
- **Backward Compatibility**: Ensuring the design is built so that each major version has minimal breaking changes.
- **Readability**: Ensuring the code is easily readable.
- **Comment-First**: Ensuring the code has high comment coverage.
- **Decision-Driven**: Ensuring each design choice is justified.

### Stability
- Make it explicit that all versions before 1.0.0.rc are not recommended for production environments.

## Contributing
There will be no contributions accepted until the project reaches a mature and stable version. The target version for accepting contributions is set to 1.0.
