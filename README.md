# paRAnoia

A psychedelic psychological horror(ish) game developed by Psychedelic Camel Studios for IMGD 4000 and 4500 at WPI (B-Term 2026).

## About the Game
After taking an experimental hallucinogen, Goop-X, on their night off, a college Resident Advisor (RA) is unexpectedly called to fill in to complete the nightly rounds. As the drug takes effect, the dorm building becomes surreal and ever-changing, where the line between reality and hallucination becomes indistinguishable. To make it through the night, the RA must navigate distorted hallways, solve mind-bending puzzles, and address bizarre student problems.

## Development
**Engine:** Unreal Engine 5.8(.4)
**Course:** Technical Game Development II & Artistic Game Development II - Worcester Polytechnic Institute
**Year:** 2026

## Getting Started
### Prerequisites
Before cloning the repo, install:
- Unreal Engine 5.8.4 - Make sure the whole team uses 5.8. 5.8.0 **is** compatible with 5.8.4, so dw about that on the lab computers.
- Git
- Git LFS - Found in the class discord or just look it up
- Visual Studio 2026 - Currently on the October 2026 Feature Update (18.11.2). Install the Game Development with C++ workload

### Clone the Repository
1. Enable Git LFS:
   ```git lfs install```
2. Clone the repo:
   ```git clone https://github.com/Boommook/paranoia.git```
   ```cd paranoia```
3. Verify that LFS assets have been downloaded:
   ```git lfs pull```
4. Open the project (paRAnoia.uproject) using UE 5.8

## Repository Structure
paRAnoia/
├── Config/              # Project and engine configuration
├── Content/             # Levels, Blueprints, materials, assets
├── Source/              # C++ source code
├── Plugins/             # Project-specific plugins (if needed)
├── paRAnoia.uproject    # Unreal Engine project file
├── .gitattributes       # Git LFS configuration
├── .gitignore           # Excluded generated files
└── README.md            # Hey that's this!!

## Contributing
This project is developed collaboratively by the members of Psychedelic Camel Studios.
### Branching Workflow
To keep our project stable, we should be developing on feature branches, rather than on main directly.

1. Update your local repo before starting any work:
   ```git checkout main```
   ```git pull origin main```
2. Create a branch, such as:
   ```git checkout -b [type]/[insert name]```
   Ex. branch names:
   - feature/player-movement
   - feature/post-processing
   - art/dorm-environment
   - fix/camera-collision
3. Commit your work:
   ```git add .```
   ```git commit -m "[a **useful** message describing the commit]```
4. Push to your branch
   ```git push -u origin [branch name]```
5. Open a pull request to main on GitHub.

### Git LFS
This project uses Git LFS for Unreal Engine assets and other large files

You can verify your LFS setup with:
```git lfs track``` - Displays configured tracking patterns
```git lfs ls-files``` - Displays files currently tracked by LFS

Do not remove or bypass the .gitattributes config when adding assets. The .gitattributes file tells Git which files should be managed by Git LFS instead of regular Git.

## Team
Developed by **Psychedelic Camel Studios**, a student team at WPI working to complete their respective Game Development II courses.

### Technical Team
- Cole Bennett
- Brandon Contardi
- Chloe Polit
- Berenis Tekin
- Domenic Kramer

### Art Team
- Morgan Acevedo
- Trevor Jolin

#### Studio Website
Studio Website: https://psychedelic-camel-studios-site.vercel.app/

## Liscense
This project is developed for educational purposes as part of Technical and Artistic Game Development II at Worcester Polytechnic Institute.

All rights reserved by the project contributors, unless otherwise specified.
