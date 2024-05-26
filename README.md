# n00dWorkshop

### Welcome to n00dWorkshop!

n00dWorkshop is a comprehensive integration of all plugins offered by n00dbeaverStudios for Unreal Engine. This unified project allows developers to explore, dissect, and tailor these tools to fit their specific project needs while providing practical insights into how each component interacts seamlessly.

This example project in the main repository is developed in C++ due to the requirements of the Binary Editor. When cloning submodules, you'll need to manually compile them. Alternatively, if you prefer using plugins directly from the Launcher, simply drop them into the Plugins folder of the project download from the Releases, and they should integrate seamlessly with this project.

**Important Note**: Your own project does not need to be C++-based to utilise these plugins effectively. If you download the plugins either from the Releases section within each GitHub repository or directly from the Launcher, they come pre-compiled with all necessary binaries, ready for immediate use.

# Installation

Follow these steps to set up n00dWorkshop on your system.

## Prerequisites for cloning this repository
- **Windows:** Install [Git SCM](https://git-scm.com/) if not already installed.
- **Linux:** Git should be pre-installed.
- **Recommended:** Use a desktop Git client like [GitHub Desktop for Windows](https://desktop.github.com/) or the [setup for Linux](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1). Choose the client that best fits your workflow.

## Prerequisites for Content (mandatory)
### Unreal Engine Marketplace Permanantly Free Assets
This project leverages permanantly free assets that are available on the marketplace, to use this project you must acquire the files from the Launcher that we are using for various features, as we will not be including them in this repository. 

- [Human Vocalizations](https://www.unrealengine.com/marketplace/en-US/product/human-vocalizations)
- [Stylized Egypt](https://www.unrealengine.com/marketplace/en-US/product/stylized-egypt)
- [Niagara Footstep VFX](https://www.unrealengine.com/marketplace/en-US/product/niagara-footstep-vfx)
- [GOOD SKY](https://www.unrealengine.com/marketplace/en-US/product/good-sky)
- [Interface & Item Sounds Pack](https://www.unrealengine.com/marketplace/en-US/product/interface-item-sounds-pack)
- [Realistic Starter VFX Pack Vol 2](https://www.unrealengine.com/marketplace/en-US/product/realistic-starter-vfx-pack-vol)
- [Basic Pickups VFX Set (Niagara)](https://www.unrealengine.com/marketplace/en-US/product/basic-pickups-vfx-set-niagara?sessionInvalidated=true)
- [Stylized Eastern Village](https://www.unrealengine.com/marketplace/en-US/product/stylized-eastern-village)
- [Stylized Fantasy Provencal (Stylized, Fantasy, Provencal)](https://www.unrealengine.com/marketplace/en-US/product/stylized-fantasy-provencal)

Please visit the Launcher to download these assets and add them to this project manually. 

### Verification
If you own the plugins but do not have repository access, visit [Verification](https://www.n00dbeaverstudios.com/verification) to verify your ownership and gain the necessary access.

## Getting Started

The following only applies to cloning main to receive the latest and greatest, see [Releases](https://github.com/n00dbeaverstudios/n00dWorkshop/releases) to download the Binary version of this project where you can simply add the required plugins to the Plugins folder!

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

## Generate Files
Now that you've cloned the repositories, we must generate visual studio files for the project to see them. 

Right-click on n00dWorkshop.uproject and select `Generate Visual Studio Project Files`

![image](https://github.com/n00dbeaverstudios/n00dWorkshop/assets/20903421/b0409a19-1a48-4a93-abfe-5a7262da3f34)

Once this is complete, double-click the project file and you will be prompted to compile the project. Go ahead and do this, it may take a few minutes.

## Dive In!
You’re all set! Explore the capabilities of n00dWorkshop and start building your projects with enhanced flexibility and power. See you inside!
