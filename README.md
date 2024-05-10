# n00dWorkshop

### Welcome to n00dWorkshop!

n00dWorkshop is a comprehensive integration of all plugins offered by n00dbeaverStudios for Unreal Engine. This unified project allows developers to explore, dissect, and tailor these tools to fit their specific project needs while providing practical insights into how each component interacts seamlessly.

This example project is developed in C++ due to the requirements of the Binary Editor. When cloning submodules, you'll need to manually compile them. Alternatively, if you prefer using plugins directly from the Launcher, simply drop them into the Plugins folder, and they should integrate seamlessly with this project.

**Important Note**: Your own project does not need to be C++-based to utilise these plugins effectively. If you download the plugins either from the Releases section within each GitHub repository or directly from the Launcher, they come pre-compiled with all necessary binaries, ready for immediate use.

## Installation

Follow these steps to set up n00dWorkshop on your system.

### Prerequisites
- **Windows:** Install [Git SCM](https://git-scm.com/) if not already installed.
- **Linux:** Git should be pre-installed.
- **Recommended:** Use a desktop Git client like [GitHub Desktop for Windows](https://desktop.github.com/) or the [setup for Linux](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1). Choose the client that best fits your workflow.

### Verification
If you own the plugins but do not have repository access, visit [Verification](https://verify.n00dbeaverstudios.com/) to verify your ownership and gain the necessary access.

## Getting Started

### Clone the Project
To clone n00dWorkshop along with all associated submodules, execute the following commands in your terminal:
```bash
git clone https://github.com/n00dbeaverstudios/n00dWorkshop.git
cd n00dWorkshop
git submodule update --init --recursive
```
This set of commands initializes and updates the submodules recursively.

### Keep updated
Command to update your submodules:

```bash
git submodule update --remote
```

## Dive In!
You’re all set! Explore the capabilities of n00dWorkshop and start building your projects with enhanced flexibility and power. See you inside!
